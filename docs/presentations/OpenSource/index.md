---
template: post
title: All In On Open Source
description: Talk given to Colchester Digital about Open Source
author: rob

featured: 
  class: bg1
  element: '<image-artifact imgsrc="/public/templates/risk-first/posts/opensource.svg">All In On Open Source</image-artifact>'
date: 2020-10-08 16:32:03 +0000
tags: 
 - Presentations
sidebar_position: 7
hide_table_of_contents: true
---
    <h1>All In On Open Source</h1>
    
    <em>These slides and text are based on a presentation for Colchester Digital's Hacktoberfest.</em>

    <div class="slides">
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.001.jpg" alt="Image of slide number 1" />
            </div>
            <div class="slide-notes">
                      <p>Hi, my name’s Rob Moffat.  Today, I’m going to talk about Open Source software, but first a bit of background:</p>

      <p>I am a software consultant, currently at Deutsche Bank building ChatBots which potentially have a huge power to transform banking processes, although it’s early days right now.  </p>

      <p>We're using a chat-platform called Symphony, which is basically like “WhatsApp”, but for banks.  Unlike WhatsApp, Symphony is a very secure platform, relying on lots of industrial-grade encryption and so on.</p>

      <p>I’m also the author of “Risk-First Software Development”, a book about managing risk on software projects.   I’ll be touching on both of these things later in the talk, because there are 3 main sides I want to cover today, for which I’ve chosen 3 words beginning with P…</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.002.jpg" alt="Image of slide number 2" />
            </div>
            <div class="slide-notes">
                      <p>Power, Personal, Professional.</p>

      <p>Firstly, I’m going to look at why open source is such a tremendously big deal.  Why it’s such a powerful thing.  </p>

      <p>Secondly, I’m going to cover how Open Source affects me personally: both my contributions to it, and what I get from it.  </p>

      <p>Finally, I’m going to look at how I’m able to contribute to open-source software in a professional manner, in my consultancy work with Deutsche Bank, who it turns out, are quite forward-thinking about Open Source software.  </p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.003.jpg" alt="Image of slide number 3" />
            </div>
            <div class="slide-notes">
                      <p>So let’s start with Power.  On this slide is the cover of one of the most famous books on Software Engineering - TMMM by Fred Brooks.  It’s a collection of essays he wrote about his experience of being a software developer whilst at IBM. This is the 1995 edition, but And it’s so called because it has a chapter explaining Brooks’ Law</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.004.jpg" alt="Image of slide number 4" />
            </div>
            <div class="slide-notes">
                      <p>And the reason this is true is that if you add extra people to a project, suddenly there are more lines of communication, more people with different ideas, more people who need to be brought up-to-speed and so on.  It can often make things worse.</p>

      <p>But I want to focus on another quote in the book, from his “No Silver Bullet” essay.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.005.jpg" alt="Image of slide number 5" />
            </div>
            <div class="slide-notes">
                      <p>Brooks wrote this in 1985, so in the 1995 edition, he was able to reflect on whether he had been right or not.    In that 10-year span between 1985 and 1995, there were some improvements, new languages, some advances in AI, better tooling, better testing tools, all of which he anticipated in the original essay.  So, in the 1995 edition, looking back, he said that he was probably broadly correct.</p>

      <p>But what Brooks didn’t see coming in this essay, I think, was the Internet, which would fundamentally change the way in which we share, develop, value and improve software.   Because the way we develop software now is entirely different to the way Brooks did it.  Sharing code on the internet, and Open Source specifically, have changed everything. They are the silver bullet.  Maybe even a golden bullet. </p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.006.jpg" alt="Image of slide number 6" />
            </div>
            <div class="slide-notes">
                      <p>So, let’s talk about some early pieces of open source software that are still shaping the world we live in.  So, Linux is one of the oldest pieces of open-source software.  It was started in 1991, but really got going in the late 90’s and 00’s.  Linux takes a lot of code from the GNU project, which started in the 80’s, and was mainly an academic endeavour, as there weren’t many other people on the internet.  This is an operating system, so it provides services to other programs to run, like file management, handling displays and keyboards and so on.</p>

      <p>Now you might not think you’re familiar with Linux, but both Android and iOS (Apples iPhone operating system) both use a lot of code from this open-source route.</p>

      <p>Next to that, I’ve got the Apache feather and the Nginx logo, which between them host about 60-70% of all the traffic on the internet.  They are web servers, so when you ask for a web page, the chances are it’ll be Apache or NGinX serving the page.  Apache dates from 1995.</p>

      <p>Down on the bottom right, I have the wordpress logo, which a lot of people will be familiar with.  Wordpress serves about 30% or so of all web pages, so it’s also huge, and, Open Source. It dates back to 2003, originally.  </p>

      <p>Often, people will run their Wordpress blog on an Apache server, on a Linux Operating System.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.007.jpg" alt="Image of slide number 7" />
            </div>
            <div class="slide-notes">
                      <p>So, that’s often known as a LAMP stack.  So Linux, Apache, we know.  MySQL is a database - so all your wordpress posts get stored in there.  And PHP, Pearl, Python, they’re open-source programming languages - some of the biggest.  And Wordpress is written in PHP.</p>

      <p>All of this is Open Source… except perhaps for MySQL, which was Open Source, but is now owned by Oracle.  But here’s the thing:  once Oracle (somehow) managed to acquire MySQL, the original open-source MySQL became MariaDB.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.008.jpg" alt="Image of slide number 8" />
            </div>
            <div class="slide-notes">
                      <p>So now, no-one really uses MySQL, because Oracle want to charge money for it, and because most of the improvements are being done in MariaDB.  So the LAMP stack is now really Linux, Apache, MariaDB, Php.</p>

      <p>And this brings us to a really interesting question:  did these Open Source projects get so popular because they were good, or because they were Open Source?  </p>

      <p>We’ll touch on that as we.  But for now, the take away is that Open Source is a big deal - a much bigger deal than a lot of commercial software.  </p>

      <p>Now often, to be successful, it looks like you have to Open Source your software.  </p>

      <p>Now, why is that?  Why are you more likely to be successful if your software is open source?</p>

      <p>A lot of that might come down to developers. </p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.009.jpg" alt="Image of slide number 9" />
            </div>
            <div class="slide-notes">
                      <p>To emphasise this point, we’re going to head into the personal part of the story.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.010.jpg" alt="Image of slide number 10" />
            </div>
            <div class="slide-notes">
                      <p>Ok, so here’s a story from before I was at Deutsche Bank, when I was working with Credit Suisse in their Risk department.  We were building a new risk calculator.  And the process went something like this.  The guy on the left, he’s the Analyst.  He writes a requirements document, explaining exactly how he thinks the calculator should work.  Then, he goes to the pub.  Often, for several days. </p>

      <p>Next, the developer picks up these requirements, and starts programming. </p>

      <p>Eventually, on the right, you get the completed risk system</p>

      <p>The problem is: how do we know the developer implemented the requirements correctly?</p>

      <p>Well, we somehow, need to test them.  And this is where Open Source came in.  </p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.011.jpg" alt="Image of slide number 11" />
            </div>
            <div class="slide-notes">
                      <p>I looked around for an Open-Source solution to the problem, and found Concordion.  Now, the way Concordion works is this:  you write your specification using HTML, so it’s like a webpage.  Then, you have some Java code you want to test, and, so long as you follow concordion’s way of working, when you pass it the specification and the test, it can generate a report.  Here’s an example.  So, the analyst writes something about how names should be split, say.  </p>

      <p>Then, in the example, concordion is able to execute the code using the input “John Smith” and see that it is divided into “John” and “Smith”.  This is a pretty trivial example, but actually splitting names gets really, really hard when you consider other countries and ethnicities and so on.</p>

      <p>I thought - what if instead of using a HTML page, I could get the analyst to write a spreadsheet in Excel to do the same thing?</p>

      <p>And so, after evaluating concordion for a while as was, I wrote an extension to allow it to do just that.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.012.jpg" alt="Image of slide number 12" />
            </div>
            <div class="slide-notes">
                      <p>What happens, is that the extension takes your spreadsheet, and converts it to HTML that Concordion understands, and then you’re back where you were in the first diagram - you just run it through Concordion.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.013.jpg" alt="Image of slide number 13" />
            </div>
            <div class="slide-notes">
                      <p>Here’s an example: I write a spreadsheet here, doing taxi-fare calculations.   As you can see I’m entering all the formulas.  Now, this is the bit the analyst would do.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.014.jpg" alt="Image of slide number 14" />
            </div>
            <div class="slide-notes">
                      <p>When I run it through Concordion, it produces this HTML page with this table of results.  </p>

      <p>And, we used this a whole bunch for some really very complicated risk calculations, and we knew that if the programmer had programmed them wrong, then the tests would fail.  If the tests didn’t fail, then well, the analyst had obviously not provided enough tests to catch all the errors.</p>

      <p>So, it was a closed feedback loop.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.015.jpg" alt="Image of slide number 15" />
            </div>
            <div class="slide-notes">
                      <p>I’m not the only person to do this - there are 49 repositories in the concordion organisation.  I wrote this 6 years ago, and I don’t really do the maintenance anymore, but it’s a useful feature of concordion that other people can benefit from.  And, this only happened because it was open source and free to use.  If it hadn’t been, I wouldn’t have considered using it, and I certainly wouldn’t have contributed. </p>

      <p>This is not going to change the world.  But, it might really help out someone, somewhere.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.016.jpg" alt="Image of slide number 16" />
            </div>
            <div class="slide-notes">
                      <p>The second example I want to quickly cover is Risk-First.  So this image is from my website, riskfirst.org.  The idea of Risk-First is to be a catalog of the different risks you could face managing a software project.  And, it goes into detail discussing each of them.  </p>

      <p>The reason I wrote this was because I felt that a lot of software development is blindly following processes, but really, it should try to tailor those processes to the types of risks that it faces along the way:  staff risks, complexity risks, dependency risks, even Legal risks, if you’re Facebook.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.017.jpg" alt="Image of slide number 17" />
            </div>
            <div class="slide-notes">
                      <p>So, this is the risk-first website repo, on GitHub.  And, each page of the website is a file in my repo…</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.018.jpg" alt="Image of slide number 18" />
            </div>
            <div class="slide-notes">
                      <p>Here’s one of them, called “A Pattern Language”.</p>

      <p>Now, if I want, I can press the “Edit” button, and GitHub will allow me to edit that page. </p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.019.jpg" alt="Image of slide number 19" />
            </div>
            <div class="slide-notes">
                      <p>Now this is written in a language called “MarkDown”.  As opposed to “Markup” like HTML is.  See what they did there?  The idea of markdown is that it still looks OK even when you’re just viewing it as text, but, it can be made to look really nice when you view it as a webpage.</p>

      <p>So, I can have headings, and bullets, and quotes, and sub-headings - and, all the formatting is simply done just with text.  If a line begins with a hash, it’s a heading.  If it starts with a dash, it’s a bullet.  Quotes begin with a chevron.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.020.jpg" alt="Image of slide number 20" />
            </div>
            <div class="slide-notes">
                      <p>And, when you save it, on GitHub it looks like this.</p>

      <p>But, GitHub also has a feature called Jekyll, which is a Open-Source (obviously) static website generator.  After I make an edit on GitHub, it recreates the webpages in my website, on <a href="http://riskfirst.org" target="_blank">riskfirst.org</a></p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.021.jpg" alt="Image of slide number 21" />
            </div>
            <div class="slide-notes">
                      <p>It looks something like this.</p>

      <p>And obviously, Markdown is open source and Jekyll is open source, and people write extensions for them too.  GitHub is hosting this page for me, and the domain is riskfirst.org, but I don’t have to worry about running a webserver, or paying for a server somewhere.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.022.jpg" alt="Image of slide number 22" />
            </div>
            <div class="slide-notes">
                      <p>But one last thing I can do is take all those markdown files, run them through a tool called pandoc, which produced a PDF.  I was then able to upload that onto KDP, and have a book to sell.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.023.jpg" alt="Image of slide number 23" />
            </div>
            <div class="slide-notes">
                      <p>Now, I’m not going to give JK Rowling any sleepless nights, but this is a nice thing to have, and people do buy this - sometimes.  I’m glad I did it.  </p>

      <p>The point is, without open-source software, I would be nowhere.  I couldn’t have done any of this stuff - least of all publish a book!</p>

      <p>Because my writing is open-source, more people have access to these ideas.  The work, to a certain extent, advertises itself to people who are interested in this topic. It can be found with search engines.  People can read it and see if they like it first.  I was never going to sell millions of copies, and maybe, by publishing the whole thing open-source, I am limiting sales.  But actually, selling books isn’t that good a way to make money anyway, so let’s move on and talk about Open Source in the workplace.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.024.jpg" alt="Image of slide number 24" />
            </div>
            <div class="slide-notes">
                      <p>So, I’ve been working in the finance industry in London for many years.  During that time, consuming open source has always been on the cards: programming languages and things like Linux and Apache were always available.</p>

      <p>However, in the last two or three years, especially at Deutsche Bank, there has been a new focus on giving back.  It’s now acknowledged that it might be a good idea for banks to contribute to the open source community.  </p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.025.jpg" alt="Image of slide number 25" />
            </div>
            <div class="slide-notes">
                      <p>As I said at the start of the talk, I am building ChatBots at Deutsche Bank.  And this is one of the things I have been building:  it’s a library of components that helps you build chatbots for Symphony (the chat platform I mentioned earlier).</p>

      <p>Now, we could have just build this as an internal deutsche-bank-only library.  And, some people would have used it.  But, none of this functionality is Deutsche-specific.  There are no algorithms in here that other banks or other users of Symphony couldn’t have come up with! There are no trade secrets.  </p>

      <p>So DB have let me open-source this.</p>

      <p>I wrote it at DB, we had a thorough review of the code, and then we set up a process to synchronise our internal git repos with the ones on GitHub.   </p>

      <p>And since then, as you can see, DB have actually donated this project to FINOS:  A Financial Open-Source consortium, who will own it going forward.</p>

      <p>Why would they do that?</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.026.jpg" alt="Image of slide number 26" />
            </div>
            <div class="slide-notes">
                      <p>Firstly, it’s now understood that owning code is a bad thing. The more you have, the more work you have to look after it! </p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.027.jpg" alt="Image of slide number 27" />
            </div>
            <div class="slide-notes">
                      <p>As Bill gates said:</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.028.jpg" alt="Image of slide number 28" />
            </div>
            <div class="slide-notes">
                      <p>Secondly, Network effects.  The more people looking at, using, working on a body of code, the more likely it is that bugs in it will get fixed. </p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.029.jpg" alt="Image of slide number 29" />
            </div>
            <div class="slide-notes">
                      <p>By getting other people outside the bank to use this, we have a chance of actually making something good, and lasting, like the Concordion contribution. </p>

      <p>Not something that will be thrown in the bin when I or my team-mates leave.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.030.jpg" alt="Image of slide number 30" />
            </div>
            <div class="slide-notes">
                      <p>The third reason, and maybe the main one, is that for Deutsche bank, it looks cool.  It looks impressive that they are contributing code for others to use.  They do press releases on this sort of stuff!   And I guess this is really a good reason for everyone.  Building things, and giving them away for others to use is a kind of charity.  So if you can possibly make it happen, then you should.  </p>

      <p>I don’t think that this Symphony library will change the earth, but if it saves people time to work on more important problems, then I think that’s a good thing.  </p>

      <p>That’s what Open Source does - it allows people to worry about the big picture, the important problems, rather that getting bogged down in all the nuts and bolts of coding.</p>


            </div>
        </div>
        
        <div class="slide slide--bordered">
            <div class="slide-image">
                <img src="/img/presentations/OpenSource/images/images.031.jpg" alt="Image of slide number 31" />
            </div>
            <div class="slide-notes">
                      <p>That’s it!  My name’s robmoffat, you can find me on GitHub if you want - please star my projects while you’re there!  </p>


            </div>
        </div>
        
    </div>

    <p class="credits">Made with <a href="https://keynote-extractor.com">Keynote Extractor</a>.</p>

