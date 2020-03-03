
# res

A repository that will act as the central location to contain any common resource that is to be shared among multiple repositories.

To elaborate, this repository will contain all the common resources that can/will be shared between multiple repositories. So, instead of adding the common resource to all the repositories or adding it to one repo and linking the other(s) to that repo, this repository will be used as the central location to contain the common resource(s) and any repository can point to the resource in here instead of having multiple copies of the same stuff in different repositories.

## Why is this repo named 'res'?

Uh, the biggest reason being that I suck at naming anything (I'm pretty sure one look at the names of my repositories will make this obvious).

Also, Android development is what brought me into programming, there is a directory named `res` (which I'm *pretty sure* is short for 'resources'), this directory contains many of the shared resources that are required at various places in the app (such as constant strings used in the app, hexes for colors used, etc).

Since I wanted to make a similar repo that will contain the common resources for the other repositories, I decided to go with the same name as the Android directory (saves me the trouble of trying to come up with a name).

## Why not directly add the common resource where required?

If the common resource is stored centrally in this repo, any changes required can be directly made to the resource in here instead of having to make the same change in any repository that contains that common resource (eliminates redundancy).

This also means that instead of having to search for repositories that have that resource, I can simply look for the resource in here without having to search through all of my repositories.

Since the other repositories will just contain a link pointing to this repo, no changes will be required in those repositories.

## I want memes.
Sure, here you go :p

![Meme](https://github.com/demon-rem/res/blob/master/memes/wSDuErTUb9PpuslVfom82SroXl.jpg?raw=true)