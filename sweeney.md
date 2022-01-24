# Tim Sweeney Metaverse

![](https://i.imgur.com/Vgd3qxD.jpg)


- Video: <https://www.youtube.com/watch?v=KBEg9riBc_U>
- Soundcloud: <https://soundcloud.com/siggraph-spotlight/30-tim-sweeney-and-the-metaverse>
- Kent Bye tweets: <https://i.imgur.com/CtlwDR2.jpg>
- Dana Cowley tweets: <https://i.imgur.com/wY53tKj.jpg>

**Speed read this transcript**
- Spreed extension: <https://chrome.google.com/webstore/detail/spreed-speed-read-the-web/ipikiaejjblmdopojhpejjmbedhlibno>
- Clean text version (for spreed): <https://hackmd.io/@XR/timsweeneyclean>
- Speed read video (13 minutes): <https://vimeo.com/373079933>

---

## Table of Contents

- [03:20](https://github.com/M3-org/research/blob/master/sweeney.md#Purpose) - Purpose
- [07:27](https://github.com/M3-org/research/blob/master/sweeney.md#Web-Standards) - Web standards
- [09:24](https://github.com/M3-org/research/blob/master/sweeney.md#File-Formats) - File Formats
- [13:57](https://github.com/M3-org/research/blob/master/sweeney.md#Identity) - Identity
- [16:42](https://github.com/M3-org/research/blob/master/sweeney.md#Networking) - Network Architecture
- [18:21](https://github.com/M3-org/research/blob/master/sweeney.md#Blockchain) - Blockchain
- [22:35](https://github.com/M3-org/research/blob/master/sweeney.md#Programming) - Programming Models
- [24:03](https://github.com/M3-org/research/blob/master/sweeney.md#Advertising) - Advertising Experiences
- [26:45](https://github.com/M3-org/research/blob/master/sweeney.md#Compatibility) - Open world compatibility
- [29:26](https://github.com/M3-org/research/blob/master/sweeney.md#Transactions) - Transactions
- [34:54](https://github.com/M3-org/research/blob/master/sweeney.md#Economy) - Virtual Economy
- [39:13](https://github.com/M3-org/research/blob/master/sweeney.md#Curation) - Curation and Moderation
- [41:47](https://github.com/M3-org/research/blob/master/sweeney.md#Empathy) - Empathy
- [43:36](https://github.com/M3-org/research/blob/master/sweeney.md#Betterverse) - The Betterverse
- [45:46](https://github.com/M3-org/research/blob/master/sweeney.md#Roadmap) - Roadmap
- [53:23](https://github.com/M3-org/research/blob/master/sweeney.md#QA) - Q&A


---

[00:09](https://youtu.be/KBEg9riBc_U?t=9)

Hello and welcome back to SIGGRAPH spotlight. I hope you're prepared for a really great talk today from an industry legend. For the first time we're bringing you a live recording from one of our sessions. Specifically the SIGGRAPH 2019 talk given by Tim Sweeney, founder and CEO of Epic Games. He'll dive deep into the metaverse and the future of creator-centric and social gaming. For a man who needs no introduction, here's Tim.


## Intro

[00:37](https://youtu.be/KBEg9riBc_U?t=37)

Thank you all for coming. It was in the early 1990s when the first fictional writing about the metaverse began, and that was an interesting environment back then. the internet had not taken off as a consumer phenomena yet, but everybody who was in a college or university setting or big corporation had access to the early version of the Internet which was you know text-based.

[01:01](https://youtu.be/KBEg9riBc_U?t=61)

At the time there were also early Silicon Graphics workstations demonstrating real-time 3d for the low low price of a quarter million dollars.

There's a growing awareness that 3d interactive experiences would be possible. You know the first VR headset had been developed on more than 15 years prior. There was a growing recognition that the technologies were falling in place to put this a medium together.

In the 30 years since, it's been a very slow process, and we've seen little leaps and bounds here and there, but we're still not anywhere near the original visions for the Metaverse. 

Some of the interesting developments have occurred lately are the advent of creator centric games, like Minecraft and Roblox where some or all of the game's content is created by the community itself and engaging in community content in these virtual worlds created by other people is the primary experience. 


[01:56](https://youtu.be/KBEg9riBc_U?t=114)

We've also seen a really interesting interplay of the real world and the virtual world with games like Pokemon go and location-based entertainment.

We've also seen the advent of social gaming as a new type of experience people have together with Fortnite. Fortnite is kind of the biggest scaled phenomena yet in this sector: 

- More than 250 million people have experienced the game
- They interact across seven different platforms
- It's a very broad audience, not all hardcore gamerz 

There is a study that showed that about 35% of Fortnite players were female which is a really impressive statistic for a game that's primarily a shooter in nature.

[02:38](https://youtu.be/KBEg9riBc_U?t=158)

We find a lot of the time when people are playing Fortnite they're spending a large fraction of their time actually just in the game lobby on voice chat with friends, emoting and just hanging out and having a good time in between play sessions. 

We're really seeing the beginning of these social experiences in a 3D world and yet what we have I don't think anybody would claim is the Metaverse. Actually nobody really knows what the Metaverse is because all of these science fiction portrayals are very interesting, but they they don't really get to the core elements of what the media is, how it works, and what what's necessary for it to succeed in a major competitive economy.

### Purpose

[03:20](https://youtu.be/KBEg9riBc_U?t=200)

The purpose of this talk is to try to say what the Metaverse is and then review the building blocks that we at Epic think are going to be necessary for the industry to build together in order to enable this medium to really take off on a new scale. 

Then I hope to leave a lot of time for questions and other viewpoints to be heard on this topic.

I started out by trying to say what the Metaverse is and my first version of the statement was **it's a real-time 3d social medium where people can engage in shared experiences together**, but that doesn't really work does it?

Doom is the Metaverse and Halo is the Metaverse, every multiplayer games the Metaverse, so that's not quite enough. 

[04:06](https://youtu.be/KBEg9riBc_U?t=246)

I think that players being able to create a large amount of the content to the world is a critical part of this new medium. 

If players can create their own stuff then the whole platform is just going to be limited to what this one central company can build and I don't see any argument or any indication that that could ever succeed of at a phenomenal level necessary for it to change the world. 

[04:30](https://youtu.be/KBEg9riBc_U?t=270)

So, I think creating is a really critical part of it but creating isn't enough because creating content costs money and creating high quality content costs a lot of money. 

The Metaverse is a platform we'll be competing with all of these other platforms and Triple A games and every other digital competitor for players times. 

I think it's also critically important that the Metaverse have an economy that's open for creators to participate in so that you can not only be a builder of content, but you can also build a business around content. Companies can have employees, that can grow and we can build an entire digital ecosystem around a degree of free-market economics. 


[05:13](https://youtu.be/KBEg9riBc_U?t=313)

Is that enough still? I think what why I described there which is a real-time 3d social medium where people can create, share, and engage in shared experiences as part of an open economy is also a potential invitation for a corporate dystopia like we have with a lot of the social media platforms now where one company sucks all the money out or most of it, and has the unilateral right to decide what can and should be seen in the thing. 

[05:42](https://youtu.be/KBEg9riBc_U?t=342)

I don't think that's enough. I think that we not only need to be participants in this economy but we need to all be equal participants - users together with all the software and technology companies that provide portions of the platform in order for it to be a really fair and competitive medium. 

So I'm talking about the Metaverse I'm really talking about the **open Metaverse** so let's try it so one more time.

**It's a real-time 3d social medium where people can create and engage in shared experience as equal participants in an economy with societal impact.** 

[06:19](https://youtu.be/KBEg9riBc_U?t=379)

If this is a small thing and it fails, then it's not the Metaverse. The Metaverse has to be a next-generation platform that's a successor to a lot of communication media that came before it and has to take off at an unprecedented scale. 

That's what I think the Metaverse is, so we're now going to try to break down the technical aspects and the principles that we need in place to actually build this thing successfully together.

[06:46](https://youtu.be/KBEg9riBc_U?t=406)

If we're going to try to build the Metaverse as an open platform then we're going to need a degree of industry standards to specify what it is, how it works, how all the participants interoperate. 

I think you can look at the history of technical standards evolving over time. The first really interesting technical standard I could find for interoperability was RFC 822, you know as the internet standards - the standard for the format of ARPA Internet text messages.

They're talking about email here, the standard was formed in 1982, it's like the dozen pages of text, very simple stuff anybody can implement. The protocol is necessary to exchange email.

### Web Standards

[07:27](https://youtu.be/KBEg9riBc_U?t=447)

Today you step forward to the web standards powering the modern web. You've a large array of actual standards, they're all bundled up together under a bunch of different industry initiatives. 

There's the World Wide Web Consortium providing the HTML standard, ECMA providing the javascript standard, a separate organization. Then there are dozens of audio and video formats and visual formats for different data types that can be conveyed by the web. 

[07:55](https://youtu.be/KBEg9riBc_U?t=475)

These standards are really diverse; you not only specify file formats they also specify protocols for exchanging data, and some fairly complex specifications of operations. 

[08:07](https://youtu.be/KBEg9riBc_U?t=487)

The web works based on the document object model Dom, which describes the top-level document of a web page and how code can interact with it, and how content is injected to it through HTML. It's sort of the 2d web browser equivalent of a 3d scene graph that we experience in a modern game. 

Also powering the web or a lot of other related standards used on the backend side, server-to-server and server-to-service, such as JSON and XML and WebRTC. 

It will be actually a hard project to find all of the standards governing the web and to collect them together. I imagine you'd need dozens of standards, and they'd span tens of thousands of pages to understand it all. 

[08:52](https://youtu.be/KBEg9riBc_U?t=532)

There's a growth in complexity and I can only imagine the future 3d standards will have to be significantly more complex than this, because what 3d engines do is far far beyond what web does. If you look at the variety of ways that game objects interoperate, there's a huge huge surface area there that would need to be specified. 

It doesn't all need to happen at once right? As with the web standards we can break down all of the components needed for 3D scene formats and related data by category and decompose at all.

### File Formats

[09:24](https://youtu.be/KBEg9riBc_U?t=564)

The good news is there are actually quite a lot of standards that are candidates for powering an open Metaverse. For example, there's the Pixar USD universal scene description format which does a pretty good job of describing scene graphs. There is the MDL material description language and material X shading graph language which described their operation of shaders for physically based realistic materials. Then there are formats like glTF for describing geometry, intensive geometry, and 3d objects of all sorts. 

[09:56](https://youtu.be/KBEg9riBc_U?t=596)

We're lacking standards a lot of areas or we have very early formative standards that haven't really taken hold yet. There are standards for a character animation, faces, particle systems, for describing the physics of objects that can interact together, and for describing how live servers and clients interact together using real-time network streams because we're presuming you're not sending everybody the entire scene graph every time something changes but you have to have optimized protocols to make all these things really efficient.

[10:27](https://youtu.be/KBEg9riBc_U?t=627)

You need standards for objects: How does code interact with the scene graph to make interesting things happen in a dynamic world? How does audio work in this environment? It's not just sound file, it's also 3D geospatial location and physical interactions and interface user interface components on top of that because this future 3D medium will also have forms of 2D interaction in it. 

[10:51](https://youtu.be/KBEg9riBc_U?t=651)

So we're going to need dozens of different file formats of which many exist. The constant challenge over the next few decades is going to be filling in all of these gaps over time. We're going to need to fill in these gaps and then iterate and constantly improve things. 

It really took about five iterations before HTML really hit a sweet spot where it's a completely functional language for powering webpages.

If we look around at the whole spectrum file formats it's really quite a mess right now. Most standard file formats are layered on top of one of two standards, either JSON you know JavaScript object notation or XML, and these file formats actually don't solve the core problem of a file format which is to convey data and information about any topic losslessly from any computer to any other computer.

[11:40](https://youtu.be/KBEg9riBc_U?t=700)

If you look at like glTF and all of these other JSON based file formats what they really do is they specify, "like okay the key name for this data type is vertex and the value is a bunch of floating-point numbers separated by commas."

So really saying is like here's a file format for bundling up sub file formats together in a really messy way. 

I think there's a real opportunity for a simpler and more definitive file format for any data type that could conceivably exist in any system can describe that data in a way that can always be conveyed from one end to the other without the need for any interpretation, or any schema, and without any sort of loss. 

[12:24](https://youtu.be/KBEg9riBc_U?t=744)

Right? JSON is a good example, it supports two data types: strings and double-precision floating-point numbers, but it's missing a huge set of of data types that you would need to convey any realistic data that would exist in a in a complex environment. 

So over time it will be great if we could take the existing file formats there based on these crappy low-level file formats and rebase them in a more rigorous way on top of a new kind of carrier file format so that USD and MDL and glTF and others could cut it into a more uniform framework for describing describing the data they contain. 

[13:03](https://youtu.be/KBEg9riBc_U?t=783)

That might sound a little bit pedantic when talking about specific file formats because after all you write the importer once and you're done, and you never have to touch it again. However, file format issues really come to the forefront when you're talking about a Metaverse consisting of huge sets of user-created objects powered by user created scripts each defining huge quantities of data that they will can contain and data types that define new containers of data.

[13:29](https://youtu.be/KBEg9riBc_U?t=809)

What we need it's not just a file format for specific types of data that we lay out in advance but also file formats for any type of data that any programmer might write in one of these programs. 

This is because in the open Metaverse you expect these objects be able to move around between servers and interact and be conveyable losslessly even between software products written using different code bases and different engines or so on. 


### Identity


[13:57](https://youtu.be/KBEg9riBc_U?t=837)

Next there's a set of technical standards that are needed not for representing the world but for representing participants in the world.

Here we'll need standards for identity of people, for communication between people (voice communication, text communication, video streaming), and also social interactions and social relationships between people such as social graphs. 

[14:20](https://youtu.be/KBEg9riBc_U?t=860)

There are some really interesting web standards that already exist and already widely deployed now along these lines like oauth, a good standard for identity and authentication. 

In the federated environment we have many different authentication for writers who can all interoperate and respect each other's users. You also have a really good standard for communications with WebRTC


[14:42](https://youtu.be/KBEg9riBc_U?t=882)

Epics build up a lot of experience with these topics lately and implementing Fortnight cross-platform play and cross-platform item ownership across all seven platforms. 

Fortnite was kind of the first game that runs on Windows/Mac/iOS/Android/Xbox/Playstation and Nintendo switch and now supports game play with players in all these platforms together in a single game play session.

We actually built these systems by supporting Playstation login on Epic's account system and Xbox logon plus all these other different components.

[15:17](https://youtu.be/KBEg9riBc_U?t=917)

I think if we look around we find we already have in place most of the infrastructure we need for federated identity across many different ecosystems. That's a great starting point for a shared open Metaverse anybody can participate in.

However, we need more standards. There's a no workable standard for social graphs right now. There was an OpenSocial standard that was proposed that never gained traction because I guess Facebook and the Instagram and everybody else found it was more profitable if they didn't open their social graphs up to other people.

[15:47](https://youtu.be/KBEg9riBc_U?t=947)

We need to develop a bunch of new standards also need standards for ownership of digital objects if we want to create an economy around this future Metaverse. That means the ability for creators to create things, for them to sell the things to users, for users to be able to prove and establish that they own things, wherever they go, whatever server they're on, and whoever they communicate with. 

We will also need some sorts of standards for appearance, right? Because the key point about the Metaverse is it cannot just be another App Store, right? 

We already have app stores, they already sell 3D games, and I think the unique element that's going to make this an engaging medium for everybody is the fact that you can carry your image, yourself, your persona, and your avatar across different entertainment experiences as you go around these shared worlds.  We'll need first-class ways of treating all that. 

### Networking

[16:42](https://youtu.be/KBEg9riBc_U?t=1002)

We're also going to need to decide on some sort of network architecture for the system to work. 

If we look at how games work today and how all of these shared entertainment experiences work, they're essentially client-server applications. 

A client is distinguished from a server, it's transient, it's not necessarily trusted, it might be on a device that's hacked, they might be trying to cheat. 

The client is kind of a single autonomous machine representing an owner in the whole system. 

Servers are trusted authoritative decision-makers about interactions in the world. 

[17:19](https://youtu.be/KBEg9riBc_U?t=1039)

That works for Fortnite: up to 100 players and when you have 10 million concurrent Fortnite players you have a hundred thousand Fortnite servers running around the world hosting them all, but I don't think that that's enough for a future medium as the Metaverse fiction suggests should exist.

I think what you really want is one single huge shared world everybody can participate in seamlessly. This is obviously going to be something that cannot run on a single server or even a single data center, but will require massive massive numbers of servers all over the world to host.

[17:51](https://youtu.be/KBEg9riBc_U?t=1071)

There needs to be standards for client to server communication and server to server communication. We need to make a big architectural decision about the the model in which servers work together.

There are two major possibilities: one is a Federation model where a bunch of trusted companies and service providers agree to link their systems together so that all of their servers can interoperate. 

Email is the perfect example of that: tens of thousands of companies link their email servers together.

### Blockchain

[18:21](https://youtu.be/KBEg9riBc_U?t=https://youtu.be/KBEg9riBc_U?t=1101)

The other alternative is a decentralized model where something like the blockchain centrally ensures that anybody can participate, anybody can add their hardware power to the overall network that's computing the evolution of this game world. 


These decentralized participants in the network don't need to be trusted because the network protocols and the economy itself ensure that everybody operates honestly.

[18:49](https://youtu.be/KBEg9riBc_U?t=1129)

There's a suggestion the Metaverse could be powered by the blockchain. I think it's really important to recognize that this could be a really fundamental part of all computing in the long-term future. 

I think it's easy to for this to be obscured by hype around Bitcoin and all these other cryptocurrencies. A lot of it is financial hucksterism, a lot of it is scams, and the focus is way too much on money. 

[19:14](https://youtu.be/KBEg9riBc_U?t=1154)

The existence of these currency tokens as money is almost a coincidence to the underlying fact of the existence of this blockchain. 

What the blockchain is, it's a decentralized network for processing transactions, for determining ownership of items, for data storage, and compute power. 

There's an economic model that incentivizes everybody to contribute the computing power to this shared cloud of decentralized computers. 

There's also an economic model based on game theory that incentivizes everybody to be honest and to conduct transactions fairly and so heavily punishes dishonest transactions that everybody has a clear economic incentive to operate honestly. This is this is how the Bitcoin blockchain implements trust.

[20:04](https://youtu.be/KBEg9riBc_U?t=1204)

It's a whole lot of machines competing to compute hashes, but the underlying protocol guarantee is that as long as the majority participants in the network are acting honestly a dishonest participant cannot take over, hijack, introduce corrupt or untrusted computations in the blockchain.

That's done in two ways:

1. This blockchain protocol itself ensures that the blockchain only accumulates the best and longest amount of further computations and transactions that can be created 

2. Also by ensuring that every transaction that's recognized on the blockchain is actually signed by the owners of some current currency and transferring currency to somebody else

We can completely divorce this topic from money because what we could easily be talking about are virtual goods, ownership of items, real estate, data storage, or anything else.

[20:57](https://youtu.be/KBEg9riBc_U?t=1257)

I think there is a real possibility of blockchain implementation eventually being a practical solution for this, but there is a huge huge gap between current state of the art and what would be needed for a real-time game or Metaverse experience.


The blockchain works at one update every 10 minutes, game servers like in Fortnite and Call of Duty support one update every one thirtieth of a second. So we're off by orders of magnitude in performance and there are also significant single-threaded bottlenecks and these blockchain implementations.

[21:34](https://youtu.be/KBEg9riBc_U?t=1294)

If we were ever to look to a blockchain solution for this we're going to need something radically different than anything that exists now.

It will need a lot of parallel computation bandwidth where there cannot just be a single evolving global transaction state which everybody has to synchronize with. The speed of light ensures that that cannot possibly work for a real-time communication medium.

[21:55](https://youtu.be/KBEg9riBc_U?t=1315)

This is a big open question, but I think it can be answered by Federation now and decentralization later. 

We're already seeing increased interconnectivity between all of the gaming ecosystems. You know, good old games introduced a game store that's now supports purchases on Steam and other stores. We're seeing more and more integration where games are supporting players across all platforms and platforms themselves are recognizing players from other platforms.

We're going to have to watch that space closely but I certainly feel like there's the necessary technical infrastructure in place now that you could build this and you wouldn't find co-operation between servers to be a practical issue. 

### Programming

[22:35](https://youtu.be/KBEg9riBc_U?t=1355)

The next question is about programming model, because if we want to have this huge shared experience with many different types of games, other entertainment experiences, or any sort of experience at all, what you're talking about is a huge amount of user-generated content in the form of 3D assets and also a huge amount of user written code - perhaps an unprecedented amount of user written code. 

[23:00](https://youtu.be/KBEg9riBc_U?t=1380)

There's already some evidence of models like this working: I think the web with JavaScript is sort of a microcosm of this. 

Now the web is a much simpler programming model than the Metaverse will have to be because on a website all of the code that's running in JavaScript on that site is nominally under the control of the website operator. You can decide exactly what code runs and you don't ever have to deal with random user code being injected that might interact with you.

[23:28](https://youtu.be/KBEg9riBc_U?t=1408)

The web uses the closed world programming model, whereas the Metaverse will need to be an open world programming model because the goal is it can't just be another App Store, right? You can't have a thousand different experiences, and you can be in one at a time, and when you're in that one experience it dictates everything.

The Metaverse has got to be about interoperability of user created objects of all different types, right? Because besides having some core game experiences in the sort of place you're also going to have the equivalent of Facebook pages for every object that exists in the physical world.

### Advertising

[24:03](https://youtu.be/KBEg9riBc_U?t=1443)

Say Ford creates a new car and they're going to want to unveil the car as a user drivable object in this virtual world. That's going to be really interesting and more powerful way to unveil a car than to just announce it on your Facebook page. The Facebook page can have text and video, but in the virtual world you can:

- Actually get in the car
- Go around it
- Look at it from all different angles
- Open the doors
- Drive it you
- See how it handles
- Have a huge set of interactions that are much more interesting and organic as it's not just an advertisement for a product but also something that you can experience and have fun with. 

[24:45](https://youtu.be/KBEg9riBc_U?t=1485)

I think we need to look at all of the crossovers that have occurred in recent years between games and other brands as kind of an indicator of where the Metaverse will go. 

These are not just like cheap advertising deals. If you look at Fortnite for example, the musician Marshmellow held a concert in the virtual world of Fortnite. It's a really amazing experience that introduced a huge set of new people to his music and brought a lot of marshmallow fans into the game. It was a real crossover that it was not commercial and too intense at all. It was an incredibly fun event for everybody who participated. 

You also saw Marvel's Infinity War movie appeared in Fortnite as a mode and Fortnite appeared in the movie. 

[25:30](https://youtu.be/KBEg9riBc_U?t=1530)

A few years ago Epic partnered with McLaren to build a digital version of their car. The purpose of that project was to see if we could recreate completely realistic carbon fiber, an isotropic paint, and other workings from a billion polygons model that was used to CAD model the original car.

The modeling project succeeded, but then a few years later, very recently, McLaren car showed up in Rocket League as a drivable car you can play the game with. That was incredibly interesting to see, I think this is going to be the future of this shared 3D entertainment medium. 

[26:06](https://youtu.be/KBEg9riBc_U?t=1566)

It's not about Facebook pages, it's not about advertising, it's about actually delivering meaningful experiences that people can interact with and that become part of this much larger world.

The programming model for the Metaverse must incorporate the assumption that everybody's on objects that they build should be able to interact sensibly and safely with everybody else's objects.

[26:29](https://youtu.be/KBEg9riBc_U?t=1589)

Your car built by Ford should be able to interact with your motorcycle built by Ducati. If an architect to be is a major work of architecture in the Metaverse that should work with all the different player models have been introduced into the game, and everything should work together.

### Compatibility

[26:45](https://youtu.be/KBEg9riBc_U?t=1605)

I think the focus of any programming model for the Metaverse needs to be open world compatibility over time. Open interfaces, which can evolve, would be extended over time.

If you look at Java and C sharp they've done a remarkably thorough job of pursuing this direction and it's largely been under exploited, but if you look under the covers and compare what these languages have done to C++ just from extreme intelligence and the backwards compatibility rules they've introduced into the languages. 

If you release one version of a module with an interface you specify (and that interface is a set of classes and member functions and variables) then there's a guaranteed set of rules where you can add new members to your class, you can add new variable, add new functions, if you have a constant you can narrow the type of the constant, if you have a function you can add new optional parameters without breaking compatibility with existing users of the class.

[27:47](https://youtu.be/KBEg9riBc_U?t=1667)

I think we have to realize that the Metaverse isn't going to evolve through one Standards Committee specifying how the entire world is supposed to work.

The Metaverse is going to evolve as a lot of independent creators each creating their own modules with their own interfaces. Your game object might be a car, your car might suppose a bunch of physical points of interaction to a user like door handles that you can open, and indicators to say you can sit in this here, you can drive this car this way, indications for the users. 

[28:18](https://youtu.be/KBEg9riBc_U?t=1698)

It can also expose a programming language interface for programmers to interface with which enable other objects to interact with the car, to understand what it is, and how to interact with it. 

This is going to have to be the central point of any programming language - to really be designed with modular open world evolution as the first-class design consideration in order for it to just not fall apart as so many other software frameworks have over time.

### Transactions

[28:47](https://youtu.be/KBEg9riBc_U?t=1727)

The other essential element for the Metaverse is if we want to scale beyond just a few hundred players in a shard and separate disconnected worlds, I think what we really want is one shared world everybody can participate in that's completely seamless.


That means that any sort of programming language needs to scale to be unlimited in size. It needs to support interaction with an outside world that is much larger than can be held in any one server computer or any one data center.

You know that that has really profound programming model implications. It's not just going to be single threaded C++ code anymore running locally.

[29:26](https://youtu.be/KBEg9riBc_U?t=1766)

There are several competing ideas for that: one idea is message passing concurrency as Erlang and other languages define. I think you could look at JSON over HTTP is one way of delivering this sort of message passing concurrency.

[29:42](https://youtu.be/KBEg9riBc_U?t=1782)

The challenge with that is every interaction between objects requires negotiating to be consistent on both ends. If you have two different objects on two different servers, they send each other a bunch of messages. 

For example, I'm trying to trade you an object for money, then on my side for the economy to work I had better be able to spend money and guarantee that either you get my money and I get the object you offered or nothing happened at all.

[30:12](https://youtu.be/KBEg9riBc_U?t=1812)

It can't be like, you got my money but the other message was lost in the network and so I didn't get my object or you got I got the object and you get the money.

I think what we're really talking about here is the challenge for any sort of large-scale concurrency is implementing safe transactions. 

A transaction is an atomic operation that modifies state in a number of different places and occurs atomically. Nothing occurs during their point of view of observables in the system and nothing occurs in between it can inspect intermediate state. 

[30:50](https://youtu.be/KBEg9riBc_U?t=1850)

A transaction has to be atomic, isolated, durable, and consistent. Isolated and that nobody sees temporary intermediate states during a transaction.

Consistent in that everybody in the world sees that the transaction occurred or didn't occur and nobody sees a conflicting view of that. 

Endurable in that once the transaction is completed we better be able to count on that, because we might conduct subsequent transactions that are dependent on it. 

[31:17](https://youtu.be/KBEg9riBc_U?t=1877)

So I think what we really need for this Metaverse to work and not fall apart with data race conditions is some sort of transaction model it scales up to world scale and currency, and that's really interesting.

You know there's been a lot of research on software transactional memory as a small scale solution to running a lot of threads and being able to update shared state without data race conditions at all.

Intel's CPUs now have transactional memory extensions (tsx) to facilitate a little bit of this. 

[31:47](https://youtu.be/KBEg9riBc_U?t=1907)

I think what you need is a much higher level protocol for negotiating transactions involving sets of objects across multiple servers.

Actually this is what the blockchain does at a much slower frame rate. The Ethereum blockchain or the Bitcoin blockchain does nothing but process transactions and guarantee they meet that acid guarantee: atomic, consistent, isolated, and durable.

[32:10](https://youtu.be/KBEg9riBc_U?t=1930)

This is a big problem that we're going to have to tackle if we want to write this system and we want it to work as an economy and we want to work reliably.

Those are kind of the core requirements for the programming environment. Notice all along I didn't say programming language, because it's not clear if we needed no programming language, though a programming language might be a desirable way to specify this.

I think the lowest common denominator solution is a set of network protocols for negotiating all transactional interactions between servers in this Metaverse, right?

If you specify that then anybody can implement however they want as long as they followed the protocol. Then the system can evolve, the game state can or world state can develop consistently, and everything works fine.

[32:59](https://youtu.be/KBEg9riBc_U?t=1979)

To actually make that work I think you had at least need a software library on every side which implements a framework ensures it's easy to write code to this Metaverse later.

[33:08](https://youtu.be/KBEg9riBc_U?t=1988)

I envisioned a potential layering: at the top level we have a network protocol which standardizes transactions, data formats for describing objects and their properties, a really solid robust file format standard, and network protocol at a lower level you need a language library which could run in C++ or Python or Java or C sharp or any language which exposes really nice kind of intermediate programmer level friendly operations for interacting in this Metaverse so it's not just a bunch of low-level bit manipulation operations but a real rigorous library where if you follow the library according to the spec and everything works safely.

[33:49](https://youtu.be/KBEg9riBc_U?t=2029)

I think that the highest level layer in this platform could then be a scripting language which is a programming environment where if the compiler doesn't beep then your code is guaranteed to be safe. Meaning it can run anywhere, it's sandbox, can't craft memory, it can't steal private state, or violate security principles, and it can't break the transactional guarantees of the system.

If we added something like that whether it looks like Python or JavaScript or Lua or c-sharp those are all possibilities but I think that's the correct layering because in this software framework we have to acknowledge that the big heavy metal software here is going to be written in C++.

[34:30](https://youtu.be/KBEg9riBc_U?t=2070)

It's either going to be a game engine, or the future equivalent of a web browser engine for the Metaverse which i think would look a lot like a game engine does today, but you're going to have a lot of C++ code written in it and if there is a scripting environment then it's not going to be a new thing that takes over our entire computers - it's going to be an abstraction layer in a higher-level system that's written in a native language.

### Economy

[34:54](https://youtu.be/KBEg9riBc_U?t=2094)

Next I want to talk a little bit about the economy because the core thesis here is that to have a successful Metaverse you need an economy where creators can make money from their work so you have incentives continue to create stuff and you have a really thriving economy.

I think it's essential for success because if the Metaverse doesn't enable creators to make money, then they're probably going to go create games instead and the Metaverse will be replaced with a bunch of proprietary apps that actually do get the economy right.

[35:24](https://youtu.be/KBEg9riBc_U?t=2124)

Economy is the way of matching up buyers and sellers of items and creating discoverability mechanisms for transparency and also an environment where a level of trust exists where you know if you go to buy something you actually receive it and it actually works.

It's a bunch of layer of different components. I think financial transactions are actually the easiest part of all of this. The the higher-level issues involved in establishing trust and fairness in an economy is much harder. 

[35:56](https://youtu.be/KBEg9riBc_U?t=2156)

I think we're going to have to expect a rich and evolving set of economic models to work in this universe.

The AppStore model is you buy an app, you receive it or you buy an app, and then you conduct micro-transactions in it. In every case you're paying money to get a specific thing at a specific point in time.

That works for somethings like buying a Fortnite outfit - there's a successful business around that, some games have established it.

[36:20](https://youtu.be/KBEg9riBc_U?t=2180)

Not every item in the world that's valuable to consumers has a means of selling it, right?

If there's a beautiful building out in the Metaverse everybody loves and enjoys and goes to, for that to be an economic success you couldn't charge for access to it necessarily. 

You might need to have ancillary ways of earning revenue from related economic activity associated with it.

[36:50](https://youtu.be/KBEg9riBc_U?t=2210)

I think if we look at the modern digital economy, we see a lot of dysfunction in these advertising business models and privacy invading business models, which I thoroughly reject. 

We have to we have to look and recognize that there's a lot of value in ways of enabling monetization of content other than through paying money directly for it.

[37:12](https://youtu.be/KBEg9riBc_U?t=2232)

YouTube monetizes through annoying ads. Netflix has a more interesting model: they charge a subscription price and then the creators who put their content on Netflix usually negotiate some deal up front but they're also paid typically a percentage of the revenue from this subscription service based on their play time or the percentage of play time in the system that goes into their movie as opposed to everybody else's. 

[37:39](https://youtu.be/KBEg9riBc_U?t=2259)

Fortnite has nurtured a similar economy with its supporter creator program where when you go to buy an outfit in Fortnite you can say what streamer you're watching or what creator you want to support and part of the proceeds from that outfit goes to the creator.

I think these are just the tip of the iceberg of indirect economic models where people can make money for participating in the economic activity around it without ever charging a gate price.

[38:04](https://youtu.be/KBEg9riBc_U?t=2284)

Trust in an economy is essential and so I think we have to be skeptical of a fully decentralized economy where anybody can do anything and everybody's anonymous and there's no recourse.

You know all the successful economies have a very high degree of trust that you're going to get what you're paying for and it will work. 

[38:23](https://youtu.be/KBEg9riBc_U?t=2303)

There needs to be some sort of really active governments around all commerce and this sort of environment system for recognising reputations of sellers and qualities of items and all of these things and it's going to be a real can of worms.

If you look at Amazon which is the largest e-commerce platform in the world, Amazon Trust is built through reviews and you can buy high quality reviews for your product. It's a frequent case so there's a never-ending game of cat and mouse around shutting down fake reviews.

[38:55](https://youtu.be/KBEg9riBc_U?t=2335)

There are also services that will hurt your reviews that your competitors can use to hurt your products and send some business to them. There's a whole sham economy around that needs to be managed and I think this is going to be a first-class issue in the birth of any new digital platform and the more decentralized it is the more of a challenge it's going to be for us.

### Curation

[39:13](https://youtu.be/KBEg9riBc_U?t=2353)

I also wanted to talk about some of the challenges around curation and moderation because in a user-generated content ecosystem there's going to be all sorts of bad things being created.

There's going to be pornography, there's going to be abusive content, there's going to be trolls, and I think today's social network really is a clear warning to all of us about the dangers of future social platforms.

I think we need to be very aware of the things that have gone terribly wrong with existing social platforms as we think about what a Metaverse should be when it grows up.

I think that there are problems because there's so much partisan rhetoric on these social platforms, I think the real causes of the problems tend to be obscured, but there are enormous problems with trolls, and bullies, and astroturfers, and fake news. 

We have to acknowledge it doesn't exist just because a lot of people are bad - it's just because there are these algorithms that drive curation in the system are driven by engagement.

[40:19](https://youtu.be/KBEg9riBc_U?t=2419)

Engagement can be positive and engagement can be negative. Unfortunately for humans, a lot of the things that are most engaging in an impersonal, text-based, social environment are negative things.

I really believe that the problems that we see in today's social networks are not a defect of the idea of social communications in itself. I believe they are a defect of the specific curation medium and the way that bad content can magnify and outgrow good content through this this economic model that they've devised here. 

[40:55](https://youtu.be/KBEg9riBc_U?t=2455)

Let's remember that these platforms curate content to maximize engagement. So basically, tweet that gets more likes or retweets or responses, even if the responses are negative, is curated higher than tweets that get less interaction.

[41:10](https://youtu.be/KBEg9riBc_U?t=2470)

They do that for money, right? They do that because the more time you engage on the platform, the more ads you can see, the more money they can make.

It's all financially driven and when you pay somebody money to do something, they're really motivated to do it.

When we're paying when we're paying Facebook, Instagram, and Google money in the form of our eyeballs translating to advertising dollars to display crap that offends us - well they're going to do it. We shouldn't be surprised by it, but what we should do is we should think about designing platforms that don't fall victim to this set of problems.

### Empathy

[41:47](https://youtu.be/KBEg9riBc_U?t=2507)

There's some really great news here. I couldn't be more pleased with the situation in Fortnite. Fortnite is the most positive social experience I've ever interacted with.

It's true that there are negative people out there sometimes, but the far majority of encounters are positive. Also the far majority of social engagement on Fortnite isn't with random strangers - it's not many-to-many with millions of people participating. It's players together with their friends, talking with their friends, kind of as an isolated group wandering through a much larger outside world.

A lot of the decisions we made in the game have really contributed to the positivity here.

[42:25](https://youtu.be/KBEg9riBc_U?t=2545)

One is that we have voice chat so you can chat with your friends, but voice chat only works with people in your squad that either you're explicitly friends with and you explicitly joined up with, or your friends explicitly joined up with.

The social communication in this environment has led to a much more positive and empathetic place.

Voice carries much much higher empathetic bandwidth than text. The tone of somebody voice carries a huge amount of subtlety about their thought and their state of mind.

[42:56](https://youtu.be/KBEg9riBc_U?t=2576)

We really are innately trained to, in ordinary circumstances, respect people when we're interacting with them personally far far more than when we're interacting with them with text.

[43:05](https://youtu.be/KBEg9riBc_U?t=2585)

I think this is an area where the Metaverse will have a major advantage over all other social media. It's that inherently by being focused on small groups and actual friends engaging in a much larger outside world, and in carrying all of the emotional content of voice and perhaps even facial capture in the future will be a much higher empathy platform that's much less subject to abuse where one nasty action affects millions of people because of curation.

### Betterverse

[43:36](https://youtu.be/KBEg9riBc_U?t=2616)

I think we have a lot of positive things to be excited about there, but the key challenge for this new medium is that to succeed anything that calls itself the Metaverse must actually be better than all other experiences competing for people's digital time.

That's a massive challenge. This means an hour on the Metaverse needs to be better than an hour on Facebook, or Instagram, or an hour on YouTube, or an hour on Netflix. It needs to be better than an hour in Fortnite, or an hour in minecraft, or an hour in Roblox, or GTA, or any of the world's best games.

[44:15](https://youtu.be/KBEg9riBc_U?t=2655)

It's going to carry a very high bar. It's a high technological bar, a high quality bar, a high content availability bar, and that's going to be a big challenge.

When you have a user created content ecosystem a lot of users create a lot of content and a lot of it is just really bad.  You have to have great curation mechanisms for surfacing the best stuff.

You have to have highly competitive technology and foundations for building experiences that are as compelling as Triple A games. You have to have really compelling integrations with people's daily lives.

[44:47](https://youtu.be/KBEg9riBc_U?t=2687)

I think you have to have a platform where every brand decides, "I'm going to put my product here!"

On Facebook that means we're going to advertise a new Ford Escape on our Facebook page and we're going to pay a bunch of money to reach a bunch of users with this video ad.

I think in the Metaverse it'll be much more interesting. It will be actual interactive objects, actual experiences, and actual engaging things, and not just ads forced upon.

[45:17](https://youtu.be/KBEg9riBc_U?t=2717)

I think we can completely escape an advertising based business model if we take this approach that the only way you ever get to see a commercial thing is if you decide to see it yourself because it's really cool.

I think we'll see a whole new level of competition among brands to surface really awesome 3D content.

I think you can look to Fornite and some of these other games is pioneering a lot of these really exciting engaging non-advertising based mechanisms for exposing stuff. 

### Roadmap

[45:46](https://youtu.be/KBEg9riBc_U?t=2746)

It's that quality bar that I think limits the possibilities for the Metaverse. I have a feeling that if we built a spec for this thing, and we got a thousand experts together for three years, and we roll it all out, and we build really great documents for standards, and then we built the software, players might not come. They might just find that it sucks.

They might find that other games are more experienced. They might find it never gains a critical mass needed for success.

I think we have to be very cognizant in the entertainment experience. **Failure is forever.** Once a brand, a new platform, or experience is rejected it tends not to come back.

[46:29](https://youtu.be/KBEg9riBc_U?t=2789)

I think that we're going to have to evolve from where we are to the Metaverse with what we have by going from success to success; taking the existing engines that we have today, and existing games we have today, and future ones we build, and driving them more and more that in the direction of the Metaverse by integrating more features across platforms, across ecosystems, and across game experiences.

We're going to have to do a little bit more of this every month and every year until we finally get there because I think the barriers to success and launching a completely new platform with nothing are just so immense and it's so unlikely for standards-based solution to win out.

[47:14](https://youtu.be/KBEg9riBc_U?t=2834)

I think we're going to have to gradually adopt standards in existing software, but I don't know that might sound like bad news but I think it's very exciting because it means we're much closer to the start of an open Metaverse then we would be if we had to begin negotiating standards right now.

We already have a lot of the standards we need for file formats - or at least version one or two of them and by Version three or four they might be there.

We need to continue to iterate on these standards for scene descriptions, material descriptions, animation, networking protocols, and real-time game communication until we get to something that's ready to open up to a large scale. We can do that right now in live products.

Epic is conscientiously making an effort to do this and everything we do. For example, we're moving to a webRTC based voice-comms framework in Fortnite for voice, text, and video chat so that we can start integrating with other services, other platforms, other stores, other ecosystems, other chat clients, and have shared social experiences across different game clients.

[48:18](https://youtu.be/KBEg9riBc_U?t=2898)

We already have some standards for identity and authentication, we can expand them from there with new standards for friends and connectivity.

Right now most of the major engines (unreal / unity / Godot) support most of the major interchange formats like Pixar's USD format and will support more and more over time as interchange formats we can import.

[48:40](https://youtu.be/KBEg9riBc_U?t=2920)

That's just the first step. I think the next really interesting step is that we need to start supporting these file formats as our primary format.

It's only going to be in the Metaverse when anybody can load the content as it exists on the server and that means moving away from proprietary Unreal binary files, Unity package files, to the actual file formats.

That means further iteration on the file formats to make them load efficiently enough and contain and all the features needed by all the engines to make it work. We can do this and it doesn't have to be one big step, we can do a little bit more of it every month until we get there a few years from now.

[49:17](https://youtu.be/KBEg9riBc_U?t=2957)

Also needs standards for these networking protocols and we'll need agreements between companies so that you can start integrating on a much larger scale. For example, if Fortnite and Minecraft happened to agree that we're going to support each other's avatar formats, and you could have Minecraft avatars in Fortnite and Fortnite avatars in minecraft, and we had agreed to integrate our account systems and our voice and text communication systems, then what could you do?

Then as a Fortnite player you've gone to Minecraft and continued identity and stay in contact with your friends and even though you're switching between different applications, you're still a single persistent identity of yourself going from place to place.

[50:04](https://youtu.be/KBEg9riBc_U?t=3004)

As a next step beyond that, if we agreed on file formats for worlds and for digital scenes and for physics interactions in scenes, and perhaps some degree of gameplay object scripting, then perhaps you can actually be in Fortnite and go on to a Minecraft server and be in a Minecraft world and while you're in Minecraft go into a Fortnite level and be in a Fortnite world.

I think in those cases now we have a Minecraft server which is still a distinct piece of software, and a Fortnite server which is running Unreal engine, is totally different than that, but if they have agreement on the networking protocol and at least the client-side components of scripting then you should be able to connect to a server and if it says this object is here and it's model is that model then you can render it and you can communicate and coordinate those objects in real time.

[50:51](https://youtu.be/KBEg9riBc_U?t=3051)

I think without agreeing on standardizing everything all at once we can make great strides towards this and I think the final one most interesting component of this is if we eventually agree on a programming language standard of some sort or at least a library standard of some sort, then you could have the ability to write game object that would run in any engine, or any Metaverse server framework, or any future client for this, then have a completely standards-based ecosystem.

[51:22](https://youtu.be/KBEg9riBc_U?t=3082)

I think it's important to identify that this will be very different from a bunch of games in an app store in that it's a single seamless experience, you never have to download a new program, you never need to sign up for a new account, you never need to change characters. It's you, and your persistent avatar and identity, as you traverse through this entire world. You can bring any of your friends with you anywhere you go in this entire time.

I think these entertainment experiences will be hugely varied. There's an anecdote, right? We recognize this when you're looking at how people were playing Fortnite. A bunch of guys can't get together for a night and just sit on a couch and talk, like for some reason everybody thinks "oh that's gay you can't do it", but what you can do is get together and play billiards all night with a bunch of guys and that's totally cool. Or you can shoot hoops or you can play Fortnite and that brings the fundamental realization that all of these social experiences needed some sort of actual activities to drive the conversation, right?

[52:22](https://youtu.be/KBEg9riBc_U?t=3142)

You know when you run out of things to talk about in billiards you start talking about the game, and then when you run out of things in Fortnite you're talking about the game, and you're going in and out of personal life conversations and game conversations throughout the whole process.

That's what makes it so compelling. That's what's going to make the Metaverse a vastly better platform than Facebook or Instagram or any other social media platform before it.

It's going to be you and your actual friends hanging out having a great time together. It's going to be small groups. It's going to be a largely positive experience not affected by global politics to any greater extent than you want it to be and it's going to  be based on open standards that we can all participate in and contribute to.

[53:04](https://youtu.be/KBEg9riBc_U?t=3184)

So that's my idea for this and I would like to open it up for questions and criticisms of this view and your own thoughts of any sort, thank you.

### Q&A

[53:23](https://youtu.be/KBEg9riBc_U?t=3203)

**Q**: Tim, I was just wondering about, you talked about voice being very expressive and a much more emotional way of doing stuff and obviously one of the things about Fortnite is you're aware of other characters that are other people, but what about somehow putting a face on the character in Fortnite so I can see them emoting as much as listening to them talking? 

[53:46](https://youtu.be/KBEg9riBc_U?t=3226)

**A**: Well yeah, that brings the core topic of digital humans and I think the really critical thing for a social 3D experience to succeed is empathy between the participants, right? That's where the voice communication breaks that barrier that text creates, but the next step is digital humans. Digital humans will be a central component of this. Being able to scan faces in real time. 

This is Mike Seymour asking the question, one of the world's foremost digital humans, but you know we have the tech for that now. The iPhone 10 has an amazing face scanning technology and you could, while you're playing on console or PC or iPhone, you could be using that simultaneously. I think this is going to be a key component of the experience. We need to have be able to project faces on the characters both photorealistic characters, but also stylized characters.

[54:35](https://youtu.be/KBEg9riBc_U?t=3275)

I think it's a stylization of Fortnite that breaks down a lot of the barriers to people who don't want to play a hardcore shooter game, right? The graphics aren't so intimidating, they're really readable and keep the game whimsical and I think that being able to project realistic humans faces and emotions onto that is going to change the world. 

Funny anecdote, you know the Marshmellow concert we did in Fortnite, it was just the perfect partnership. One of the really key elements that was perfect for that was that this is the one great musician in the world who doesn't have a face, so we didn't have to solve that problem that quickly.

[55:15](https://youtu.be/KBEg9riBc_U?t=3315)

For future events like that you really want to see performers, you want to see their faces, you want to see your friends, you want to see their emotions, and that's going to be the key part of it, thank you.

---

[55:23](https://youtu.be/KBEg9riBc_U?t=3323)

**Q**: What is something that you're personally looking forward to in the near future?

**A**: Personally looking forward to, well lets see... I think the really exciting thing to me is the increasing connectivity of these ecosystems. Y'know Fortnite was the first game that finally got Microsoft and Sony on board with cross-platform play between all platforms in Fortnite. Now we're working with a bunch of other partners like Ubisoft and the humble store to integrate our store ecosystems so that you don't have to have so many accounts as you go around.

I think there's now finally a lot of momentum in the whole tech industry, at least the good parts of it, to integrate systems and reduce barriers to interconnectivity, recognizing that everybody benefits from increased social graph size, increased connectivity, and decreased friction.

[56:11](https://youtu.be/KBEg9riBc_U?t=3371)

I'm really really looking forward to times when you start seeing much greater crossover of content between games and much greater crossover of actual games themselves as the barriers start to be removed. You're gonna see some really interesting things in Fortnite along these lines over the next year. 

---

[56:32](https://youtu.be/KBEg9riBc_U?t=3392)

**Q**: Hi Tim, so you often criticize Apple Store model which gives 30% away from creators, so could you share your deeper comment about this? How do you solve this problem between platformer and creator for Metaverse concept?

**A**: Oh sure, yeah promise I wouldn't use this as a ploy pulpit to promote store economics, but economic efficiency is going to be a really important part of this, right?

[57:06](https://youtu.be/KBEg9riBc_U?t=3426)

Content creation costs are really high and the more of the revenue from content that goes to the actual creators as opposed to overheads means better content and more efficiency and more jobs and you know just an overall better state for the industry.

Digital commerce is the most efficient platform in the world. MasterCard and Visa charge two and a half or three and a half percent for processing and transaction. Download bandwidth for major games is maybe 1% and if you add up all the cost of operating a store it's really only between 5 and 7%.

[57:37](https://youtu.be/KBEg9riBc_U?t=3457)

It's higher in developing economies where there aren't official payment processing methods, but= we really hope that economization of payments and just digital commerce in general is a critical part of this.

I guess the more we can reduce the need for middlemen the better, but if we need middlemen then we just want to be to be as efficient as possible. 

A funny story is there was a Bitcoin transaction a couple years ago that made the news. Somebody transferred a hundred million dollars from one Bitcoin user to another, and the payment processing charge that was collected by the blockchain was 33 cents.

So we can do better here, and that's just the tip of the iceberg, right? How much tax the ecosystem collects is a big issue we can optimize, but the variety of methods available for monetizing content in ways that don't detract from the users experience is really critical too.

[58:33](https://youtu.be/KBEg9riBc_U?t=3513)

Fortnite support-a-creator program is a multi tens of millions of dollar program worldwide. It's a very first attempt for us to enable streamers and other people to create content around Fortnite to make some money from it without putting up any sort of any sort of pay walls in front of any content.

We do that by saying "Oh gee, you bought a skin and you were recently watching that streamer, well that streamer will get some money from that."

We'd like to explore ways of expanding that and increasing its reach so that we can more naturally just accumulate an understanding of all of the things you interacted with and all the revenue you spent in association or proximity to that and ensure that there's revenue sharing even for free completely free content.

---

[59:21](https://youtu.be/KBEg9riBc_U?t=3561)

**Q**: Hi Tim, nice talk. What you described sounded a little bit like Ubuntu with a better presentation layer, and I'm wondering how the contract would work between the user contributed code and operating system, and also how you would incentivize apps to be good citizens and not consume too many resources?

**A**: Well lets see, I think to make this sort of thing work where you would run the same code on a bunch of different servers run by a bunch of different companies you need to release it under some sort of license. You can create one like an semi-open-source Metaverse license of some sort. The creator of the code owns the copyright to the codes so it's automatically theirs, and they can choose to share it open-source if they want or they can choose to license it just for use in this context.

**Q**: Oh sorry I didn't mean legally like ownership, I meant in terms of interfaces. It sounds like you'd be replacing the window with the scene graph and what you envision as the interface between the application and the shared state. 

**A**: Let's see, I think there are really two levels of that. One is sort of the operating system itself would provide the equivalent of the web browser's document object model, which is kind of the scene graph storing basically, the leaves are a bunch of user created objects, and all the other nodes are kind of standardized by the system. Also a large set of library functions which everybody can use just to interoperate. 

[60:47](https://youtu.be/KBEg9riBc_U?t=3647)

So I think everybody as a participant in this system would have some degree of access to the scene graph and be able to look at other objects, and query / interact with them. I think this doesn't need to necessarily look much different than a bunch of like c-sharp code that's running within the Unity engine to implement gameplay, except all of these scripts are written by different people. Doesn't need to look much different than the C++ code powering or blueprints powering an Unreal Engine game.

I think what you really need are long-term backwards compatibility guarantees to the code and also super robust sandboxing and security guarantees where like if you declare a bunch of variables private, nobody but you can touch them. All users can do is they can call your public interface. They might pass to you their identity like some sort of cryptographic proof of their ownership or credentials as a condition of that object interacting with you.

[61:41](https://youtu.be/KBEg9riBc_U?t=3701)

So you'd have some very robust security protocols enabling each programmer of every object to determine what an arbitrary user can do with the object and how it responds.

For example, a car in the game, you probably have the system provide like a standardized car interface just kind of two bound the set of possibilities and provide a standard way of interacting with cars. Then every implementation of that car might implement that class and might provide some additional interfaces that are specific to it, like how to integrate with its navigation system or jet boosters or whatever.

[62:15](https://youtu.be/KBEg9riBc_U?t=3716)

I think you're ultimately going to have a bunch of interfaces that are standardized either by a standards committee or de-facto standardized by the user who owns that code. You would use code signing to specify that like this is really my co-owned code and only future versions of it can be trusted if I'm signing it using the same signing key to have a degree of cryptographic security, degree of programming model, sandboxing, and interface security, to ensure that nobody does bad things.

[62:45](https://youtu.be/KBEg9riBc_U?t=3765)

**Q**: To draw an analogy with UE4 development, when people contribute changes they often need to make new subsystems that provide singletons that many actors can use. Would that sort of thing be involved in this signing process?

**A**: Yeah, I think ultimately with an open Metaverse you'd have a Standards Committee that gets together and decides what pieces to standardize over time. I think there could be a lot of pieces of this that are owned by people in the community, they just stay owned by them as long as that works fine, then having private ownership of stuff is great.

But, when something becomes so pervasive and there's an outcry for standardizing it, then you can start working on standardizing the behavior specification. 

If a user writes a car using the scripting system it should be able to work on every server everywhere and automatically work, regardless of whether it's standardized or not. The standardization reflects whether it's officially blessed and whether ownership of the cryptographic signing key is handed over from a creator to the Standards Committee by their choice. 

[63:48](https://youtu.be/KBEg9riBc_U?t=3828)

I think the Metaverse would have a lot of different experiences and every experience would be able to say what sorts of things are allowed within it. So you might have this badass car, but this level only allows you to run around in it - it bans cars and so you'd have some sort of really robust system for categorizing objects and saying what's allowed and ensuring that even if objects don't like - it's okay if the thing breaks sometimes. If some parts of the Metaverse that are user-created break from time to time it's okay the authors can just go in and fix it. 

We shouldn't be worried about that, we should just be worried about the user's privacy and security always being respected.

---

[64:28](https://youtu.be/KBEg9riBc_U?t=3868)

**Q**: Hi Tim, I think you touched on a lot of things adjacent to this, but as the Metaverse gets to a point where your real identity is more tied into it you - this is something that exists across country lines and everything do, you think this will get to a point where you need like specific laws for the Metaverse or even like a government for things within the Metaverse? Or is there another way to think about it?

**A**: That's a good question. You know people write laws in response to bad things that happen, right? Nobody's speculatively writes laws because something might happen. I think the best way of avoiding unfavorable legislation is to build a system that is open so that it's not accused of bad practices of any sort and that the curation mechanisms and the way that people interact socially together are reinforced positive behavior so that you don't end up having to have massive debates over censorship of hateful content.

[65:28](https://youtu.be/KBEg9riBc_U?t=3928)

I believe with the sort of system you want it to be so focused on positive interaction among small social groups that you could allow free speech, Just as a member of a group if you never want to hear awful stuff you just avoid it and you never see it. I think we need to get to a point where like if you don't search for porn or go out and seek it out, you just never see porn. 

If we do it that way I think that we avoid a lot of the calls from censorship which arise from hateful content surfacing to a massive number of people, intentionally reserves all of the curation algorithms.

[66:03](https://youtu.be/KBEg9riBc_U?t=3963)

That's what's killing sentiment about social media right now. It's not that it's bad stuff is being said, it's that bad stuff is being broadcast to millions of people procedurally.

**Q***: Right, on top of that there's also the interaction between you mentioned a lot of the engagement, a lot of the feedback mechanisms are engagement driven, but that might not always be aligned with like what might be good in a different sense.

[66:29](https://youtu.be/KBEg9riBc_U?t=3989)

**A**: Yeah, I think there's a negative feedback loop, it begins with making money from advertising which means that the amount of time you spend with your eyeballs on the screen determines how much money they make. That's a crappy thing to optimize for, because they're just trying to suck your time away and the way to get you to spend the most time on the thing might be to aggravate you to the point where you're spending all of your time fighting the people. 

It's kind of a well of despair they seem to be stuck in, whereas if you create a social experience where people would just like to interact with their friends then you could be on it or not - it doesn't matter.

I think what you're going to optimize for is an engagement with positive experiences where if money is being made, they you want to sell you an item, so you have the item and enjoy it, right? That's why the Fortnite economic model is quite positive. None of the items in Fortnite Battle Royale give you a gameplay advantage so you're just buying them because you want to have a cool outfit.

[67:24](https://youtu.be/KBEg9riBc_U?t=4044)

I think ensuring that all commerce is optimized for things that people will be happy buying and not like the negative feedback loop of loot boxes where you really want a rare item so you buy another loot box, it doesn't have it, so you buy another one - and now you've bought 10 and then you're really pissed off.

I think optimizing for positive economic engagement is crucially important. I think what's really needed there are systems for building trust where if a company makes a game that has crappy monetization practices, word gets around and people don't play it.

You want that rather than a huge set of rules saying you can't do this that or the other thing. Reputation based rather than rules based.

---

[68:10](https://youtu.be/KBEg9riBc_U?t=4090)

**Q**: So I just kind of want to know your thoughts about kind of stepping out of the Metaverse, powering, accessing, sustainability, and infrastructure - how accessing the Metaverse... and kind want your thoughts about that.

**A**: Oh infrastructure, well that's an interesting question. Our Amazon Web Services bill is astronomical in running Fortnite servers for 2 million peak concurrent users, but I think the Metaverse will be a lot larger than that.

It's going to be interesting, I think the really interesting effects start to happen once you have an open Federation between a bunch of different servers, potentially running different server software, that can all interoperate properly together because then you will have a lot of competition between them, you'll have optimization and features and a whole economy develop around running servers for this Metaverse environment.

[69:01](https://youtu.be/KBEg9riBc_U?t=4141)

I think the hope is to ensure that there's competition in the economy for every aspect of this thing so the best deals and the best software wins at every stage of it, right?

I wish there's competition among App Stores where they competed on the fees they charge. If you had a dozen app stores competing for business that would keep everybody honest. Same thing for server time, same thing for server hosting, same thing for digital goods in the Metaverse. You really want economic competition to drive the quality and value trade-offs that are made in the economy.

---

[69:36](https://youtu.be/KBEg9riBc_U?t=4176)

**Q**: Hi Tim, keeping in mind the long term view of the Metaverse, what 3 things do you hope Unreal as a game engine should achieve five years from now?


**A**: That's really interesting, you know we've been pushing photorealism so fast I'm thinking like it might not take five years. I think the real core challenge for every engine right now, which nobody's really solved fully, are being able to serve gigantic open worlds with an unbounded number of participants playing together without any visible boundaries between them.

Fortnight is 10 million peak concurrent users but divided up into hundred players each in a hundred thousand sessions. What we want is one world with ten million players in it all at once and a huge procedurally generated world that we can render and stream.

[70:27](https://youtu.be/KBEg9riBc_U?t=4227)

I think that the server side challenges of dealing with these huge environments and user accounts without charting are really critical. The rendering side details of being able to render those things are critical. Also, just increased adoption of open standards as interchange formats now and as definitive formats in the future is going to be really important.

Game engines are always pushing new features far ahead of the point where it would make sense to standardize and we've got to decide where the bleeding edge is, like what we're trying to standardize and what we're not bothering with yet. I feel we shouldn't really be trying to standardize particle systems yet because they're too complicated and engine specific, but we can certainly standardize animation and faces and body rigs and all sorts of other components.

[71:15](https://youtu.be/KBEg9riBc_U?t=4275)

I think standardization push is going to be another really huge one.

**Q**: Last question on that, you clearly don't seem to be a fan of the existing advertising business, what would be Tim Sweeney version of YouTube's positive reinforcement sort of economics - what would your version be if you were to retool?

**A**: I think my revulsion is to business models that are adversarial to the consumer, where you make money by doing things that are detracting from the consumers experience. I think an honest business model makes money from selling consumers things that they want or delivering great experiences to consumers and making money from economic activity around it.

[72:00](https://youtu.be/KBEg9riBc_U?t=4320)

I think and advertising is just taxing your time instead of taxing your wallet, I'd rather have my wallet taxed personally. Similar thing with our privacy situation right now is so many of these platforms are so invasive with privacy that they're taxing your personal life rather than your wallet as well.

I think having a business model that's always aligned with consumer interest is critical. That's actually a pretty subtle topic because in a game like Fortnite a reasonable percentage f the population never spends money at all, but they are actually adding a lot of value to the economy.

They're playing with friends, they're creating additional engagement in their social group, and even if you're not spending the money in Fortnite you're participating an economic activity that is valuable.

I think we need to be really broad and open-minded about how we structure the roles for this thing just so that indirect monetization of content that inherently has to be free is a major part of it and it's not neglected.

We'd like to see an environment where all these decisions are made not by ecosystem vendors trying to extract taxes out of it, but the taxes are low and agreed on and all of the economic trade-offs are between the value created by the different economic participants themselves.

They are hopefully going to be self balancing to some extent, and then if you under pay somebody for their work they deliver less of it and the people who profit from the work do worse, and so they actually recognize it's in their best interest to transfer more the value of their work to them.

[73:33](https://youtu.be/KBEg9riBc_U?t=4413)

It's like Fortnite selling skins as the primary or sewing costumes is the primary monetization vector, but the value creation is primarily around people playing the game and streamers streaming the game and raising awareness.

There needs to be lots of internal inflows within the economy that are a tied to activity rather than to spending. 

Thank you all for your time.
