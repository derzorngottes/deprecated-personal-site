---
layout: post
title: Biological Code
---

The past couple of weeks I've been learning Angular and going through some C# Unity tutorials in preparation for beginning work on infinite_garden. This week we've been reviewing algorithms and data structures, and the topic of genetic algorithms came up.

I'm intensely interested in computational models of biological processes, and the question of whether a machine could experience emotions, relationships, and a sense of self-determination by using a successful neurochemical simulator. (Since we don't explicitly understand the origin/formation of human emotion and self-determination, I expect this is a distant goal.)

A few weeks ago I attended the MIT Enterprise Forum's Future of Artificial Intelligence event and had the opportunity to ask the presenters about neurological modeling. I was curious about whether AI researchers were using dopamine models to reinforce learning, and although I didn't find much on the answer I got at the event — spiking models of neurons — my research led me to reinforcement learning, a subsection of machine learning.

I'm still working through books on statistics and linear algebra, so I filed those references for now. But just reading the wikipedia overview and the abstracts for recent papers gets my mind churning with possibilities.

So far the Unity tutorial I've enjoyed the most is [Sebastian Lague](https://sebastian.itch.io/)'s [Procedural Cave Generation](
https://unity3d.com/learn/tutorials/projects/procedural-cave-generation-tutorial) which uses procedural logic and random generation to create a random cave map in Unity 3D.

The first step of the process involves using _cellular automata_, which are processes of tile population that can be used to model the skin color changes of octopi. In this case the code generates the map with a set number of tiles, each in an _on_ (walkable terrain) or _off_ (wall) state, and then fine-tunes the generation process to create organic cave shapes with varying degrees of connectivity and open space.

Eventually my collaborator and I hope to produce a project that involves several biological models, including genetic algorithms for plant life, procedural generation via cellular automata (and perhaps other integrated algorithms?) for map growth, and some kind of behavior modeling for the gardener.

Now that I'm on the lookout for biological code models I see them everywhere. Even in the the Angular $digest cycle.
