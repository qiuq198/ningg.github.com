---
layout: post
title: Lecture 8--Doing Things That Don't Scale, PR, and How to Get Started
description: 阅读原文
published: true
category: ycombinator
---

> 原文地址：[Doing Things That Don't Scale, PR, and How to Get Started][Doing Things That Don't Scale, PR, and How to Get Started]

## Doing things that don't scale

### Stanley(founder of DoorDash)

Thanks for having me! I'm Stanley, the founder of DoorDash. It's really amazing to be here, because it wasn't actually that long ago when I sat in your seats. I was class of 2014, graduated in CS, as well as my cofounder Andy. For those of you who don't know what DoorDash is, we're building an on-demand delivery network for local cities. I want to start off with this photo that I took a few months ago. This was the night when we just raised our series A. I took this photo as I was walking back to where I lived; I actually lived in Roble at the time on campus. I took this photo because I realized just how ridiculous the combination of things I was holding in my hand was at the time. I was holding my CS247 homework, my tax forms (it was April – so I had to fill out my tax forms), that yellow speeding ticket, and right below that was a $15 million piece of paper I had just signed from Sequoia. And that kind of summarizes just how ridiculous our journey has been, doing this while I was at Stanford, and then transitioning this to an actual startup. I want to share with you that story today.

It all began two years ago in a macaroon store. It was my junior year at Stanford during the fall quarter. At the time, I was really passionate about building technology for small business owners. I sat down with Chloe, the owner of Chantal Guillon, a macaroon store in Palo Alto at the time, just interviewing her, trying to get feedback on this prototype we'd been working on, and also just learning about what her problems were in general. It was during this meeting when Chloe first brought up this problem of delivery. I remember she brought down this really really thick booklet. She showed me pages and pages of delivery orders, and a lot of these orders she had to turn down because there was no way she could have fulfilled them. She had no drivers, and she ended up having to personally deliver all these orders. That was a very interesting moment for us.

Over the course of the next few weeks, we talked to around 150 to 200 small business owners, and when we brought up this idea of delivery, they kept agreeing with us; they would say, "You know, we don't have delivery infrastructure. It's such a huge pain for us. There aren't any good solutions out there." This led us to wonder, delivery is such a common thing, such an obvious thing; why hasn't anyone solved this yet? Like, we must be missing something here right? We thought it was maybe because people had already tried this in the past, but they failed because there wasn't consumer demand for this. We asked ourselves, "How can we test this hypothesis?" We were just a bunch of college kids at the time. We didn't own trucks or delivery infrastructure or anything like that; we couldn't just build a delivery company overnight right? So how could we test this assumption we had?

We decided to create a simple experiment with restaurant delivery. We spent about an afternoon just putting together a quick landing page. When I went on the Internet, I found some PDF menus of restaurants in Palo Alto. We stuck it up there and added a phone number at the bottom, which was actually our personal cell phone number. And that was it. We put up the landing page and called it PaloAltoDelivery.com. This is actually what it looked liked (PowerPoint slide): It was super simple, ugly, and honestly we weren't really expecting anything - we just launched it. What we wanted to see was just would we receive phone calls, and if we got enough phone calls, then maybe this delivery idea was worth pursuing.

So we put it up there; we weren't really expecting anything, and all of a sudden we got a phone call. Someone called! They wanted to order Thai food. And we're like, “This is a real order; we're going to have to do something about it.” So we're in our cars and we're like, "We're not doing anything right now, might as well swing by, pick up some Pad Thai, and let's try to see how this whole delivery thing works." And we did. We delivered it to some guy up on Alpine Road I remember. We asked him, "How did you hear about us, what do you do?" He told us he was a scholar, and then he handed me his business card and told me he was the author of a book called Weed the People. That was our first ever delivery. It was like the best delivery/worst delivery you could ever ask for.

And then yeah, the next day we got two more phone calls. The day after that we got five, then it became seven, and then it became ten. And then soon we began to gain traction on campus through PaloAltoDelivery.com which is pretty crazy, because think about it: This was just a landing page. You had to look up PDF menus to place your orders and then call in. This isn't exactly the most professional-looking site, yet we kept getting phone calls; we kept getting orders. And that's kind of when we knew that we were onto something. We knew we found a need people wanted when people were willing to put up with all of this.

I think another key point to remember is we launched this in about an hour. We didn't have any drivers; we didn't have any algorithms; we didn't have a backend; we didn't spend six months building a fancy dispatch system – we didn't have any of that. We just launched because at the beginning it's all about testing the idea, trying to get this thing off the ground, and figuring out if this was something people even wanted. And it's okay to hack things together at the beginning.

At YC there's a mantra we like to talk about that is doing things that don't scale. So at the beginning we were the delivery drivers. We would go to class, and then after we would go deliver food. We were the customer support; you know I sometimes had to take phone calls during lectures. We spent afternoons just going down University Avenue just passing out flyers trying to promote DoorDash. We didn't have any dispatch system so what we had to do was use Square to charge all of our customers. We used a Google Doc to keep track of our orders. We used Apple's Find My Friends to keep track of where all of our drivers were. You know, just stuff like that, just hacking together solutions to try to get this thing off the ground. In fact at one point we were growing so fast that Square actually shut us down because we were under suspicion for money laundering. I mean think about it, we were getting small chunks of $15-$20 orders coming in at a rapid pace. Luckily, my cofounder Tony worked at Square so he just emailed some buddies there and everything was solved.

有个口头禅：doing things that don't scale，自己做客服、没有复杂的调度系统，利用现有的工具，把事情做起来。

Another thing about doing things that don't scale is it also allows you to become an expert in your business, like driving helped us understand how the whole delivery process worked. We used that as an opportunity to talk to our customers, talk to restaurants. We did dispatching which helped us figure out - you know, we manually dispatched our drivers and that helped us figure out what our driver assignment algorithms should look like. We did customer support ourselves, getting real-time feedback from customers. I remember for the first few months when we got started, we would manually email every single new customer at the end of every night asking how their first delivery went, and how they heard about us. We would personalize all these emails: If I saw someone order chicken skewers from Oren's Hummus, we would say "Oh I love Oren's Hummus. How are your chicken skewers? How did you hear about us?" Feedback like that was really valuable, and customers really appreciated that.

doing things that don't scale 还有一个好处：让自己变为自己领域的专家，例如：自己开车，让我们更好的理解整个送货过程是怎么运转的；利用做事的时间，跟客户交流、跟供应商交流；自己做客服，实时获得用户的反馈；在前几个月，我们每天晚上都会手动向用户发送Email，询问他们对首次服务的感受，以及他们是通过什么途径知道我们的，我们的交流都是个性化的，这样用户的体验会很好。

I remember this one time - this was during YC - we had just come out of a meeting with one of our restaurant partners, and we heard about this ice cream place that had just opened up on University Avenue called Cream, and we wanted to go try it out. Then all of a sudden, our cofounder back at our office/house texted us saying "Oh we need drivers on the road; we got a huge spike in demand." So we debated for maybe about 10 seconds if we should go get ice cream or should we go deliver. We obviously went to deliver, but that kind of became our motivation on scaling, like you know, if we would scale, then we could go get ice cream next time.

Now of course we scale across different cities. Now we have to worry about building automated solutions, building dispatch systems, and figuring out how to match demand and supply - all that fancy technology stuff. But none of that mattered at the beginning because at the beginning it's all about getting the thing off the ground, and trying to find product-market fit.

初期规模很小，所有的工具都使用第三方的，因为初期的关键是把事情做起来，行动起来，让事情运转起来，找到市场和需求的契合点。当然，现在我们已经扩大了规模，创建自动化解决方案、构建调度系统、构建需求和供给方案。

Just to summarize, there are three things I would say I learned from doing DoorDash. First, test your hypothesis. You want to treat your startup ideas like experiments. The second thing is, launch fast. We launched in less than an hour with a really simple landing page. And finally, it's okay to do things that don't scale. Doing things that don't scale is one of your biggest competitive advantages when you're starting out, and you can figure out how to scale once you have your demand. And then maybe once you've scaled, then you go get that ice cream. Thank you

几点：

* 测试你的假设：将startup idea当作实验一样进行；
* 快速行动：我们在一个小时内就行动起来了；
* do things that don't scale，是优点，会带来巨大的好处，你可以在规模还不大的时候，负担很小的时候，思考如何进行规模化；

Q: How did your first customer hear about you?

A: Our very first one, I have no idea. We just launched in Palo Alto; we didn't do any marketing, so I assume he just must have typed in “Palo Alto delivery” into the web browser. And then after that, we did barely any marketing. I think I sent out one email to my dorm, and that was about it. It was all through word-of-mouth. And that kind of just validates how strong the need we found was when people are just talking about you, and willing to put up with a terrible user experience, terrible design, and stuff like that.

Q: When you started, it seemed so obvious to you, you were wondering why, what the reason was nobody had done this before. What's your answer now looking back?

A: Looking back I think the biggest thing is mobile. Now everyone has one of those in their pocket, and we saw that trend and thought what if you could design a delivery system that was entirely based off mobile, where you didn't have to have any infrastructure, or delivery fleets. Instead of hiring drivers full-time or purchasing vehicles, what if you could tap into more of an on-demand pool of independent contractors, and only send orders to them when they have time. So that's kind of the insight we had; everything was done through mobile.

产生新的机会在于：人手一个的智能手机*（移动互联网）*。

Q: Did you know you were going to be a startup, or were you just making some money at first?

A: At the time we were all just really passionate about building technology for small business owners, and obviously this delivery thing came out of an experiment with the landing page. It was literally an experiment. We weren't expecting anything, and it just took off, and we just went with it. And logistics was always something we were really passionate about as well, like logistics of transportation – the perfect fusion of how you can help small business owners through delivery.

前期只是希望构建一个小的商业模式，并对此充满激情，可以说最初只是在激情的试验、认真的试验；事情在发展，我们在追着事情向前走，并没有想过尽快赚钱。

Q: Did you launch the mobile site first or the website?

A: We started with this landing page right here which took us about an hour to launch.

Q: How does DoorDash stand out amongst a very competitive space?

A: At the beginning consumer demand was never a problem, even up until now. So for us it's just about finding a need and just focusing on serving that demand. At the beginning competition doesn't really matter.

Q: How long did it take you to get incorporated into a company?

A: We launched in January 2013, and then we did YC that very summer. When we decided to take this idea through YC, we incorporated.

Q: Where do you plan to go beyond food delivery?

A: For us when we started DoorDash, it was always about helping small business owners and figuring out how you served this for any local merchant whether you were a macaroon store, restaurant, or furniture shop. That's still our focus; that's our long-term vision. For now we are just focused on restaurant delivery as a way to scale, but ultimately that's where we want to end up in.

## Walker(founder of Teespring)

Sam Altman: Next is Walker Williams, founder of Teespring. He's been working with YC for about a year and a half, something like that. I almost rejected him, which sounds like a dumb idea, but now they're making hundreds of millions of dollars in revenue, so very luckily I did not. Walker is also going to talk about doing things that don't scale.

Walker: Thank you guys for having me! My name is Walker; I am the CEO/Founder of Teespring. For those of you who don't know what Teespring is, we are an e-commerce platform that allows entrepreneurs to launch products and apparel brands without risk, cost, or compromise. Today the company is about 180 folks and we ship tens of thousands of products each day. I want to talk to you about one of the most fundamental advantages you have as a start up, and that's that you are able to do things that don't scale.

I define things that don't scale as things that are sort of fundamentally unsustainable; they will not last; they will not bring in the millionth user. Where they break, it's usually time but it could be a number of other things. But it's really growth strategies that won't take you to a million users. There are three places I want to focus on today. First one is finding your first users. The second one is turning those users into champions, and the third one is finding your product/market fit.

关于do things that don't scale，打算说3点：

* 找到第一批用户
* 使第一批用户获得成功/便利/优势
* 找到产品和市场的契合点

So finding your first users: The first thing you have to understand is that there's no silver bullet for user acquisition. You know, everybody, and this includes me when we got started, looks for that dream solution, that paperclip campaign that has tremendous ROI, some accelerating partnership that's going to springboard you into the stratosphere, and affiliate agreement; something that solves it for you. But the reality is for the vast majority of companies and in fact for every company that I've had the chance to speak to the CEO of, that's just not possible - those are unicorns. And most of the companies that from the outside look like they've had this dream growth curve, the reality is that those first users were impossibly hard to get. Let me tell you about the story about this ridiculously unsustainable business.

So this is Teespring in 2012 (PowerPoint). When we first launched, the business couldn't have looked worse. It took days of meetings; we had to offer free designs, and days of revisions back-and-forth, we'd have to launch the product ourselves, we'd have to do the social media, all to sell about 50 shirts to a local nonprofit and generate about $1000 of revenue. Anybody looking in would've said, "You guys have to give up, this is a terrible idea." But as time went on, those users started to add up, and I think something you have to understand is when you first launch a company, just by virtue of the fact that it's a new product, you're going to be bad at selling it right? You've got no idea what the pain points of customers really are. You've never sold that before. You don't have any success stories to point to, or testimonials. Those first users are always going to be the hardest.

获取第一批用户，并不容易，你要清楚，第一批用户是很艰难的，因为产品第一次出来，不可避免有很多问题，初期一段时间内用户没有增长是可以提前预期得到的。

And so it's your responsibility as a founder to do whatever it takes to bring in your first users. It's going to be different for every company. The common thread that I hear is, founders need to spend personal time and effort, a lot of their personal time and effort to bring those users in themselves. It could mean a number of things - anything from sending 100 emails a day, getting on the phone and just calling as many people as you can, going through a network like Stanford or Y Combinator. Anything you can do to just get that first user. I really equate it to pushing a boulder uphill. And if you think of a smooth hill when you get started, the incline is the steepest and those first inches are the hardest. But over time as you get farther and farther, the incline steadies out, it gets easier, and eventually you reach a point where you're at the top of the hill and the boulder starts to roll on its own.

找到第一批用户，这就是你作为founder的责任了，想尽一切方法去找到第一批用户：每天发送100份邮件、找人聊天等等；如果产品满足了需求，则，用户会像雪球一样越滚越大。

And so for those first users, you cannot just focus on ROI in the sense of time. Do not expect to spend an hour and return thousands of dollars. Maybe Stanley was one of those unicorns - really incredible story. But for most of us, those first two users are going to take a lot of handholding, a lot of personal love, and that's okay - that's essential for building a company. The one caveat of that is, I don't recommend giving your product for free. And there are plenty of exceptions to this rule, but in general, cutting costs or giving the product away is an unsustainable strategy I wouldn't recommend. You need to make sure that users value your product. And you know, people treat products that are free in a much different way than a paid product, and often times it can give you a false sense of security like, "Oh we're getting all these users; surely we can convert them to paid."

对于第一批用户，不要只想着 ROI （投资回报率，Return On Investment）；但并不建议免费提供产品，你需要知道用户看重你的产品；免费产品和收费产品在用户看来差异是很大的。

The second aspect is what happens when you get those users? How do you turn those users into champions? A champion is a user who talks about and advocates for your product. Every company with a great growth strategy has users who are champions. The easiest way to turn a user into a champion is to the delight them with an experience they are going to remember, so something that's unusual or out of the ordinary – an exceptional experience.

第二点：让第一批用户获得成功/便利/优势*（超出预期）*，这样他们会讨论你的产品，为你的产品代言；如何达到这样的效果，保持与用户的互动，听取用户的意见，坚持下去。

The easiest way to do this early, and again something that is completely unsustainable - it's not going to scale forever - is to just talk to those users. People will say this all the time, it's sort of the core tenant of Y Combinator, is talk to users. I cannot stress how important it is that you spend a large chunk of your time talking to users. You should do it constantly, every single day, and as long as possible. Today at Teespring, I'm still the catchall email address, so anytime anybody misspells "support" or writes an email address that doesn't exist, I get that email. And so I still do about 10 to 20 customer service tickets every single day; I spend hours each night reading every single tweet, probably a little bit OCD, but that's okay; I read through all the Teespring communities. You're never going to get a better sense for your products than actually listening to real users. Especially in the early days, the product and the feature set you launch with is almost certainly not going to be the feature set that you scale with. So the quicker you talk to users and learn what they actually need, the faster you can get to that point.

There are three ways to talk to your customers. You can run customer service yourself. Up until Teespring was doing about $130-$140,000 a month, my cofounder Evan and I did everything in customer service. This is one where there's going to be an instinct to quickly pass off, and that's because it's painful. Even today when I open our customer service portal, I have an emotional reaction where my stomach sinks because it sucks talking to so many users who have had a terrible experience, and it's painful that something that you love and put so much effort into, to know you got it wrong or somebody didn't treat them right. But it's so important that you go through that and learn what you need to build, and what you need to fix.

The second step is to proactively reach out to current and churn customers. Churn customers are customers who have left. This is one that often falls by the wayside in the pursuit of new customers, but you want to make sure that your customers are having consistent good experiences; you don't want to take your current users for granted. When a user actually leaves your service, you want to reach out and find out why, both because that personal outreach can make the difference between leaving and staying; sometimes people just need to know that you care and it's going to get better. And even if you can't bring them back, there's a chance that you can learn from the mistakes you made that caused them leave, and fix it so you don't churn users out in the future in the same way.

想办法联系上流失用户，更他们聊天，即使无法挽回他们，也能从他们的建议中吸取教训。

Finally, the one I'm probably most OCD about is social media and communities. You need to know how people are talking about your brand. You need to try to make sure that when somebody does have a bad experience, and they're talking about it, that you make it right. Problems are inevitable: You're not going to have the perfect product; things are going to break; things are going to go wrong. That's not important. What's important is to always make it right, to always go the extra mile and make that customer happy. One detractor who's had a terrible experience in your platform is enough to reverse the progress of 10 champions. That's all it takes, is one to say, "No you shouldn't use those guys for X reasons," to ruin a ton of momentum.

到社交媒体和论坛上去看看人们怎么讨论你的产品，讨论的好的地方、坏的地方，用户的感受是什么样的。

There are examples in the early days where we would mess up massive orders. We'd print out colors slightly wrong; it would be the wrong size, and it would be half of our GMV for that month. We would know we got it wrong, and the customer would be unhappy, and the instinct was to say that it was only a little bit off, not completely wrong, or that it would be fine. But the reality is you just have to bite the bullet and make sure it's right. And the customers who are originally the most frustrated tend to turn into the biggest champions and the longest term users.

The last one I want to talk about is finding product/market fit. What I mean by that is the product you launch with will almost certainly not be the product that takes you to scale. So your job in those early days of a startup is to progress and iterate as fast as possible to reach that product that does have market fit. And as engineers your instinct is building a platform that's beautiful, clean-code, and that scales. You don't want to write a duct tape code that's going to pile on technical debt. But you need to optimize for speed over scalability and clean code. An example of this is in the early days, we had a couple enterprise customers come in, sort of bigger nonprofits, and say "Hey, we really like your service, but you're missing these fundamental things, so we're not going to use it." And we looked at what it would take to build out those features, and we weren't sure if they were going to work out long-term, but we wanted to try it.

第三点：找到产品和市场的切合点。实际上，起步的产品很大概率上都不是可以规模化的产品，

My cofounder Evan, who is our CTO and a million times better developer than I am, ran the math and figured out that if we did it the right way, it was going to take about a month to build out these features. A month for a startup – you live in dog years – a month is a year, and that just wasn't going to do. So he actually went out and duplicated the code-base, duplicated the database, and was able to basically build a completely different product so that he didn't have to worry about the existing users to serve these enterprise customers. We gave them the tool, they on-boarded, and generated a lot of revenue. Eventually we learned what features were core, and we integrated them into the core product. But what would've taken a month, we were able to do in three to four days.

如果产品的底层技术不行，将会买下巨大隐患，特别是在规模化的时候；而如果要做好底层技术，最短也需要1个月，这对于startup来说，比一年都要漫长，将错过无数的机会，怎么办？并行启动一个新的产品/技术线，上面按步骤的进行架构；而一个基本能用的系统，现在线上用着；等到需要的时候，可以直接切入新技术系统。

A great rule of thumb is to only worry about the next order of magnitude, so when you have your tenth user, you shouldn't be wondering how you are going to serve one million users. You should be worried about how you're going to get to 100. When you're at 100, you should think about 1,000. It's one of those things where necessity is the mother of invention, so when you hit the breaking point (the Twitter Fail Whale is a great example), and in Teespring there were month-stretches where every single night the site would crash - every night. Every single person on the team would go to sleep with their phone on loud, under their pillows, so inevitably when their phones went off, we could quickly restart the server and go back to sleep; this would happen daily. But the reality is that it was worth it, and you'll end up with these huge pain points and all this technical debt and regret, but it's worth it just to get to that end goal and that product fit faster. You will make it work; you will survive. Those bumps are just speed-bumps, and speed is so so important early.

另一个要点：不要过度提前担心，只有10个用户的时候，不要想100万用户的事情。最佳的做法：10个用户的时候，思考100个用户的做法；只考虑接近的一个量级*（只考虑最近的未来，并位置准备？）*；简单来说：因需而设。初期时，成长速度很重要。

The lesson that I've been learning lately is that you want to do things that don't scale as long as possible. There's not some magical moment; it's not Series A, or it's not when you hit a certain revenue milestone that you stop doing things that don't scale. This is one of your biggest advantages as a company, and the moment you give it up, you're giving your competitors that are smaller and can still do these things, that advantage over you. So as long as humanly possible, as long as it is a net positive, you need to spend time talking to your users, you need to move as fast as possible in development, but don't give it up willingly; it should be ripped from you.

To practice what I preach, I want to give you guys my email address. If you guys have any questions, if you want to learn about Teespring, or if you want to print some T-shirts (fingers-crossed), just shoot me an email. I'd love to help and I'd love to speak to you.

The last thing is, we've created an official "How to Start a Startup" T-shirt with Sam. All proceeds are going to Watsi.org. I couldn't miss this opportunity to sell, so if you guys want to grab one of the official tees, just go to teespring.com/startup; it's supporting a great cause.

Thank you.

Q: What convinced you to get into the market of T-shirt printing when there is so much competition in this business?

A: I think there are two factors to it. First, I completely agree. From the outside, people have been telling us that this is a silly idea since day one in every order magnitude we reach. People will come and say, "This is a terrible idea. Why are you doing that?" But the reason why we launched Teespring is because we ran into a personal pain point. We identified a need and found that there were no great current solutions. I was a student at Brown trying to create a "Remember the Bar" shirt for a dive bar that got shutdown, and I realized that nothing matched my needs. And so because I knew that I had that pain point, and I knew there was market fit, and I had seen people adopt the product, I knew there was something there. And it was also one of those things where you could sort of feel the wind on your back where people were adopting the product quickly. The pain point was clearly there; it's not a met need. So I would say that most times, great ideas start out by looking like the silly ideas, and then you can feel out whether or not there is a scalable business by how people are adopting it and whether it is possible to bring customers onboard.

解决个人的痛点*（强需求）*，意识到这个需求的存在，并且，没能找到好的解决方案，因为如此，才开始做这件事。

Q: Are nonprofits your biggest customer base?

A: No, today our biggest customer base is entrepreneurs who are trying to build brands and businesses. We have a little over 1000 people who make their full-time living on Teespring today via brands they've launched. And the other side is influencers, so YouTube stars, Reddit communities, bloggers who want to add product merchandise as a way to create a brand and monetize that affinity. Those are our two biggest markets. We still work with a lot of nonprofits, and love working with them. They are still part of our business, but just not the majority.

Thank you.

## Public Relations

Sam Altman: Now we have Justin Kan. Justin was the founder of Kiko, and the Justin.tv which became Twitch. He is going to talk about Public Relations.

Justin: I’ve started a lot of start-ups, but I think you've heard a lot of awesome "how I got started" stories, so I'm going to talk about something very specific that people always have questions about, which is press: how do you get it and how does it work? This is kind of like an abridged version of what we talk about at Y Combinator. Hopefully you guys will find it helpful.

When most people get started with entrepreneurship, they think about press and being in the press as something that happens magically. They think about journalists out there, trying to get the best stories - it's like a meritocracy - which is absolutely not the case.

很多企业家，都想出现在新闻媒体上。实际上，你应该考虑好，自己希望哪些人在新闻媒体上看到你，定位好细分人群，以及向这些人传递什么信息*（简单来说：要让谁？知道什么？）*。

Before you think about press, one of the things you really want to consider is who you want to reach, as well as your actual goal. I know when I got started I wanted to be in the news because I thought that's what you did as an important company. It turns out that if you don't have any goals, you're not going to achieve them - that's true of pretty much everything. And with press, if you aimlessly just want to be covered, it's not going to do anything for your startup. If you don't have an actual business goal, then it's not a good use of time.

如果没有目标，就不会达到这些目标*（此处的目标是指稍微有难度，需要付出努力的目标）*。

So there are many different goals. With Socialcam, which is a spinoff of Justin.tv, our goal was to be known as like video Instagram and be thought of in that context. When it was time to pitch to our Silicon Valley investors and influencers, we really wanted to get covered in tech press and be positioned as this new, hot social app.

With Exec one of my goals was to get customers. Exec was like a local cleaning service, and our goal was to get people in San Francisco to use it. It wasn't useful to get national press because 99% of those people couldn't use it. So we targeted initially local press like SF Chronicle, who would directly talk to people who could potentially use our app. TwitchTV, which is probably what you guys mostly know, is like ESPN for gamers, kind of like a live stream community for gamers. Our goal was to reach the gaming industry. Now it's like 55 million uniques and people in the gaming industry know about it, but when we started nobody really knew that; it wasn't a place to advertise, we were a very small gaming community. Our goal was to get people in the gaming industry, whether they were developers or advertisers, to think about us as an important place where influencers were. So we really targeted industry trades and game dev blogs. Stuff that the industry was reading.

So what's an actual story? I think there's a bunch of different types of stories, but these are the ones you usually see in startups. Product launches are when you launch a different version of your app.

There's fundraising; for whatever reason, the press loves to write about fundraising even though it's not very interesting. So like if you raise a million dollar seed round you can pretty much get that covered.

Milestones are metrics, like if you've achieved one million dollars a week in revenue. The company that bought Exec just announced that they achieved one million dollars a week in revenue, and it was covered pretty widely. Business stories, which happen when you're already a successful company, The New York Times, The New Yorker, or Business Magazine, will want to cover your startup story. You don't have to worry about that in the beginning.

What I like to call stunts - I don't know if you guys remember, but a couples years ago, this YC company called WePay dropped a block of ice with money frozen in it outside of a PayPal developer's conference because PayPal was in the news for freezing various developers' account. It was widely covered because it was such an interesting thing, you know, it got them in the story, they wouldn't have been talked about in the context of PayPal at all.

Hiring announcements: If you're a big enough company and you hire someone really important, people will want to cover that.

And finally contributor articles which would be you writing some sort of industry overview or some opinion piece, maybe a tech blog, stuff like that.

什么时候，新闻媒体会关注到你的产品/公司？他们关注到之后，会如何报道？如何驾驭并设计这种情况？

Basically any of those things can be a story. Something that people usually don't think about when you're trying to start a startup is, when you start a startup, you think that everything you're doing is interesting, but that may not be true for other people. What you really need to think about objectively is, if I wasn't the founder of this company, would I want to read a story about what I'm pitching? So your incremental feature release or your 2.01 feature release might not be interesting just because you added "Find Your Contacts" on Facebook. You really want to take a step back before you invest the time in actually trying to pitch a story, and think, "Will anyone actually really want to read this?" What journalists and bloggers are really looking for are things that people actually want to read.

The other thing is you don't actually have to be very original - your press doesn't have to be original. It just has to be what I like to call "original enough." You don't want to be the second-coolest company to raise $5 million on Kickstarter - the first guy gets all the news. The first video game console to raise $10 million on Kickstarter was huge news because they were the first in that category, even though a lot of people had raised a lot of money for Kickstarter before. Think about your stories in the context of other things that have been written and if they're like novel enough or aren't something that was just written about in the news.

So one of the actual mechanics of getting the story (this is pretty tactical), if you want to get your news in the press, basically there are some really easy steps to follow: Think of getting press like a sales funnel. You're going to talk to a lot of people but not all of them are going to convert – so you shouldn't be upset when one individual person or reporter doesn't write your story. The first thing is you have to think of it like a story. The second thing is you want to get introduced to any reporter or multiple reporters who are going to write about your thing. It's much much easier, just like any business development, to get in touch with them through someone, rather than cold emailing them.

The best thing to do is go to entrepreneurs who were just written about or friends who were just covered on TechCrunch, get them to introduce you to that reporter who wrote about them. The reason that's good is because from the entrepreneur's perspective, the easiest thing in the world to do is to introduce you to the reporter who already wrote about them. They don't need anything else from the reporter, and they're actually doing that person a favor if the story is interesting; it's not like you're asking for intros to investors or people they would want to hire as employees. And then from the reporter's perspective, they're getting introduced to someone who they already vetted as interesting; they're getting an intro from someone who they believed was interesting enough to write about, so by the transitive property, they're going to think you're probably interesting.

So you get an email from this guy who introduces you to the reporter, and you want to get in contact with them with enough time to get them to write a story - let them know probably a week in advance or more, because they're not going to drop everything they're doing to just write about your news. A lot of people, especially first time entrepreneurs, will come and say "Justin I'm launching this product tomorrow. Can you get me in TechCrunch?" That's probably not going to happen unless you already have a relationship. The best thing to do is give yourself some lead time; get that intro in advance.

So once you've set a date for your news to go out – you’re going to launch a product in two weeks - you have this intro, you've set up some sort of meeting, and you really want to get the reporter to invest time and effort into you because there's a sunk cost fallacy at play. Basically, the more time they spend with you, the more likely they are to write about you. The best thing to do is get a face-to-face meeting. Some bloggers don't actually want to meet face-to-face, but like if not that, then get a phone call. The worst thing to do is just have an email exchange because it's very easy for them to forget about it or ignore it.

The next step is actually pitch them. What I do is actually write out the ideal story that I want to see published in bullet points, and memorize it. And when I have a conversation with them if it's in person, the conversation is structured like my outline, and they'll be taking notes. Then they'll go transcribe those notes into a story. So basically what I wrote will be translated into an actual story. By preparing, you can actually control more of the conversation and not forget critical things like mentioning your cofounder's name or the awesome features in your app are.

If I'm doing this over the phone, I'll make sure to have the bullet point list in front of me and I will make sure to walk through a conversation that includes all those things. So you have a pitch, they take notes, and they're going to write the story at this time. The next thing to do is follow-up like a couple days or day before your actual news goes out. You want to send them an email that says "This is the time we're launching the app; thanks for meeting; here's collateral if there are any videos, photos, or screenshot you want to include; how to spell your cofounder's name or your name. I just include all the information that I really care about and bold it. And then that's it. Hopefully the day comes when you press submit on the release to the App Store and at the same time, they released their article on TechCrunch and you are famous.

So a lot of people ask us about PR firms. So I think in the beginning it's kind of like, everything you do in a startup, you want to do yourself. And it's actually pretty easy especially with tech press and bloggers who constantly need new things to write about. I strongly encourage people to try it themselves, and kind of get started by learning the process themselves before they hire anyone. One thing I'll say is that firms can only help you with the contacts and the logistics, but they can't help you know what's interesting about your company, or – I'm never been able to have any one that’s told me what the stories that I'm producing on; they've only been able to give me a list of reporters I might want to contact. So you really have to be responsible about thinking about what's interesting about your company and what you're doing, you know, the roadmap of interesting things that you're working on.

They're also really expensive. I think we were spending about $5,000 and $20,000 a month, and for various firms, it’s a lot - for a startup right? It's generally not a good use of money especially in the early days. Getting press is a lot of work, so you should really make sure it's worth it. Getting press is like a vanity metric: It feels like you're being successful because many successful companies like Facebook are covered in the press all the time, but it doesn't actually mean you're successful; it doesn't actually mean you're making money, getting users, or making those users happy.

Sometimes it's a really good strategy for getting your first hundred or two hundred or a thousand customers, but it's really not a user-scalable acquisition strategy, so it's really something that's just a bootstrap; you can't just get like infinity articles written about you. Eventually people are going to get tired of hearing about your company, and usually that happens really quickly right? The pull point about news is that it's new, so it's pretty hard, unless you’re like Google, to get covered in the press every week. If you decide it's worth it though, that you do want to have a regular heartbeat of news, you're thinking about what you're doing that matches those seven story types in the future. When I was working primarily on marketing and PR, I would make a schedule on the calendar of when we're going to launch things and make sure to space them out, but have them appear at regular intervals so people didn't want to forget about us and we could maximize our coverage.

You also want to keep your contacts fresh; it's really a relationship business. Once someone writes about you, you should keep up with them because they could potentially write about you in the future. You're more likely to do something for someone that you've already done something for in the past. I would try to establish good relationships with a couple reporters that you could go to for breaking news; it could come in handy later if you're fortunate enough to have people writing negative things about you; your relationships will help you get out your side of the story.

The last thing is kind of like a golden rule or more of like a "pay it forward:" You should help your fellow entrepreneurs get coverage because they'll help you get coverage. The best way to get coverage is really through these introductions. Whenever I'm meeting with reporters, I throw out names of other things I think would be interesting stories for them, and usually that comes back. The reporters like it because you're helping them find interesting stories, and you're more likely to get leads back from those entrepreneurs that you helped out.

If you're interested in learning more about press, here are two resources that I really like: Jason Kincaid, who is a former TechCrunch reporter, goes through a great overview that covers a lot of things I talked about in more depth. And then kind of an evil resource is this book called Trust Me, I'm Lying which was written by a former marketer at American Apparel. He talked about ways that he evilly manipulated the press, but I think it's a pretty good look into the psychology of how stories spread on the Internet; it's valuable to take a look at. Cool, that's basically it.

Q: When is the right time to start worrying about press altogether?

A: The first time I launched my first startup, you know my first products, for a lot of them we got zero attention and we didn't really know how we could get 100 users. I think it's a really fine way to get 100 users, and a lot of companies at YC when they first launch their product, we'll encourage them to get out and do one TechCrunch story to get a few people to see it. It's good to get in the practice. I wouldn't obsess getting coverage in multiple outlets or anything like that in the very beginning.

Q: How much of a role did you guys play in getting the Pokemon thing out?

A: Twitch had this thing called "Twitch Plays Pokemon" where developers set up a Pokémon Gameboy game that was controlled by chat, so millions of people would be typing in A or B, and the character would wander around aimlessly. That was a huge news story. I think what we did was set the stage by having other news stories that someone from the BBC would Google "Twitch" and be like, "What is this crazy thing that everyone on Reddit is talking about?" They would have some context. The other thing is we didn't come up with the idea for Twitch. That was like fortuitous, but we helped give it legs by making the company available to talk to reporters and suggesting follow-up stories, not only about "Twitch Plays Pokémon" with 100,000 people watching, but also stories about when they beat the game or when Twitch played Crystal, the new Pokémon version. We didn't originate the story; it was the community who I think really originated it.

Okay I think that's it, thank you very much!






















[NingG]:    http://ningg.github.com  "NingG"




[Doing Things That Don't Scale, PR, and How to Get Started]:						http://genius.com/Walker-williams-lecture-8-doing-things-that-dont-scale-pr-and-how-to-get-started-annotated




















