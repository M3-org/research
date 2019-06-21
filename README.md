# world-traversal

# Cross-linking Virtual Worlds Pt. 2


![Traveling Between](https://i.imgur.com/BXjUHDZ.jpg)

>"Instead of building one large Metaverse and splitting it into pieces, as has been done before, I looked at a different solution. How do we start with a bunch of unrelated pieces of software and combine them together to form a larger Metaverse? ... There are different authors, languages, graphics libraries, and more. If you wanted to create a way for players (avatars) to actually move between them, how could it be done? How would you move from JanusVR to Minecraft? How do you walk from Minecraft into VRChat?" - [*Traveling Between Unrelated Virtual Worlds*](https://metaversing.com/2014/05/11/travelling-between-unrelated-virtual-worlds/) by [Atari_Historian](https://www.reddit.com/user/Atari_Historian/)



> "While Iribe admits that a billion-person MMO is "going to take a bigger network than exists in the world today," he says Facebook's network makes a great place to start, and suggested it could be a Metaverse that joins disparate virtual worlds." - [Oculus wants to build a billion person MMO with Facebook](https://www.theverge.com/2014/5/5/5684236/oculus-wants-to-build-a-billion-person-mmo-with-facebook)


#### Main question

How are avatars and objects moving between virtual worlds, why is this important, and how can a more seamless metaverse might benefit the parties involved?

#### Other questions

- What are these worlds made out of?
- Who created the content we are consuming? Users? Pros?
- How easy was it for them to do it?
- What tools were they likely using?
- Were they happy with what they created?
- What kind of system powers the distribution of their creations when we join the server?


Original proposal: https://github.com/M3-org/proposals/issues/4

--- 

### What do we want to communicate between worlds?

Discuss data portability such as:

- **basic identity information**
- **real-time positional information**

We can elaborate further on data portability where possible to discuss:

- Places
- Bookmarks
- Ledgers
- Credentials
- Credit cards
- Chat logs
- Graph relationships
- Media streams

---

## The Path

Here is the route that we took on this cross-link trip, click any to scroll down fast:

:arrow_forward: [Anarchy Arcade]()
:arrow_forward: [Hubs]()
:arrow_forward: [JanusWeb]()
:arrow_forward: [Cryptovoxels]()
:arrow_forward: [Anyland]()
:leftwards_arrow_with_hook: [Cryptovoxels]()
:arrow_forward: [JanusWeb]()
:arrow_forward: [High Fidelity]()
:arrow_forward: [VRChat]()
:leftwards_arrow_with_hook: [Anarchy Arcade]()



### Anarchy Arcade >> Hubs

![AA to Hubs](https://i.imgur.com/mUA7SdK.jpg)

We started first in Anarchy Arcade, a 3D desktop / shortcut launcher, and made our way through a hallway jam packed with virtual shortcuts represented as tablets and cabinets to one that was decorated with the Hubs logo. 

![Discord login required for Hubs room](https://i.imgur.com/UGVlX8y.jpg)

Double clicking the screen opened the Hubs website in full screen, showing a button on the right that says "Launch Game".

![Launching the title pauses Anarchy Arcade](https://i.imgur.com/FsBrOmF.jpg)

After clicking Launch, the screen darkens and pauses and a new tab opens on my default web browser with the link. Because I'm already signed into discord from my browser, I'm automatically granted access into the room.

![Hubs and AA](https://i.imgur.com/x90jezC.jpg)

#### Anarchy Arcade Survey

**What is communicated between the worlds?**

The destination that we wanted to go to (server and spawn position) was communicatd from the launching app (AA) to the launched app (Hubs) which allowed us to bypass menus.

We were in Anarchy Arcade signed in with our Steam identity. The Hubs world is locked behind Discord identity system. It launches the Hubs link just like how a regular desktop shortcut would. IE. when we launch Hubs from the MSF object, our favorite trusted default web browser, which may already be signed into Discord, opens the link in a new tab.

**What are these worlds made out of?**

Anarchy Arcade is built by users spawning dynamic objects inside pre-made maps.


**Who created the content we are consuming? Users? Pros?**

It's a mix, pros create the primitives that users populate their maps with.


**How easy was it for them to do it?**

Simple as drag and drop.


**What tools were they likely using?**

In-game tools to position the objects and customize their attributes.


**Were they happy with what they created?**

Very happy since the worlds are made from the stuff they like.


**What kind of system powers the distribution of their creations when we join the server?**

JSON through the Firebase and it could also be transfered through web servers and the steam workshop. Anywhere we can transfer files.

The worlds are created and saved locally. When hosted multiplayer they are instanced to the cloud (like Firebase) where others can join and explore the content.

---

### Hubs >> JanusWeb

We are using Discords identity system, communicating over Discords voice chat, while inside Hubs and muting the in-game voice so we don't echo.

![](https://i.imgur.com/lV6lLon.jpg)

To launch the next destination, a link was posted in the chat and then spawned as a 3D object as a flat plane with a button on it.

![](https://i.imgur.com/aa02zFu.jpg)

Clicking the link then opened up JanusWeb on a new tab, keeping Hubs still open in the same browser session. The Hubs tab was optimized because it was in the background, not being rendered, but still active as a communication channel.

#### Hubs Survey

**What is communicated between the worlds?**

The destination that we wanted to go to (server and spawn position) was communicatd from the launching app (Hubs) to the launched app (JanusWeb) which allowed us to bypass menus.

When going from Hubs to JanusWeb, our identities were lost but we could spawn to a location and server within the Janus scene specified within the JML. See: [Entrance Portal](https://madjin.github.io/janus-guide/#/build/room?id=entrance-portal). 

**What are these worlds made out of?**

The environments for Hubs are created in Spoke then uploaded to be remixed. Within Hubs we can then spawn props, links, videos, and images from the web or our local hard drives which get uploaded temporarily to Mozilla's servers for 48 hours unless pinned.

**Who created the content we are consuming? Users? Pros?**

Mix of pros creating the presets and props and tooling to make it easy for regular users to spawn and populate the environments with.

**How easy was it for them to do it?**

Simple as drag and drop or spawning with a magic wand then repositioning in space.

**What tools were they likely using?**

In-game tools and editor system.

**Were they happy with what they created?**

Yes although much of the content is ephemeral and used in the process of brainstorming.

**What kind of system powers the distribution of their creations when we join the server?**

The Hubs server which is all [open source](https://github.com/mozilla/hubs).

---

### JanusWeb >> Cryptovoxels

When we spawned into JanusWeb, our identities were lost and we took the form of floating tablets.

The portal to Cryptovoxels is a [showcase](https://madjin.github.io/janus-guide/#/examples/components?id=showcase) component that featured a live websurface with a live websurface of our destination. The URL we saw running on the wall is the same that we navigated to by passing through the [teleporter](https://madjin.github.io/janus-guide/#/examples/components?id=teleporter).

![](https://i.imgur.com/cicxuFp.jpg)

It's another web to web transition but this time it replaced our active window instead of launching a new tab! Just like teleportation, the original gets destroyed when transitioning to the next dimension thus balancing the equation [(Ship of Theseus)](https://en.wikipedia.org/wiki/Teletransportation_paradox).

#### JanusWeb Survey

**What is communicated between the worlds?**

The destination that we wanted to go to (server and spawn position) was communicated from the launching app (JanusWeb) to the launched app (Cryptovoxels) via the URL parameters. We could go to any specific XYZ point within Cryptovoxels by the URL.


**What are these worlds made out of?**

JanusVR sites are made with JML which is a markup language very similar HTML which is often made using the native browser/editor Janus because of how easy it is to build.

**Who created the content we are consuming? Users? Pros?**

These worlds are typically made by users which are often modded by each other.


**How easy was it for them to do it?**

The instructions are a bit obscure right now but most often people build and export JML using the in-game editing system that Janus has.

**What tools were they likely using?**

- [Janus](https://madjin.github.io/janus-guide/#/home/install)
- [Janus Tools](https://madjin.github.io/janus-guide/#/README?id=janus-tools)
- [Vesta templates](https://vesta.janusvr.com/search/template/1)
- [JanusVR Examples](https://github.com/janusvr-examples)

**Were they happy with what they created?**

Yeah I guess.

**What kind of system powers the distribution of their creations when we join the server?**

Janus apps are basically text files containing JML which can be hosted via web servers, p2p swarms, and free hosting services like [Vesta](https://vesta.janusvr.com), [Glitch](https://glitch.com), and [Neocities](https://neocities.org).

---


### Cryptovoxels >> Anyland



### Anyland >> Cryptovoxels


---


### Cryptovoxels >> JanusWeb

We spawned in Cryptovoxels at a specific location and waited for everybody to gather before walking to the portal hub down the street.

![](https://i.imgur.com/oKklrJh.jpg)

Our group made its way through the alley between the [The Warp Bar](https://www.cryptovoxels.com/play?coords=209E,25S) and [1 Ron Road](https://www.cryptovoxels.com/play?coords=231E,8S) which contained a link to our next destination.

![](https://i.imgur.com/taAjpbj.jpg)

Standing in front of the [VRcade](https://vesta.janusvr.com/bepis/vrcade) picture we directed our attention to the hyperlink at the base which upon being clicked opened a new tab to JanusWeb.

#### Cryptovoxels Survey

**What is communicated between the worlds?**

The destination that we wanted to go to (server and spawn position) was communicatd from the launching app (Hubs) to the launched app (JanusWeb) which allowed us to bypass menus.

**What are these worlds made out of?**

Cryptovoxels parcels are made from 0.5cm parcels and users can add in their favorite art, mp3s, text, particles, and NFTs.

**Who created the content we are consuming? Users? Pros?**

The community in Cryptovoxels is mostly composed of users, many of whom do not have previous 3D modeling experience. Professional artists are swarming into the city to establish art galleries.

**How easy was it for them to do it?**

Very easy, in 24 hours a person with 0 experience making 3D content can build something incredible.

**What tools were they likely using?**

The in-game editor which is very similar to Minecraft.

**Were they happy with what they created?**

People are really happy, the feeling of ownership, self expression, and community in Cryptovoxels creates a positive network effect.

**What kind of system powers the distribution of their creations when we join the server?**

The ownership of parcels (NFTs) is decentralized and tied to ethereum wallets and the world state is saved as a giant json (about 3.7mb right now).

---

### JanusWeb >> High Fidelity

When we spawned into JanusWeb, there was a [teleporter](https://madjin.github.io/janus-guide/#/examples/components?id=teleporter) already setup in the room with the URL to open <hifi://tin-land>. 

In order to use the protocol handler in the first place, users had to run High Fidelity atleast once. Flying into the teleporter launched the world put us in a blank room in JanusWeb while High Fidelity launched.

![](https://i.imgur.com/EBO33Ge.jpg)

You can link to specific locations (XYZ) in High Fidelity with a link such as <hifi://makerbox/-39.9882,0.176166,-43.5439/0,0.995315,0,-0.0966881>.

**What is communicated between the worlds?**

We did not carry any data with us when traversing between platforms.

---

### High Fidelity >> VRChat

At this point, a lot of background applications and tabs were open (Anarchy Arcade, Hubs, JanusWeb, Cryptovoxels, JanusWeb again). There was a [web page](https://vrchat.net/home/launch?worldId=wrld_78373831-0109-4808-9b63-27382f4c6975) with a profile page of a public VRChat world that contained a launch button.

![](https://i.imgur.com/9mghR1r.jpg)

Only people with good computers were able to survive this transition because we were about to launch VRChat while High Fidelity was running, along with all the other background applications still there.

#### High Fidelity Survey

**What is communicated between the worlds?**

The destination that we wanted to go to (server and spawn position) was communicated from the launching app (High Fidelity) to the launched app (VRChat) which allowed us to bypass menus.

The VRChat world always had a default spawn position. Our steam identity was carried over from High Fidelity to VRChat as a login option.

**What are these worlds made out of?**

High Fidelity worlds are made with custom models, often using Blender, then ported into High Fidelity using their Blender plugin or in-world create tool which allows users to spawn objects. The scene is described using JSON.

**Who created the content we are consuming? Users? Pros?**

The worlds are often created by users, although there is a learning curve involved with authoring your own worlds because you have to setup your own domain.

**How easy was it for them to do it?**

It's hard.

**What tools were they likely using?**

Most often [Blender](https://www.blender.org/2-8/) is used and there is a [Blender plugin](https://github.com/Menithal/Blender-Hifi-Addon) for porting content into High Fidelity.

The in-world editor system is new and not very easy to use, although it does have a gizmo that many 3D artists are familiar with using.

**Were they happy with what they created?**

Yeah, the world's are a temple of accomplishment and self expression for the domain owners. The higher the investment, the greater the reward.

**What kind of system powers the distribution of their creations when we join the server?**

High Fidelity worlds are self-hosted on a federated network.

---


### VRChat >> Anarchy Arcade

VRChat is the final destination on the world-hopping trip and 4 people made it through to the end. This is because of the high demand of the host computer since not all of the background applications were optimized like Anarchy Arcade was.

![](https://i.imgur.com/7HLavYk.jpg)

However, we made it through a continuous path into all of the social VR capable platforms on our list! The current state of traversal between disparate virtual worlds is a bumpy ride with few applications making an effort to make it a smooth transition. 

VRChat is a dead end in terms of launching other apps but you can explore the VRChat universe by spawning portals from here into other user-generated VRC worlds.

Thus, to get back to Anarchy Arcade we alt-f4'd from VRChat.

#### VRChat Survey

**What is communicated between the worlds?**

Nothing was communicated between VRchat and Anarchy Arcade between the transition, you were either logged in steam or not so no real change.


**What are these worlds made out of?**

VRChat worlds are made in Unity then uploaded to VRChat's servers using their SDK.

**Who created the content we are consuming? Users? Pros?**

A mix of users and professionals build the maps in VRChat.

**How easy was it for them to do it?**

There's a learning curve involved with creating your scene in Unity. If one already has a scene in Unity, the simplest path to uploading to VRChat is described in [this guide](https://github.com/madjin/awesome-vrchat/blob/master/guides/worlds/basicworlds.md).

**What tools were they likely using?**

Most often Blender for modeling and Unity3D for scene creation.

**Were they happy with what they created?**

Yes because they create and can share their worlds with a large community of users on desktop and VR headsets.


**What kind of system powers the distribution of their creations when we join the server?**

The VRChat servers that users upload their worlds and avatars to are centralized but each world has a 2D web profile page that can be shared to launch the native application.


---

## Final Notes

We were communicating over Discord's voice chat the entire time.

Anarchy Arcade served as the most premium base reality we ventured to on this trip for several main reasons:

- Shortcuts were easy to launch
- Universally compatible
- Optimized heavily in the background


Shortcuts examples for each platform:

- Anarchy Arcade
  - `steam://run/266430//+join lobby81`
- Hubs
  - `https://hubs.mozilla.com/SbDZKaS/talkative-remarkable-adventure`
- JanusWeb 
  - `https://vesta.janusvr.com/bepis/vrcade`
- Cryptovoxels
  - `https://www.cryptovoxels.com/play?coords=N@214E,3U,29S`
- Anyland
  - `steam://run/505700//retrosunset`
- High Fidelity
  - `hifi://makerbox/-39.9882,0.176166,-43.5439/0,0.995315,0,-0.0966881`
- VRChat
  - `vrchat://launch?id=wrld_b51f016d-1073-4c75-930d-9f44222c7fc3`

