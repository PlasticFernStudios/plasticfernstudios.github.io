---
layout: post
title:  "Getting to Know Porting"
excerpt_separator: <!--more-->
permalink: /resources/:title
---
![Porting Image](/assets/img/portingthinking.png)  
<br />

Who wouldn’t want their game to be available on as many platforms as possible? Why don’t devs just do it? Well...... it’s complicated and is difficult (requiring a lot of work and know-how) to be able to hit the release of multiple platforms, especially simultaneously. This also, can cost quite a bit of money depending on the game. It’s unfortunately not as easy as clicking to build a new platform in Unity!
<!--more-->
This isn't an exhaustive list, but ports can take weeks, months, and sometimes years to get right in order to bring it from PC (or another platform) onto your target platform. This is because usually a lot of things need to be added, changed, and iterated on, but most ports consist of these basic steps:

  - Code needs to be changed to include platform specific calls, settings, and needs
  - Sometimes entire systems need to be reworked (like for graphic or cpu issues, or for save data/achievements, shaders etc)
  - The title needs to be in ‘compliance’ with the platform standards (each has its own rules to follow and checks to be done)
  - Sometimes new art or other things are needed to address performance issues running on the new platform
  - Testing on target platforms to make sure it's working correctly
  - Triaging issues/timelines/priorities to hit dates and budget
  - Navigating the backend systems for each platform to successfully setup and release your game!

----

![Porting Image](/assets/img/portingcost.png)

💲 What about cost?

📝 How do I budget for this? (That's one of the most common questions we get)

💳 How do I pay for this?

There’s a few different ways porting might be paid for, regardless of if you're using a publisher or not. This can be through a royalty percentage of sales, out of pocket payments (monthly etc), or a combination of these and more. the royalty rate can vary a lot, so I’m going to be touching more on the out of pocket cost portion.

The first and most important thing: know what porting will cover. Is it just programming? QA? Release Management (submissions etc)? Tech Art? This is the first step in knowing what the costs are/might be.

At Plastic Fern Studios, we offer all encompassing services to handle whatever is needed to port a game, including everything mentioned above. We're also used to working with different teams with different capabilities and can easily help "fill holes" in the development process instead (or, just consult if you're doing it yourself!)
Another thing to keep in mind is that porting requires specific hardware to develop for certain platforms. This cost is usually taken into account when getting a quote from someone but might be a "hidden" cost if you attempt to do it yourself.

<br />
![Porting Information](/assets/img/portinginfo.png)
<br />


Example time! Let’s say you have a game where all this work takes exactly 3 months for a few people. Usually you’ll have a programmer or two, a production-y kind of person for handling release management and other things and possibly even a small QA team as a part of this. Now, how much does this even cost? It varies, but below are some general ideas of cost to get you started on a budget.  

- **Programmer**: A decently experienced programmer on a contract can cost anywhere from ~$8,000 to ~$25,000 (or more!) a month, depending on the company, region, platform, or experience needed.
  - A note here: a more expensive engineer, can save money in the long run by avoiding mistakes or knowing issues before they occur
  - You might also need different types of specialists, like someone for networking, a specific console, tech art, optimizations etc. (which specialists can  be more expensive or harder to schedule).
- **Release Management**: If the porting is also going to have someone doing the submissions and handling all of the platform-side paperwork/meetings/emails etc for you (aka "release management"), you’re likely going to need at least 1 month of the 3 for someone to handle that. Essentially, you're paying for time-saving knowledge, decision making, and platform relationships etc, though it can be charged in a few ways:
  - Sometimes it’s an hourly rate, could be anywhere from $50 - $150 an hour depending on a lot of factors
  - Sometimes it’s a flat fee, per platform (which assumes a # of hours commitment and is usually pretty close to a month * their rate)
  - A note here: similar to contract producers, it's not always 40 hours a week the entirety of the project, and could be some her, some there (or 15 hours a week etc). The release cycle is usually a bit more busy!
- **Quality Assurance**: expect anywhere from $20 up to $50 or more an hour for testing and ‘lead’ work, depending on how much is involved. Let’s assume they use their QA for 1 month of that 3 month time, to make sure the submission is ready to go. Larger companies als usually have a lead or PM costs as well, not just a 'single tester'.

____

![Cost Information](/assets/img/cost.png)

These are estimated costs based on the above example project and could vary.

----

So based on the above, we're going to do some real quick math:


- 3 months x 1 experienced engineer                 $24,000 - $75,000

- “1 month” x 1 release management person     $7,000 - $13,000

- 1 month of QA help from a specialist              $4,000 - $10,000

Anyways, this brings you to a total of $35,000 - $98,000 to bring this made-up game to your platform in this completely made-up example. This *doesn’t* count any time you might need to take to help these teams do their job (provide guidance, images, or docs etc), any additional tech art or optimization support, or the time to research and make important decisions about things. This also does not include any costs for marketing, localizing, or other things you should be doing to release a game. It's very hard to determine needs just from the game alone and the costs can be quite a bit more than you expect so it's helpful to work together with someone to figure out what your title's needs are and what it'll take to accomplish your goals.

**Are these the same for every game?** Nope! One of our main goals at Plastic Fern Studios is actually to help teams figure out what their budgets are and how we could best use that budget to complete their goals. It also depends WILDLY on the game, since an online multiplayer game would need more things than a single player one, and some games require a lot more help than others even if they are both "basically" the same game.


----

![Porting Cost Factors](/assets/img/portingfactors.png)

----
<br />


#### But why can't you just tell us how much my game costs to port?

The answer is because every game is different, and we take time during each quote to look at source code and ask a lot of questions to determine how much time and cost something might be. Some contributing factors include:

- The platform the game is coming from and going to (especially multiple platforms)
- How the game controls/works in general
- The graphic style/pipeline used for the game
- If the game is GPU/CPU bound on slower hardware (and if there’s straightforward fixes for it)
- How performant the code is in general (and if things need to be reworked or taken out completely to work on certain platforms)
- How long the game is/how big the scope of the game is
- Any plugins or 3rd party things used in the game (and if they are supported on platforms)
- The engine used, and the version of the engine used
- When these processes start in the development cycle. For QA, earlier checks can help save money later, but for porting, if you’re trying to hit performance targets and more things get added/changed, you end up redoing a lot of work to hit a "moving" target, costing you more. If you do release management yourself, and miss important steps, you could delay the release waiting for other processes to finish

Want to know more? Feel free to contact us at [info@plasticfernstudios.com](mailto:info@plasticfernstudios.com)
