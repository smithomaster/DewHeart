---
layout: post
title: Finished running, plans ahead
---

I'm very pleased with the finishing of the running animation today, found in the last post here. Give it a whirl if you actually read this.

But now the time has come for me to... actually decide on what I'm going to do for the game. I know so far that there will be 40 levels. I also know that for each level, I want Jasper to be able to run down a room of decent width - I'm not sure what obstacles he'll face yet, I'm thinking crash bandicoot-style enemies. The first level will be the receptionists, so I'm thinking for the background it will just be a waiting room. I'll have the wall as a parallax background with maybe a scale of 0.75, and then have things like chairs and such in front of it at a scale of around 1, obviously I'll need to tweak it to get the feeling just right - I don't have a heap of experience, but I think the further away it is, the lower the scaling. Hopefully that will keep the background moving with the character, but the chairs and tv's and magazines as such moving closer.

I'm thinking of making a few generic walls for scenes, because being themed around a hospital, there aren't *that* many different wall types that they'll have. In each level scene, there will be a background node that encompasses the wall, any decorations the wall might have (gotta spice it up). That'll be a ParralaxBackground sprite, with a parralaxlayer node inside, with the wall sprite inside that, and also any decoration sprites. Inside the ParralaxBackground there'll also be more parralaxlayer nodes to encompass items between the main sphere of play and the wall - for example chairs and a receptionists desk in ground floor.

For enemies onscreen it'll probably be fist contact until I animate weapons and such. There will be individual scenes for each type of enemy, for example, a nurse scene. Then I will just link in more nurse scenes as nodes for multiple in each level. In addition, other static obstacles that he'll encounter will be the same - a scene made for the object, for example, a table of magazines in the reception, and just linked in where necessary. In addition, the red bull will also just be one scene (with an extern variable to change the destination scene each time).

I think for the floor I will just draw up a few different types of floor, and then just make tilemaps for each type, and use when necessary.

I'm godawful scared of all the drawing I'm going to do, and I'm definitely more nervous now than before about how I'll put it all together in Godot (especially considering I started using the software a few days ago) but I think I should be good enough at it to make this work over time.

Peace out,
your captain,
Emil.
