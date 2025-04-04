---
template: post
title: 4. Agile vs Open Source
description: Talk given to Simply Business about Risk-First and Open Source
author: rob

featured: 
  class: bg1
  element: '<image-artifact imgsrc="/public/templates/risk-first/posts/scrum.svg">Agile vs Open Source</image-artifact>'
date: 2022-04-30 16:32:03 +0000
tags: 
 - Presentations
sidebar_position: 4
hide_table_of_contents: true
---
    <h1>Agile Vs Open-Source</h1>
    
    <em>These slides are from a talk I gave to Simply Business about Risk-First</em>

    <div class="slides">
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.001.jpg" alt="Image of slide number 1" />
            </div>
            <div class="slide-notes">
                      <p>So, for this talk, I am going to talk about Risk-First, the passion I have for Open-Source and also about my current job, which I’ve had for just over a month.</p>
            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.002.jpg" alt="Image of slide number 2" />
            </div>
            <div class="slide-notes">
                      <p>So-we’ve looked at Feedback Loops in detail, and I talked about how Scrum was just the formalisation of a few well-chosen feedback loops, out of the many available to software developers.   </p>

      <p>The Agile movement, of which Scrum is a part, really started about 20 years ago, and has been phenomenally successful in selling the idea of these feedback loops.</p>

      <p>There are Scrum certification courses, and badges, and certificates, and consultancy and all kinds of things.</p>

      <p>This is so super-successful that inevitably, there is a lot of push back now.  </p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.003.jpg" alt="Image of slide number 3" />
            </div>
            <div class="slide-notes">
                      <p>It’s not just people on the edge of the Agile community pushing back either.  Ron Jeffries and Martin Fowler were a couple of the original signatories of the Agile Manifesto. </p>

      <p>And, here are some articles where they complain about the way agile is going.</p>

      <p>In a large part, they are responsible for the fact that Agile is so outrageously successful.  But, they’re not happy.  They don’t like the way that Agile has been commercialised, and turned into exactly the kind of process that Agile was really rejecting in the first place.</p>

      <p>So, it feels like Agile is falling out of favour.. especially with these guys.</p>

      <p>But I have a different take on why this might be.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.004.jpg" alt="Image of slide number 4" />
            </div>
            <div class="slide-notes">
                      <p>When Kent Beck and Ron Jeffries and Martin Fowler got together to write the agile manifesto, the software landscape was very different than today.</p>

      <p>JUnit was a really early open-source library!  You could use Tomcat or Apache… or, maybe that was about it.</p>

      <p>The landscape has changed. </p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.005.jpg" alt="Image of slide number 5" />
            </div>
            <div class="slide-notes">
                      <p>What’s getting harder and harder now, is figuring out which tools to use.  Not just methodologies, or practices, like we’ve looked at today, but tools of all kinds. </p>

      <p>Because there are so many languages, so many libraries.   A lot of them are really good.</p>

      <p>It’s easy for me to stand here and say: use the libraries or tools or languages that help you address the most risk.  This seems like the underlying physics of software development.  Using a practice like “Agile Software Development” is really just one technique amongst many in addressing risk. </p>

      <p>But what’s a much harder problem now is curation.  How do I figure out which tool or library or practice to use?   How do I know it’ll solve my problems?  </p>

      <p>It would be strange if Agile, a practice invented 20 years ago for an entirely different risk landscape, was still perfectly suited to a completely different landscape today.</p>

      <p>And, I contend that the main reason the software landscape is so different today is because of Open Source - and I’ll try and persuade you of this.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.006.jpg" alt="Image of slide number 6" />
            </div>
            <div class="slide-notes">
                      <p>So, what risks does Agile address?  Risks like Schedule slippage, cancellation and the business changing their minds - they’re all addressed by having short release cycles.  Get code into production quickly so that it starts paying its way.</p>

      <p>Doing lots of releases could impact quality, and cause outages, so we bring in practices like automated testing and refactoring.  The on-site customer (from XP) and the Sprint Review are there to catch misunderstood requirements.</p>

      <p>We already talked about how Key-Person risk is addressed by Pair Programming and Collective Code Ownership. </p>

      <p>So this slide summarizes that - these are the risks addressed by XP, and the practices used to do it.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.007.jpg" alt="Image of slide number 7" />
            </div>
            <div class="slide-notes">
                      <p>But, are these Risks the biggest risks anymore?  </p>

      <p>If you’re building software in the Open-Source world, then probably what you want to do is put together a system based on six or seven key dependencies.  </p>

      <p>For example, if I was building a twitter-based website for printing T-Shirts, I might use some twitter APIs, some OAuth2 login piece, an API for getting the T-Shirts printed, and some kind of payments API like Stripe.  </p>

      <p>One really key risk then for me is what I call Lock-In Risk:  can I get all those dependencies to behave together in a cohesive manner.  What happens when the dependencies change?   Will they all co-operate in the way I want.  </p>

      <p>If some of my libraries are written in Java, and some in C++, will I be in the situation above where I’m trying to join Lego with those sticklebrick things on the left?  </p>

      <p>There are various tools out there to help you with this exact problem: things like Kubernetes, Docker or running other languages on the JVM, for example… but those are not things Agile really cares about.</p>

      <p>One tennet of Agile development is do “the simplest thing that could possibly work”.</p>

      <p>But is that going to lead you into this Lock-In Risk problem?  Are you going to try to combine things that just don’t work together?</p>

      <p>This goes back to that whole “Meta-Game” idea that I was talking about earlier.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.008.jpg" alt="Image of slide number 8" />
            </div>
            <div class="slide-notes">
                      <p>Working in IT is really interesting.  Every day is Christmas Eve.  There are always new technologies to play with, new ideas to look at new practices to try.  This is one of the reasons why it’s such a fun, crazy career to work in.</p>

      <p>But it’s easy to get caught up in hype.  </p>

      <p>Blockchain, </p>

      <p>AI, </p>

      <p>Big Data.</p>

      <p>There’s always a new Javascript framework!</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.009.jpg" alt="Image of slide number 9" />
            </div>
            <div class="slide-notes">
                      <p>So this Lock-In Risk problem is getting worse over time.  Every day there are more and more Open Source libraries to choose from.  No one has time to evaluate even a tiny fraction of them.</p>

      <p>I call this the “Broccoli Problem”.  To start with, on the left, we had computers, which did.. well, computing. </p>

      <p>But now, on the right, we have an explosion of different libraries and products which cater to more and more specific use-cases.</p>

      <p>And, in the end you end up with NPM.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.010.jpg" alt="Image of slide number 10" />
            </div>
            <div class="slide-notes">
                      <p>NPM is the Javascript package manager. It’s a list of all the Open Source Javascript Libraries. And it has been going now since 2009 and as of 2022 there are nearly 2 million packages in there.   And the number of downloads is just… staggering.</p>

      <p>This is the broccoli problem - how the hell do I find the stuff I want or need in this lot?</p>

      <p>And, this is something that Agile doesn’t talk about - it’s just not on the Agile radar.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.011.jpg" alt="Image of slide number 11" />
            </div>
            <div class="slide-notes">
                      <p>So Veracode, who make money doing source-code security scanning came out with this statistic in 2018:  95% of all IT organisations rely on Open Source.  But personally based on that slide with things like Linux, Java and so on, I feel it’s probably going to be higher.  Maybe there are a few windows- or mac-only IT organisations out there… but in any case MacOS is based on Open Source GNU/Linux code.</p>

      <p>But this brings us onto a second problem, also not addressed by Agile.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.012.jpg" alt="Image of slide number 12" />
            </div>
            <div class="slide-notes">
                      <p>Another problem with building software out of a collection of dependencies is security risk.  </p>

      <p>The log4shell exploit is a recent example of a hugely widely-used piece of open-source software (in this case, Log4j) containing a vulnerability that could then be exploited in any of the systems using it.</p>

      <p>Again, Agile doesn’t have anything specific to say about this Risk.  Unless the product owner is on top of the Security Risks, there’s no reason to think they’ll get prioritised in a Sprint.</p>

      <p>Really, DevOps has come along to try and plug that gap.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.013.jpg" alt="Image of slide number 13" />
            </div>
            <div class="slide-notes">
                      <p>So, going back to that Veracode statement, and the rise of Open Source over the last 20 years, the change we’ve seen since the Agile movement started.. how has this happened?</p>

      <p>You might look at Veracode’s statement, and say, this is because Open-Source software is free.  And, that’s certainly a part of it.  Free is always popular!</p>

      <p>But I would say, a bigger part is because Open Source can be fit together in new ways, and you can build bigger and bigger things with it.  Just like the lego on the right.</p>

      <p>For me, proprietary software is like those lego bricks on the left:  you can put them at the top of a big pyramid of open-source, and sell it, but you can’t extend it.   It’s not allowed by the license.</p>

      <p>And, this means that the life of Open software is going to be longer than proprietary software.  But, you might not make so much money on it.  </p>

      <p>Here’s why.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.014.jpg" alt="Image of slide number 14" />
            </div>
            <div class="slide-notes">
                      <p>For software to survive, it needs to evolve and change.  And for that to happen, it needs developers.  </p>

      <p>So, let’s look at the feedback loops.  </p>

      <p>With proprietary software, you have customers, who give you money.  They pay for developer effort, and you get new releases.  Then, hopefully you get more new customers and more money, and the cycle continues.</p>

      <p>With open source software, it’s all started with dependencies.  People pick up and use the software, and come to rely on it.  They then have problems with it, or new features they want to add.  </p>

      <p>This hopefully means that developers come along and fix those issues, and that means Pull Requests and New Releases.  </p>

      <p>So the lifecycle on the left is sustained by money, whereas the lifecycle on the right is dependencies.</p>

      <p>Because there are these two distinct types of feedback loops, you get two distinct types of software.  On the left are things like Google or Facebook - totally proprietary, making lots of money.  On the right, lots of languages like Java and Python are here - it’s all about the network effect, and building ecosystems.</p>

      <p>Somewhere in the middle, you might have Amazon, who open all their APIs but make lots of money along the way by selling the compute time of using those APIs.  And being a shop.</p>

      <p>But, the problem with this is that developers need to eat, so somehow, money has to be involved in the feedback loop on the right.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.015.jpg" alt="Image of slide number 15" />
            </div>
            <div class="slide-notes">
                      <p>But there’s a big problem with that Open Feedback loop.  Because it doesn’t properly involve money, it’s not well-funded.   So, there’s a big worry in Open Source which is nicely explained by this XKCD comic.  The worry is Agency Risk - that you have some dependency on a piece of software that is maintained invisibly by some critical person.  </p>

      <p>A lot of Open Source is funded by that guy in Nebraska.  It’s a personal project, done for the love of it, or through personal necessity.  The problem with that is the Agency Risk - by depending on this piece of software -no matter how good it is- you are also depending on the team maintaining it, to a certain extent.</p>

      <p>If there were more money in the system, there might be a bigger team of people involved in that one supporting project.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.016.jpg" alt="Image of slide number 16" />
            </div>
            <div class="slide-notes">
                      <p>So, I’ve worked in banking for nearly all of my career.  And nearly all the software I’ve written in that time has been proprietary.  But, I’ve consumed a lot of Open Source along the way.</p>

      <p>So, the last thing I want to talk about with respect to open source is a problem that a lot of us working in financial services have faced.  </p>

      <p>That is, on the one hand, we are massive consumers of open source software, but on the other, we have been prevented from contributing back. </p>

      <p>We’re making that Nebraska problem worse.</p>

      <p>Why is that?</p>

      <p>And, I think the reasoning goes like this:</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.017.jpg" alt="Image of slide number 17" />
            </div>
            <div class="slide-notes">
                      <p>Back when I started my career, this was how my employers thought: </p>

      <p>“Our systems are our secret sauce… their code is the one unique thing about our bank, and can’t be allowed to leave”</p>

      <p>This thinking has meant that, by-and-large, people working in Financial institutions are not contributing to Open Source as part of their jobs.  </p>

      <p>Which I find really weird.  Because look at where banks are.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.018.jpg" alt="Image of slide number 18" />
            </div>
            <div class="slide-notes">
                      <p>This is a picture of Canary Wharf in London.  But there are lots of other financial centres around the world.  That is, places where all the banks cluster together geographically.</p>

      <p>The main reason for wanting to do this is that from a labour point of view, bank workers know where to live.  And changing jobs means going to work next door. </p>

      <p>But that means it’s very easy for ideas to transmit between these organisations.  That is you are creating a collective “Internal Model” for all banks, not just building one bank’s model in isolation.</p>

      <p>So, what sense does it make to prevent software from crossing the street too?  </p>

      <p>And, yeah, attitudes are changing.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.019.jpg" alt="Image of slide number 19" />
            </div>
            <div class="slide-notes">
                      <p>To Something like this:</p>

      <p>“Ok. Maybe not all systems.  </p>

      <p>Most of our code is just a poorly-implemented, in-house version of something that exists already.  </p>

      <p>“Not maintaining that code would be a cost-saving opportunity”</p>

      <p>So instead of developers trying to build something that’s the best-in-the-bank, they can focus on building the best-in-the industry.  And everyone wins.</p>

      <p>Because by and large, the vast majority of software in banks is not doing anything that cool.  </p>

      <p>And there’s another angle to this too:</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.020.jpg" alt="Image of slide number 20" />
            </div>
            <div class="slide-notes">
                      <p>“Any time we create a proprietary version of something it eventually ends up getting left behind by its original developers who move on.</p>

      <p>“Also, Open Source is cool, and makes us look good”</p>

      <p>So, we’ve gone from the idea that sharing code is a negative, to the idea that it’ll save money then to the idea that actually there are positive benefits to it too.  </p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.021.jpg" alt="Image of slide number 21" />
            </div>
            <div class="slide-notes">
                      <p>And, it’s with that change-of-heart that Deutsche Bank allowed me to Open-Source this project, which is a library I built while at DB.</p>

      <p>It’s a library to help developers build chat-bots for the Symphony and Microsoft Teams platforms.</p>

      <p>Now, I could have built this in-house for Deutsche Bank.  But I left DB in November and even though I’m in contact with the bot-building team there, it’s not completely clear that they have anyone to maintain this going forward.</p>

      <p>If this had been in-house software, it would probably be left to rot.  </p>

      <p>However, I knew that my career at least was likely to further involve chat-bot development.   </p>

      <p>So, by Open-Sourcing this software, I am selfishly providing something that I will be able to keep using in the future.</p>

      <p>But also, there may be a further life ahead of this project, which I’ll explain soon.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.022.jpg" alt="Image of slide number 22" />
            </div>
            <div class="slide-notes">
                      <p>So the next level thinking is:</p>

      <p>“Proprietary software always goes stale</p>

      <p>If we are driving the open-source implementations that other organisations use, we’ll have a competitive advantage”</p>

      <p>If you build these kind of lego bricks, people can build on top of them, and they get looked after and maintained.</p>

      <p>So this frame of mind is where financial institutions are going.  And some are already there.  As an example of what this means, let’s look at Google, who execute this to perfection</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.023.jpg" alt="Image of slide number 23" />
            </div>
            <div class="slide-notes">
                      <p>First, Google makes money by selling ads, whether search ads or YouTube.  </p>

      <p>So, to make it as easy as possible for people to see those ads, they created a free browser called Google Chrome, which is built on top of an open-source browser implementation that they created called Chromium.</p>

      <p>This ensures that no-one really makes money from browsers.  This strategy is called “commoditising your complement” - it’s the same thing that Microsoft did with PCs.  They sold more copies of Windows when PCs were a commodity.</p>

      <p>Second, the more mobile phones there are in the world, the more YouTube ads get seen.  So it makes perfect sense for Google to also have a commodity OS, like Android. </p>

      <p>Third, they compete with Amazon’s AWS with their GCP - Google Cloud Platform.  Now, Google are late entrants to this game, but it’s a really lucrative game. The only way they would be able to persuade developers to use their stack over Amazon’s was to offer something Amazon didn’t.  Kubernetes is kind of like an Operating System for the data centre.  Again, it’s Open Source and this means that people are building other tools on top of it.</p>

      <p>The hope is therefore that Kubernetes will Evolve faster that AWS, because of the Open Source feedback loop.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.024.jpg" alt="Image of slide number 24" />
            </div>
            <div class="slide-notes">
                      <p>Now, there is a problem with this for banks.  To a greater extent, Google “own” all of those things - Android, Chrome, Kubernetes, even though they’re open-source.</p>

      <p>But this is a huge problem for banks!</p>

      <p>Going back to Spring Bot, is it likely that other banks are going to contribute to a project that is owned by Deutsche Bank?  </p>

      <p>So this is where FINOS comes in, who are my new employer.  They are custodians of financial Open-Source projects, providing a level playing field for all of the contributors.</p>

      <p>So I got my Spring Bot project donated to FINOS, in the hope that other banks would help maintain it.  Now, that’s not happening yet, with Spring Bot, but there are other projects that FINOS has that banks are collaborating on, so maybe it’s just a matter of time.</p>

      <p>But the dream for me and FINOS is that developers in banks won’t just be writing proprietary bank software, but writing open source software for their bank and getting paid for it.   This is what I was doing with Spring Bot, but it seems like lots of other projects really would work better the same way.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.025.jpg" alt="Image of slide number 25" />
            </div>
            <div class="slide-notes">
                      <p>So, let’s summarize.  Why would doing more Open Source be good for Financial Institutions?</p>

      <p>First, at the moment, we’re are duplicating a lot.  For example - regulatory code gets written by every bank.  But there are projects in the OpenRegTech space starting now which aim to provide Open Source implementations of Regulation across institutions.  This is going to share the costs.</p>

      <p>Second, if there are fewer implementations, it means more users of each one.  Linus Torvalds famously said “Given enough eyeballs, all bugs are shallow.” So more users means fewer bugs.  </p>

      <p>Third, as we talked about above, the feedback loop of Open Source means that it builds on itself.  Open Source code survives individual organisations or teams failing.</p>

      <p>Fourth, we’re tackling that Nebraska developer problem:  hopefully, we’re moving to a “Corporate Open Source” world, where there is funding for critical pieces of infrastructure.</p>

      <p>And finally, (and this is kind of happening anyway) industry is waking up to the fact that, while Open Source is currently a free lunch there are downsides. So, they need to start worrying about things like security.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.026.jpg" alt="Image of slide number 26" />
            </div>
            <div class="slide-notes">
                      <p>So, the place I see organisations like FINOS or the Linux Foundation helping are to provide a level playing field, where financial institutions can cooperate on this stuff.  </p>

      <p>Not only that, but we’ve got to make it much, much easier for people in large corporations to get involved with this stuff, instead of getting bogged down in the bureaucracy and paperwork, which I think is the stage we’re currently in.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/AgileVsOpenSource/images/images.027.jpg" alt="Image of slide number 27" />
            </div>
            <div class="slide-notes">
                      <p>So, to summarise then, I think Agile has its place.  It’s about testing ideas fast and finding a solution.   We will always need to do that.</p>

      <p>But at the same time, we need to get to a place where the components we use to build our software are professionally constructed,  maintained and curated.  And not just the work of some guy in Nebraska.  </p>

      <p>And to get there, we need Open Source to be more people’s jobs.</p>

      <p>That’s the hope.  If you’d asked me 10 years ago whether that was achievable, I would have said no.  Now however, I’m not so sure - I see signs we’re headed in that direction, which I’m rea</p>


            </div>
        </div>
        
    </div>

    <p class="credits">Made with <a href="https://keynote-extractor.com">Keynote Extractor</a>.</p>
