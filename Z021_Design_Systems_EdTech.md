---
title: 28. Design Systems and EdTech
layout: default
nav_order: 30
---
# Design Systems and EdTech

### [Previous Chapter](Z020_The_Use_Of_AI_And_Technology.html)

## **Short Answer**

> “Any idiot can build a bridge that stands, but it takes an engineer to build a bridge that barely stands.”
- Anonymous
  - *Finding the source for this quotation is a Herculean task, so if someone does know the original source, let me know.*

Everyone is a designer. Not everyone is a *good* designer.

Even if you can design well, you'll still deal with *business problems* (not just design problems!), people management issues like managing upwards, and communication. These problems, and requirements to meet, may also come from non-technical people.
- If people cared about only two things on design, it'd probably be if it makes money and is the interface intuitive. 
- If you cannot figure out what business question your solution answers and the values it provides, you're likely designing without intent.
- Sometimes a problem is like just finding the best word, like good vs affordable.

Most solutions and traditional projects may be abandoned because shipping/making a product is fun, but *selling* a product is not fun. Even a single "general-use" solution is unlikely to *efficiently* address every circumstance/problem. What one person considers pointless, another person deems essential.

If you're not sure where to find problems to solve, think of something that already exists and see if you can improve it in one of these three areas:
1. Reliability: Ability to continue working despite issues; resilience
2. Scalability: Handling increased loads, stress, etc. without breaking down; growth
3. Maintainability: Adaptation and change over time; readability

A complex design is always worse than a simple design if they perform at the same effectiveness/efficiency. Complex designs are, due to the nature of complexity, more prone to failure compared to simple designs. 
- Use the simplest solution that meets your requirements.
- [Dr Richard Cook in *How Complex Systems Fail*](https://how.complexsystems.fail/) does a much better job than me succinctly describing complexity issues across multiple industries (2000).
- Creating your own systems, setups, etc. makes sense when it provides a competitive advantage, otherwise it is a waste of time.

**Your most important question is "Why?"** You don't jump straight into things or overengineer solutions when it's not necessary, especially if you'll never see the problems requiring advanced solutions. Acquire information and clarify requirements/context, when able, *before* working or you risk wasting time, money, and sanity.
- What people actually do is worth more than what people say they do.
- Sometimes all it takes is listening to or watching someone to find out nothing "fancy" was needed.
- People don't always know what they need, but may know what problem they need solved.
- Theory and testing are equally important.

## **Long Answer**

"Design" can happen in many areas. You could design a house, an application, a piece of art, and plenty more. Many concepts rooted in design are cross-disciplinary, though certain design concepts work better in some fields over others.

It's also easier to build things that you can verify, usually with hard data, solves problems people have. If you start designing with that information already, you could skip a lot of busy work and take less time going from idea to concept to reality on your design(s). This isn't a new concept and is done more often than you may realize.
- Even this book is made partly due to that concept.

And if there's any one mistake you should avoid, it's doing any work without understanding what will happen with it and when. 
- If this seems exaggerated, think about the times someone said it was "urgent" when it wasn't.

Now then, there are several things to cover in this chapter, but I'll start with three: design patterns, design systems, and system design. The latter two are explained more in-depth whereas the former can be summarized succinctly.

### **Layman's Guide to Design Patterns**

Design patterns are reusable solutions to commonly occurring problems with specific contexts. This may include things like math formulae, algorithms, lists of instructions, cooking recipes; the "fun" stuff.

To illustrate it with a deliciously, non-technical example: You want to make a cake.

Your problem is you need to make a cake. 

You have a recipe that *could* solve this problem; a method to make a cake and many more cakes like it. You recognize that recipe can make this cake, or solve the problem, then recall and reason through the steps to get from problem to solution.

The recipe, or design pattern alone, will get you most of the way through. 

*Most of the way.*

What stops you now is applying the design pattern. There may be additional variables to consider, such as elevation affecting baking time or substituting ingredients. These variables are a non-issue at best or a show-stopper (the bad kind) at worst. If you understand the recipe (the pattern) well enough and its underlying mechanics, then you can adapt your recipe to still bake your cake.

When all is said and done, someone eating your cake evaluates based on the end result; taste, texture, appearance, etc. It could have the best process of all time, but that process doesn't mean anything if the cake tastes bad. This is why you want simplicity whenever possible because it saves you time and headaches. You're very unlikely to have a sufficient amount of consumers worry about your internal production process (how it's made) for cakes compared to the cake's taste and experience they received.

That one recipe can make that one cake, but now let's say you want to make different kinds of cakes. You could reuse ingredients, but need a different recipe to make a different cake or another dessert altogether. Despite this, you still pull from recipes you know (the design patterns) to help solve problems. There are times where you need to break away from the design pattern. If you're experienced and know what you're doing, you'll panic less compared to someone who's never followed a recipe in their life before.

Another thing affecting design patterns is constraints. That recipe from earlier may make a cake, but perhaps it cannot make a wedding cake. Many steps in the recipe may transition over, but perhaps you need additional tools, such as support beams to hold up the towering cake, you previously didn't need.

If you're familiar with software, you may recognize the terms DSA, data structures, system design, and algorithms. Concepts from there are pretty close to what I'm getting at here!
- *Another way my bias shows to get you to learn math, like I said in earlier chapters!*

### **The Weird Complexity (and Simplicity) of Design Systems**

*Alternatively: Build or Buy*

Per Chad Bergman on Figma’s blog (2024) ([Further Reading](https://www.figma.com/blog/design-systems-101-what-is-a-design-system/#what-exactly-is-a-design-system)):

> A design system is a set of building blocks and standards that help keep the look and feel of products and experiences consistent.

The key part here is "*the look and feel*." For instructors and teachers, this is akin to how students interact with your content, not necessarily the underlying systems. Many new technologies are also intentionally designed to seem familiar to past products for ease of use and adoption.

For those with less artistic backgrounds or lacking design skills, don't worry. You don't need to become a design expert to handle education systems, but still look into what a design system is and what it tries to accomplish.

Done correctly, **a design system accomplishes several goals**:
- A single source of truth
- Rules, standards, and styles definitions
- Libraries of reusable components
- Consistency across all products
- Reduced redundancy
- Increased accessibility

**Design systems are typically utilized in one of three ways: Adopting, Adapting, and Creating.**

**Adopting** takes a design system and adds it into your current system(s) without changes.
- Example: You copy and follow a cake recipe as is, step-by-step, exactly as written.

**Adapting** takes a design system and changes parts and pieces to fit it into existing system(s).
- Example: You follow the cake recipe, but have to substitute in gluten-free flour, vanilla for chocolate, or use a pan instead of a Dutch oven for part of the recipe..

**Creating** borrows from no design system and makes a new system from scratch.
- Example: You don't like the current cake recipe(s), so you made your own cake recipe.

Each option has benefits and drawbacks. Adoption is typically the cheapest, but least flexible and hardest to change. Creation is typically the most expensive, but most customizable. Adaption sits in between Adoption and Creation in cost and customization to suit your needs.

If you're unsure whether to adopt, adapt, or create, consider whether or not creating (or adapting) provides a larger competitive advantage over simply adopting. If creating your own design system provides no meaningful value, you should adopt an existing design system instead. This logic applies universally across many tools, software, and so on outside of design systems.

### **How Design Systems Relate to Teaching**

Design systems help establish how students interact with your content. Let me draw some parallels they share:
- Reading materials
- Libraries of resources
- Permitting edits and updates
- Templates and reuseable materials
- Organizational Hierarchies
- Collaboration to create one
- Shared vocabulary
- Longetivity and reusability

**If you're starting fresh, here are some additional resources. This applies to both curricula and design systems:**
- Do whatever makes the most sense for your use case(s) and audience.
  - If it doesn't make sense, then no one's going to want to stick with it.
- Look up actual design systems. Some examples are linked below:
  - [https://designsystem.digital.gov/](https://designsystem.digital.gov/)
  - [https://atlassian.design/](https://atlassian.design/)
  - [https://m3.material.io/](https://m3.material.io/)
  - [https://developer.apple.com/design/](https://developer.apple.com/design/)
  - [https://developer.apple.com/design/human-interface-guidelines/](https://developer.apple.com/design/human-interface-guidelines/)
  - [https://www.designsystems.com/](https://www.designsystems.com/)
- If you want to make good designs, you have to start designing.
- Learn not to fall in love with your work, because change is likely and sometimes forced.

### **Environmental Constraints**

There's two other constraints to design systems.

The first one is you may have to design something that accommodates *another* design. You may design a machine that looks amazing and does a great many things... but there's a catch. You have to use a specific set of screws, fasteners, and more, which are strictly defined and standardized to the point custom versions of these parts are extremely expensive. The environment may also restrict *how* you can design something, which is another cost.

A more practical example in 2025 may be smartphone applications. In the links above, there were various examples of design systems. If you were to make your own application on their software/hardware, you also have to obey the rules of their design systems. You may have to design menus a certain way, have animations function at specific timings, and have interactions be consistent with how the phone is normally utilized. That's only a few examples out of countless many, as compliance ensures your product functions as intended in the environment it is presented and utilized in.

Another environmental constraint is when you need "field modifications." This may be issues with how a product looks on paper vs real life, it could be issues between professions like architects and engineers or designers and developers, and engineers and machinists, or just "the plan didn't cover this; what do we do?"

In cases like these, you may have to make an educated guess based on what is feasible and what is allowed. One example may be you received 2x6 planks when you need 2x4 planks, but you know you have a table saw around to cut down a 2x6 into a 2x4. Another example may be you need a tool or part to complete something, so you decide to peruse the environment and subsist on a potentially questionable, but surprisingly effective, "fix" to solve the problem at hand.

The general lesson is this: you can do a lot of things on paper, but not as many things in practice. When in doubt, try to create *practical* prototypes to ensure the theory is as close to practice/real-life as possible.

### **Design System vs System Design**

Design patterns translate well into *both* system design and design systems, but design systems and system design are like comparing apples and oranges. Due to their complexity, the same person may not be working on *both* design systems and system design and have duties split across multiple people.

As a reminder, design patterns are reusable solutions to problems. Design systems deal with look and feel; sometimes called consistency and usability. This means factors like typography, colors, spacing, and interactions.

System design, however, concerns itself with the architecture/infrastructure of the *entire* product/service. This means dealing with things like data flows, communication between services, failure/fault tolerance, scalability, and reliability. Rather than visual elements, it deals with non-visual elements like databases, APIs, queues, streams, computational resources, and operational concerns. Think of it as the blueprint including all the parts you don't readily see to create your service/product.

A piece of software, or an application, serves as a succinct example of system design. 

Users interact with buttons, forms, videos, and layouts; the application of a design system. Behind the interface is the system design where an API (Application Programming Interface) connects frontend visuals to backend services like databases to do various, "invisible" tasks. These tasks include, but are not limited to, storing browsing history, caching information, and handling errors to ensure a smooth experience.

System design shares aspects of management, leadership, and how teachers/instructors may construct lesson plans. Say for example you're in charge of a project. You have a desired outcome, but the path to a clear solution isn't there. That means you're working with uncertainty and need to figure out various things, like a manager might, such as:
- What resources are needed
- What requirements to meet
- What you're allowed/not allowed to do
- How to account for "hiccups" or disruptions
- How to get from start to finish
- How things fit together and interact
- How you communicate necessary information

To put it another way: it's like giving you a coloring book, but you also have to draw all the lines you color inside of as well. That is the complexity, and beauty, of system design. Two people can make two designs with multiple ways to reach the correct answer (with the caveat they can validly justify their answers).

Systems design and design systems don't work in isolation either. They're *both* tackling *design* problems, but different parts of these problems. Both are necessary for a product to function well and look well for its intended audience. Lacking one or the other risks the decline of the intended service/product you wish to create, refine, and present. 
- E.g. Something could look beautiful, but function poorly, and vice versa.
- [The Aesthetic-Usability Effect](https://www.nngroup.com/articles/aesthetic-usability-effect/) is one way to make products "work" better by looking better (Moran, 2024).

If you need to make something look good and feel good to use, you employ design system solutions. If you need to adjust how everything ties in together and functions behind the scenes, you employ system design solutions.

In both cases, you don't decide the tools before how you'll design the architecture. If you curious why, think about building a house without a blueprint. It's generally a bad idea to go in without a proper plan. Even when you decide on tools, you want to reevaluate those tools regularly on a yearly, or even bi-yearly, basis.

Many details behind system design assume technical knowledge existing outside the scope of this book and are often catered towards backgrounds like engineers. Two extensive resources, albeit more advanced readings, covering system design I've seen are:
- *Fundamentals of Data Engineering* by Reis & Housley (2022)
- *Designing Data-Intensive Applications* by Kleppmann (2018)

Despite what I've talked about with the design system, system design, and design pattern concepts, theory is only part of it. While you can learn *quite a lot* just from reading the right information, the other essential part requires doing work like projects and whiteboard exercises to ensure it sticks.

### **Things to Keep in Mind**

You may love to design as a hobby. If you're designing professionally, however, you cannot forget you're designing to solve business problems. You may have to make things you might not be fully satisfied with, but are considered "good enough" for the problems of today.

One of the first things to cover is you need to not limit yourself by tools whenever possible. You need an alternative, or at least an escape plan, in case some technology doesn't work out as every tool has some level of "lock-in," or more commonly known as technology lock-in. A company making a technology or tool you use has a business case to earn money from it, so will find ways to make you dependent on it. Despite this dependence risk, it is almost always a foolish endeavor to not rely upon tools and existing infrastructure and do everything yourself.

Sometimes, it's ok if it just works. Simple is pretty complicated already, even without introducing scale and maintenance, and you may not want to constantly think about edge cases and problems.

Many people develop their design skills, and develop design systems, as they gain experience or the organization(s) they work in mature. It varies across specific types of design, but the following steps are typically involved in the design process:
1. Defining Problem(s)
2. Capturing/Clarifying Requirements (Research)
3. Diagraming & Planning
4. Designing Solution(s)
5. Testing Solutions(s)
6. Implementing Solution(s)
7. Iterating Solution(s) (Continuous Improvement)

Much like the Scientific Method, you're not required to go through all steps above in order every time. You can, and sometimes have to, jump around if there's issues or something isn't working out. Approaching design problems in practice may mean starting with small, simple steps and evolving solutions across multiple steps.

Understanding design systems translates directly into skills across multiple fields and helps with templating, creating reusable components and materials, and making it easy to change things. 

You're usually better off quickly pushing designs, testing (one at a time to save sanity), and iterating than remaining stuck on one perfect design. This means, when in doubt, stop overthinking and design something that just works. Don't touch it again unless absolutely necessary as your attempt to make it better actually makes it worse. Sometimes a new piece of technology isn't the correct answer nor is overengineering for a solution tomorrow you need today. 

For technical designs, like charts and graphs, you could save time and solve most of your business questions by asking if someone needs to import data to Excel (or another similar spreadsheet software). Most spreadsheet software is flexible, has a lower barrier to entry due to its "simplicity," and comes with powerful capabilities for analysis, solving business problems, and developing proof of concepts. It may save you time and find early on if something is compatible across system(s).
- Though Excel is the example used here, that advice applies when making access to information compatible with tools non-technical peers utilize.

Spreadsheets are versatile and reliable, but are *not* good at everything. Their biggest weakness is a specific tool can do a specific task better compared to spreadsheets. Using them for databases and emailing is also ill-advised because it does not scale well.

No single breakthrough makes the work easier, as difficulty is often found in the *problem* instead of the *tools.*

Lastly, despite how well something is designed, human error and accidents will occur and you'll always have to make tradeoffs.

### **A Note on Non-Technical Crowds**

I'll paint a scenario here: Imagine you're in a conversation with someone and you're trying to explain how a product works. You know all the technical details, inside and out, and could go on for days about this product. You're not necessarily trying to *sell* something; just inform.

The other person has no expertise or technical knowledge in this product like you do. You *could* try and cover some gaps here and there, but they'll lack an intuition or may diverge in goals compared to you due to this lack of background knowledge. If you don't frame it in a way they'll understand, or even care about or appreciate, they won't ever be as excited about the product as you.

This is common in workplaces and why there's advice for technical roles to care about *business* goals and objectives rather than technical objectives. Many people don't care much about the underlying methods or processes. They have a problem, they need a solution, and you need to convey how your product is a solution in a way they understand.

Users (mostly) just want it to work. That's it.

To convey it in a way they understand, you have to understand the person using the product. A designer may call this empathy or putting yourself in another's shoes. That's not to say learn *everything* about the person; that's impractical and a waste of time. Only enough to be able to reframe it from the other person's perspective and think about what impact the product has for the person, business, organization, etc.

There's a lot of things involved you may need to look at, such as:
1. How will this generate a profit?
2. What does this cost and who/what is funding it?
3. What drives the investment (strategy, tactics, etc.)?

It's entirely possible for something to be good for someone or something, but they'll still reject it based on moral grounds. That's why I added the drive behind the investment, because it's someone you may skip over if you're not careful. You need to justify *why* something is important, not just show it is important.

### **The Dashboard Problem**

Dashboards are an end product; the thing consumers/users see and interface with. They provide a high level overview of relevant information and (typically) consist of a collection of visuals like graphs, charts, maps, and so on. As previously discussed in the Metrics chapter, it's a collection of diagnostics to help inform decisions and answers to problems, not directly provide an answer.

There's also multiple types of dashboards, such as:
- Operation
- Analytical
- Strategic
- Tactical

Each dashboard type has various goals. Operational dashboards provide real-time (i.e. streaming) data and analytical dashboards provide information on large batches of data. Strategic dashboards focus on KPIs across the business while tactical dashboards focus on one (or more) aspects of a business.

The big question is how do you know a dashboard is useful? The answer is simple: it helps answer your questions or change what someone does next. If it doesn't do that, it could be handcrafted by the legends of Michaelangelo, Donatello, Leonardo, and Rapheal all working together to create a beautiful masterpiece... but still be useless to you. This includes vanity metrics and parts that *look* good but don't actually help you.

Evaluating dashboards by how often they're used is often a misnomer. You'd be more accurate measuring how quickly it answers a question *as that question arises* and/or how well it lets others perform their jobs faster. For a formal name, this might be called Time-to-Insight. Let's use two examples, assuming they have equal levels of aesthetics:
- Dashboard A is viewed multiple times per day, but it takes a long time to answer questions with that dashboard.
- Dashboard B is viewed twice a year, but it almost immediately helps you answer the question you're dealing with.

If you were to ask me which of the two is better, I would say Dashboard B. If you're still unsure why, I'll use two, less technical examples: driving cars and flying planes.

When operating these vehicles, your attention should be focused on driving/flying. For cars, that's paying attention to the road, other cars, your own speed, weather, and so on. For flying planes, that's maintaining speed and altitude (amongst *many* other things) and ensuring you don't hit the ATC tower or another plane. It is legitimately dangerous to you and others to take your attention away from these tasks. 

There are HUDs (heads-up displays) with information, gauges, and other ways to monitor the status of the vehicle. They are intentionally designed to fit legal compliance as well, otherwise they're not cleared for use (for aircraft, [one example of guidelines is AC 25-11B](https://www.faa.gov/documentlibrary/media/advisory_circular/ac_25-11b.pdf) from the FAA to meet Title 14 (2014)). The questions they help answer are numerous, such as failure conditions, speed, direction, altitude, display systems, and many more. Without these systems in place, you'd be operating a vehicle that both leaves you unaware to what's happening "under the hood" and unable to make adjustments in time when emergencies arise.

You may also deal with underlying, technical issues such as if there's any lag time between when data is updated vs when data is displayed (i.e. is it behind by X timeframe). There's also developing separate tests and measures to validate these systems to ensure precision and accuracy before they're deployed. The technicalities of these aspects are beyond the scope of this book, but you should be aware not-so-apparent issues exist too.

### **The Penthouse "Suite"**

Chances are you have purchased a product made by a particular company.

There's also a chance that same company has products compatible with what you currently have, but not compatible with similar products made by a different company.

If you're wondering why they aren't cross-compatible, it's because they want you, the consumer, to buy *their* products and not their competitor's products. Why should I give you reason to buy 1 of my products, but 1 of another company's products, when I can get you to buy *2* of my products so I earn more money?
- *The answer is it also costs money, but I'll pretend I didn't answer it here.*

This can occur in software, hardware, a custom bed for man's best friend, the cardboard box a cat loves, and even a stack of paper.

A company can do a lot of things to get you to buy their products, such as: 
1. They can make one product exceptionally well you'll use for a long time, if not a lifetime. 
2. They can make one well-made product to get you into the door, then offer other items and/or add new things over time to keep your interest. 
3. They could offer a product which functions well, but also make and inform you of a separate service/product you *might* be interested in and consider putting money towards. 
4. They can also make a large variety of products to try and suit many needs as possible so they become your one-stop-shop for all goods.

A "suite" in this context typically refers to software and items 2 and 3 in the list above. It's a set of software where each "software" in the set forms a "suite." You could purchase parts of a suite or the full suite, but you could be forced to buy the whole suite.
- One example is Adobe Creative Cloud; a single service provides multiple applications like Photoshop, Illustrator, and Premiere all in one toolkit (the "suite") for a subscription fee.

At the end of the day, a suite is an anchor to get you to use and purchase the companies products. The setup of a suite also makes it so as long as you really like at least one or more products in said suite, you might pay for a bundled price despite not utilizing part of a suite.

It's like a penthouse suite in real life. It comes with a lot of features you may or may not use during your stay. That's ok though; you pay the price for the *opportunity* to have all these features bundled up nicely for you in case you *do* want to use them.

### **Why Do We Need Integration Tests?**

*Alternatively: Why Tests Matter*

Tests are pretty important. Testing mitigates hidden costs and problems resulting in bigger costs down the line. You rarely want to pay for extra costs, which means you shouldn't neglect testing.
- E.g. not enforcing quality tests is what passes students along when they should be retained.

In education, they check for understanding of material presented by a teacher/instructor. In programming, they check to make sure everything is working and (hopefully) not wake you up at 02:00 to an angry phone call to fix it. Regardless of industry, eliminating or not allocating time to testing things before putting them into practice is, put lightly, a terrible idea.

There are multiple types of tests. Integration tests, as called in the section title, are to ensure something *else* unwarranted/unexpected isn't causing a problem that affects software (i.e. affects the program's integrity). In education, this may be factors found in the students themselves, or the processes surrounding the test, you may've not accounted for but are external factors affecting how they're ran.

Other types of tests (validation methods), to borrowing from programming linguistics, include but are not limited to:
- Unit (checking individual parts for expected performance)
- Regression (verifying new changes didn't cause issues or decay)
- Integration (checking for external dependencies causing issues)
- End-to-End (validating entire systems/workflows)
- Smoke ("see if it catches on fire")

Despite the names and applications of these tests in programming, they're not too far removed from what teachers may do for their classes in education. Quizzes and pop quizzes serve as quick checks or verifying students understand functions or concepts. Exams may validate learning across whole units, the entire course, or multiple units at once. Homework may check for learning issues before the exam and whether or not there's underlying issues with teaching methodology in the course. You may also run multiple "tests" on a single unit/concept, such as homework for practicing and catching issues early, then quizzes/tests later to check understanding.

The concepts of these tests applies to the design chapter because they apply to and beyond curricula in education. Perhaps you're hosting educational material on a third-party platform. Perhaps there's material you're designing for that goes beyond the classroom. Without testing and ensuring functionality, the student learning experience is bound to suffer as a result.

As for people who question why their superiors, peers, etc. may neglect testing in many forms, I can give you at least a few reasons:
- Path of least resistance.
- It obscures poorly written processes, code, content, etc.
- Tests themselves require maintenance to stay relevant and accurate.
- Not directly translating to profit and/or exceeds deadlines.
- Requires buy-in from everyone to not let issues slip through the gaps.

### **"Built to Break"**

*Alternatively: Planned Obsolescence*

Getting customers is easy with a good product. They buy something they want, which you provide, and you both benefit from it.

Getting *repeat* customers and maintaining sales is much harder. This is where planned obsolescence, or intentionally designing failures, is prominent. You design a product with an artifically limited life and either:
1. Provide replacement parts customers buy to extend the life
2. Create new products to replace old products, which means another purchase

There's also methods like "power creep" in many types of games. That is *not* planned obsolescence, but an evolutionary change and a consequence of shifting directions. An initial product can last for a long time, but adding newer products to bring back new and old customers may overshadow existing products. It's part of being a business and the need to continue selling content to consumers, adapt to an ever-changing environment, and avoid going stale.

I'm not going into detail on this topic, but I do want you aware the concept exists.

### **What about EdTech?**

Many rules and concepts you find in designing systems, you'll find in EdTech and other digital and physical mediums. Some tools are well-designed and others are not. Quality typically improves over time, but gaps and deficiencies persist between iterations of new products.

Sometimes you're forced to use particular software to accomplish your goal. Software is a tool to achieve a task or solve a problem you have and you'll be better off knowing how to use a tool than not knowing how to use a tool. With tools, however, you won't get better with them unless you use them.

### **What if I cannot find problems with designs?**

*Alternatively: Heuristics and Heuristic Analysis*

You'll rarely, if ever, find something with *zero* issues in any way, shape, or form whatsoever. If something without *any* problems exists, then it'll probably stand the test of time for many years to come.

One common reference is [Jakob Nielsen's *10 Usability Heuristics for User Interface Design*](https://www.nngroup.com/articles/ten-usability-heuristics/) (2025). The intent of the principles is to make products easier to use and reduce cognitive load on users as they're utilizing products.

As for specific problems in general, there's countless amounts. To give a small set of examples:
- Functions without defined intents
- Readability issues
- Inconsistency
- Redundancies
- Help documentation is lacking
- Errors are permitted instead of prevented

The issues you'll find vary widely on the context and product they're located inside of. Some issues may have acceptable ranges (tolerances) which are wide or narrow depending on requirements.

### **How to Measure "Impact" (Metrics of Success) of Designs?**

This is a complicated question. 

The biggest thing is you don't want to lie about any impact and throw out random numbers. The lie quickly becomes apparent under scrutiny and you risk losing trust, influence, and even your position among peers.

A hidden reality is a lot of design work may not be "shipped" or available for use by customers or businesses. Because they are not readily available, collecting data for business metrics isn't easy, if even feasible, for someone below a director-level position or outside a data adjacent position (Scientist, Analyst, Engineer, etc.). This typically means many designers, or someone generating designs, may not have significant influence and impact at a company level.

The question shouldn't be how to provide business metrics to demonstrate success. It should be how to display the quality of decision making and problem solving and what you *should* use to prove your designs are good. While you could be in a position to acquire data to enforce decisions, if you're in an organization they may strictly limit who can access what data and manipulate it.

I'll go over what could still be answered while assuming you're in a position you cannot acquire hard data.

1. How would you measure success of the design (i.e. what you *would* use, not *did* use)?
2. What problems occurred during research into the design?
3. What are potential solutions we can implement?
4. What were the results from any tests you set up and ran on your designs?
    - Additionally, how did those tests influence decisions going forward? 
5. What processes worked and what processes didn't work?
6. What were the outcomes along the way during the design process?
7. What did you learn about?

Even for work that's never shipped, a project with sufficiently high quality design work is still a signal to show there's potential impact if it were shipped.

### **What if I Need to Find/Design Something?**

There's some questions you should ask beforehand.

1. Who is it for?
2. What problem does it solve?
3. Can it be used in your current setup, system, etc?
4. What benefits does it provide over another option?

If you don't know who is going to utilize what you provide, you risk them not using it, refunding it, or disliking the provider; you. If you cannot figure out what problem it's trying to solve, it's like using a band-aid for a non-existent wound and may not be that useful. If it cannot be used alongside your other products, or get buy-in from people to adopt it, it doesn't matter how good the solution is if it cannot be used. Lastly, if it doesn't provide benefits other another option, then why should someone use what you make?

### **I don't have much artistic design experience though!**

Two things before you panic.
1. You can "design" in programs such as PowerPoint, Excel, and Microsoft Word or their equivalents in Google Documents, Google Sheets, and Google Slides. 
    - If you need advanced design programs, you'll need dedicated design tools like Figma, ProtoPie, Photoshop, Illustrator, and Sketch.
2. You're likely focused more on content, the delivery of content, and the management of students rather than design anyway. If you lack time or resources, learn just enough to get by and supplement your teaching.

Some general rules of thumb you can quickly apply come from personal experience as well as reading through *Refactoring UI* by Wathan and Schoger (2025).

- Never rely on color alone
- Start simple and ensure functionality before adding complexity
- White space is easier to reduce than add
- Text needs sufficient contrast (e.g. WCAG "AA" rating or higher) against its background
- For colorblind people, it's easier to tell by lightness (light/dark) rather than color
- Most greys have tints of other colors mixed in

## **Bibliography**

1. Apple Inc. (n.d.). *Apple design*. [https://developer.apple.com/design/](https://developer.apple.com/design/)

2. Apple Inc. (n.d.). *Human interface guidelines*. [https://developer.apple.com/design/human-interface-guidelines/](https://developer.apple.com/design/human-interface-guidelines/)

3. Atlassian. (n.d.). *Atlassian design system*. [https://atlassian.design/](https://atlassian.design/)

4. Bergman, C. (2024, February 12). *Design systems 101: What is a design system?* [https://www.figma.com/blog/design-systems-101-what-is-a-design-system/](https://www.figma.com/blog/design-systems-101-what-is-a-design-system/)

5. Cook, R. (2000). *How Complex Systems Fail.* how.complexsystems.fail. [https://how.complexsystems.fail/](https://how.complexsystems.fail/)

5. Design Systems. (n.d.). *DesignSystems.com*. [https://www.designsystems.com/](https://www.designsystems.com/)

5. Federal Aviation Administration. (2014, October 7). *AC 25-11B - Electronic Flight Displays.* [https://www.faa.gov/documentLibrary/media/Advisory_Circular/AC_25-11B.pdf](https://www.faa.gov/documentLibrary/media/Advisory_Circular/AC_25-11B.pdf)

6. Fessenden, T. (2021, April 11). *Design systems 101*. Nielsen Norman Group. [https://www.nngroup.com/articles/design-systems-101/](https://www.nngroup.com/articles/design-systems-101/)

7. Google. (n.d.). *Material 3 design system*. [https://m3.material.io/](https://m3.material.io/)

7. Kleppmann, M. (2018). *Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems.* O’reilly Media.

7. Moran, K. (2024, February 3). *The Aesthetic-Usability Effect.* Nielsen Norman Group. [https://www.nngroup.com/articles/aesthetic-usability-effect/](https://www.nngroup.com/articles/aesthetic-usability-effect/)

7. Reis, J., & Housley, M. (2022). *Fundamentals of Data Engineering.* O’Reilly Media, Inc.

8. TV Tropes. (n.d.). *Kansas City shuffle*. [https://tvtropes.org/pmwiki/pmwiki.php/Main/KansasCityShuffle](https://tvtropes.org/pmwiki/pmwiki.php/Main/KansasCityShuffle)

9. U.S. General Services Administration. (n.d.). *U.S. Web Design System*. [https://designsystem.digital.gov/](https://designsystem.digital.gov/)

10. Wathan, A., & Schoger, S. (2025). *Refactoring UI*. Tailwind Labs Inc. [https://www.refactoringui.com/](https://www.refactoringui.com/)


## **[Next Chapter](Z022_Action_Plan_Week_1.html)**