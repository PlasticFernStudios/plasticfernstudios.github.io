---
layout: post
title:  "Common Misconceptions When It Comes To Console Porting"
excerpt_separator: <!--more-->
permalink: /resources/:title

---
![Timeline](/assets/img/timelinepost.png)

After a short break we’re back to share some knowledge about our experiences making games and especially with porting, testing, and releasing them onto consoles. One thing we wanted to address is that there are a lot of misconceptions when it comes to developing and releasing games for consoles that we wanted to cover in a multi-part series. This initial post will detail some broad strokes common misconceptions we’ve come across but stay tuned for the next newsletters in the series where we’ll dive deeply into a few of the points below with real-world examples!

To refresh your memory (and re-introduce ourselves), Plastic Fern Studios are experts in what you need to release your game. We specialize in porting, release management, audio, and QA and our veteran team provides skills, insights, and deliverables to demystify the process of launching your game.

<!--more-->
----

Below are some common myths or public misconceptions that are important to dispel when working on games with the intention of launching on consoles:

![Release Management Icon](/assets/img/release_management_icon.png)
<br />
**Myth**: If it works on lower end PCs it’ll work on Xbox/PS4 or I can just develop for what the most popular/newest console versions are (forgetting that things like Base Xboxes and Xbox One S exist).
<br />
**Truth**: Even though a lot of current consoles have really powerful or fancy variations (the PS5™ or PS4™ Pro and the Xbox One X or Series X) many people still use the base PS4™ or Xbox One, and you will run into memory, performance, or graphical issues with a lot of your player base if you don’t plan to address these early. Most devkits are also WAY more powerful than these, so you won’t see the same issues unless you try them specifically for these setups.

<br />
![Porting Icon](/assets/img/porting_icon.png)
<br />
**Myth**: All engines are equal when it comes to developing for consoles.
<br />
**Truth**: The support/plugins/tools that some engines have (or not) can vary quite a bit as well as the workflow and knowledge needed in order to use them to develop. There are also some engines where the “console support” needs to be done entirely from scratch/custom built. Even different versions of Unity and Unreal can have major impacts on the degree of difficulty of development.  
<br />
![Audio Icon](/assets/img/audio_icon.png)
<br />
**Myth**: All platforms are the same and you just choose which to build for in the dropdown menu.
<br />
**Truth**: Almost every facet of your game is handled differently depending on the console it’s being developed for. Some might require heavy refactoring of user/saves, new controls, huge optimizations for GPU and CPU, and some might require changing how the game works/feels (or even modes being dropped). They all also have unique ways to build and submit that require specific knowledge to do correctly.  
<br />
![QA Icon](/assets/img/qa_icon.png)
<br />
**Myth**: Bugs are always the developer’s fault, QA should always find every bug, bugs always have a solution, or issues on console are always the porting team’s fault.
<br />
**Truth**: Games are complicated and porting to consoles is largely working within the constraints of how the game was designed. Sometimes, bugs that show up are caused by issues with platform tools, engine versions, plugins, how game systems were setup, or other things that are largely out of the control of the team (and sometimes require a lot of work to fix!). We’ve run into bugs where even the large companies providing the development tools were stumped on what was causing them, it happens! It's also not a perfect science to find bugs and sometimes they can be missed or stay hidden for awhile (which is why it's important to have changing/long-term QA with knowledge of the game's complex systems!)
<br />
<br />
![Porting Information](/assets/img/portingthinking.png)
<br />
<br />

**Myth**: An "easy" port on one platform means it’ll be an “easy” port on all platforms
<br />
**Truth**: As mentioned before, since each platform has unique challenges and limitations, it is unwise to compare one platform’s development to another and assume since it was easier on one, then it will be easy on the next one. You will most likely run into performance, compatibility, or system issues that need to be customized for the next platform to work correctly.
<br />
<br />

![Release Management Icon](/assets/img/release_management_icon.png)
<br />
**Myth**: Audio, UI, and QA can wait till the end or I can handle those later or let someone else deal with them
<br />
**Truth**: These are generally the areas we find have the least amount of development on them when we look at the project (sometimes very late in the process). It's important for the experience off the players but also important for the bugs fixing/development side that these areas are planned ahead of time and that work is put into these systems to make sure that things work correctly, don't add more issues/are built on a house of cards, and are tested/planned for consoles.

<br />
![Porting Icon](/assets/img/porting_icon.png)
<br />
**Myth**: You planned your schedule perfectly.
<br />
**Truth**: It's never perfect but some are better than others! Generally though it's hard to accurately plan something years in advance and have it still be accurate. Generally we see problems where they are too short and don't include certain timeline quirks of some platforms or do not include any buffer if things go badly. Usually things like core issues, release management, Compliance QA, and building in a buffer for unforeseen contingencies on platforms are not taken into account (aka planning for the bare minimum with no backup or buffer plans).  
<br />
![Audio Icon](/assets/img/audio_icon.png)
<br />
**Myth**: It’s not important to have someone knowledgeable about the platform since they have docs and forums we can look at instead.
<br />
**Truth**: There is a lot of variance for submissions and development that can only be known through doing a lot of them (and that aren’t explained well, or easy to find). Even the smallest errors in Release Management or development can cause huge delays (or snowball things out of control). Things missed that require re-submitting, or having to redo entire systems late in development, can have huge knock-on effects for the rest of development (including missed timelines, missed windows for sales, and more cost to fix).
<br />
<br />
![QA Icon](/assets/img/qa_icon.png)
<br />
**Myth**: QA is "Just playing through the game" or “running into walls for hours” or can just be "tacked on" at the end of development.
<br />
**Truth**: Quality Assurance is a highly technical and separate position not only centered on the _processes_ around development and risk mitigation, but also including specialized testing that needs specific knowledge, especially for consoles. Functionality QA is making sure the game works as intended while Compliance QA is focused on making sure the title will conform to specific requirements set by consoles (which change a lot). QA for many games can be complicated, taking time, experience and skill to do right, definitely don't leave this to the end and make sure they have enough time and budget to do things properly and avoid rush checking or missed issues because of scope.
<br />
<br />
![Transparency Icon](/assets/img/transparency_120.png)
<br />
**Myth**: We can fix it with a Day 0/Day 1 patch (or a patch later on)
<br />
**Truth**: Patching can create as many (or more) issues than it solves. Patching a game requires an entirely new workflow to release (meaning more submissions, more builds etc.) and platforms have rules and timelines involved with them that might not fit into your own needs. Patching can also run the risk of potentially breaking systems in the game that were previously working, creating more issues for development/QA and even longer development times.

There's a whole separate load of considerations for patching that you don't have to do on first release including specific release checks as well as checks around save data migration and other things, not to mention that sometimes the fixes for a bug you're patching could cause other bugs (that are sometimes worse!).
<br />

---

Want to know more? Feel free to contact us at [info@plasticfernstudios.com](mailto:info@plasticfernstudios.com)
