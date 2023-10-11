---
layout: post
title:  "Comparing Game Engines and Why We Love Them (Sometimes)"
excerpt_separator: <!--more-->
permalink: /resources/Comparing-Game-Engines-and-Why-We-Love-Them-Sometimes

---
![Engines](/assets/img/engines.png)
<br />
<br />


If you didn’t know already, we develop and port games, meaning we take a game running on a platform (like PC) and make it work on another platform (like a console). There are many ways to do this, and many engines and setups that developers use, but several of these methods also create challenges for teams like ours to be able to port the game using those tools. In this post we’re going to highlight a few common engines (like Unity or Unreal Engine) and talk about some of the interesting differences in porting between the two that we commonly see. Note that we are not recommending one engine over the other (as both can have their own strengths and weaknesses) nor are we discounting the other engines that exist (both FOSS and Closed Source ones), we just wanted to highlight some common comparisons between the two most common engines we see currently.
<!--more-->
<br />

---

#### What do we code in?  

- Unity is generally a lot of C# while Unreal is a mixture of Blueprints (their visual scripting language) and C++.
- Blueprints can be good for fast prototyping but also can have problems merging sometimes, or you might need C++ anyways for specific things. It can also become very messy visually (just like code) if it’s not kept well, making it confusing to follow for people jumping into a project like us.
- Unity is C# and monobehaviors and setting up your own class hierarchies (You put your code into a class and stick it on an object and you're good to go).
- Unreal wants you to inherit from certain classes (because it has a very set way on how objects 'live') and you put code in the game instance.

---

#### What's different?

- In Unity you can’t change source code (unless you pay for that license), and have to wait for engine changes to be updated (or use a specific version) whereas in Unreal you can change source code and ‘cherry-pick’ fixes you need without updating the whole engine (usually).
- Unity is generally smaller overall (where Unreal can reach 200+ GBs sometimes!).
- Coordinate systems are in a different orientation in Unity and Unreal (Z-up vs Y-up).
- Creating builds for testing or submission are very different on both engines (Unity is considered “easier” by some while Unreal is considered more customizable by others). Automating either can be a challenge!

---

#### What's the same?

- Some problems can be caused by how the game was designed, or core issues with performance regardless of the engine used, and the fixes are generally similar.
- Both have specific ways to package files for different platforms so knowing how to do it on one doesn’t mean you’ll know how to do it on another, and it's not always straightforward on either.
- Console errors can be confusing no matter which engine you use! (and each has different ways to handle this or comb through errors to see what’s happening).

---

#### Other Things?

- Licensing and support work very differently between the two.
- Each engine has their strengths and weaknesses and though we might argue internally over which we think is ‘better’, it really is that each game is different and there’s no one-size-fits-all answer!
- For either (especially Unreal!) it can be extremely beneficial to know someone who can use the engine well to get advice/guidance on best practices or intended use. They engines also provide some of this themselves via videos/docs.

---

![Talking](/assets/img/talking.png)
<br />

### Ok but which one should I use?

There is no "right" answer here but there are some random things we can note to help make a decision. The truth is, what works for others might not work for you.
<br />

---

#### On Plug-ins

One thing we’ve noticed about developing Unity games is that it’s a very plugin-heavy environment. This can be good for finding quick solutions but a lot of core features for consoles can rely on custom code or Asset Store plugins which means relying not only on the engine support but also plugin developers (whose plugins might not even work on your targeted platform). Common examples of plugins used for Unity are Rewired (for controls), FMOD/Wwise (audio), and Photon (for online). Unity is also set up in a way where there’s so many different ways to handle a particular problem that something seemingly simple can quickly become convoluted or complicated since you have the ‘freedom’ to integrate it in so many ways. Another way to think of this: Unity kind of gives you "enough rope to hang yourself" if you're not careful, and we've definitely had to come in to help fix these situations which can take a lot of effort.
<br />

---

#### On Performance

Performance also seems to be a pretty consistent issue with Unity projects for consoles because of the variation of rendering systems and other things where performance is sacrificed for flexibility. This isn’t to say Unity games don’t perform well but just that we’ve noticed performance issues can crop up because of the built-in flexibility/choices of so many systems to use (Rendering pipelines are a good example, since you can use HDRP, Built-in, URP, Scriptable, or even a custom one with varying issues on different platforms). If you know how to use these and other systems well though, they can make for fantastic looking games that run fine.
<br />


---

#### So what about unreal then?

Unreal is also not the perfect solution and can sometimes have its own set of issues (can be less popular with indies or different supported versions than other engines/SDKs etc.) but it can also come with the benefit of being able to modify aspects of the source code and has some pretty robust tools built-in. It also seems like a lot of projects using Unreal have more senior engineers on them, so sometimes those projects can come with both simple or complicated solutions because of that (remember: we usually have to come in at the end of development, after the band-aids and solutions have been laid down). Unreal is also a much larger engine in size so downloading it can take a long time or take up a lot of space. The way that consoles are integrated into it can also feel less straightforward than Unity’s can be to some people (though it still works fine). It can also take a very long time to build, especially if you’re not using a computer made for it.

Some really neat things about Unreal are that you can do real-time debug changes (consolevar) to turn off shadows, lighting, and other things that you'd have to rebuild each time for Unity to do. This comes in really handy for performance testing!. It also has a much more robust audio system built-in (both UE4 and MetaSounds) that allows for awesome functionality that you would need middleware to do in Unity well.
<br />

---

#### In Conclusion

There are many reasons we haven't even began to dig deeply into why these Unity, Unreal, other available engines, or custom engines would be the most useful for your team/game and unfortunately we can't make that decision for you! But.... hopefully this was interesting and helps clarify why each engine presents its own set of challenges/benefits and why a team might choose one engine over the other. We barely scratched the surface of some of these subjects for brevity, but the possibilities can seem practically endless.

---

Want to know more? Feel free to contact us at [info@plasticfernstudios.com](mailto:info@plasticfernstudios.com)
