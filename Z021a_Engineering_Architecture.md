---
title: 29. Engineering & Architecture
layout: default
nav_order: 31
---
# Engineering & Architecture

### [Previous Chapter](Z021_Design_Systems_EdTech.html)

## **Short Answer**

> “Any idiot can build a bridge that stands, but it takes an engineer to build a bridge that barely stands.”

- Anonymous
  - *Finding the source for this quotation is a Herculean task, so if someone does know the original source, let me know.*

---

There's a lot of things to consider when designing educational systems.

Two of these things are engineering and architecture. You may deal with physical buildings with physical humans, but also see concepts from these fields useful to improving processes inside these systems.

As a more "personal" note, or you happen to be a student reading this right now. If you want to be an engineer, architect, or technical professional (including an educator), expect to go above and beyond learning only what is taught in a classroom, video lecture, etc. and *genuinely* invest into your own education. That means you cannot shirk off any of the creativity, critical thinking, problem solving, and ingenuity required to succeed.

## **Long Answer**

Remember: It's not stupid if it works. Even if it is stupid.

This chapter is going to have many technical terms. That's intentional. This is the chance for me to talk about a lot of engineering and architecture concepts, because I have education and experience with these kinds of things. For readers, think of this chapter as some topics from these fields you can use to better design education systems.
- No I'm not saying anything here as professional engineering or architecture advice. That requires someone with a "stamp" and a legally protected title, like Professional Engineer or Professional Architect.
- Expect me to highlight certain Industrial Engineering concepts in particular.

The main difficulty in engineering and architecture isn't the content, but more the dedication and perseverance to get through it all and devote the time and effort to figure out how *and why* things work. Engineering and architecture are also not strictly limited to engineering and architecture.

I'll identify four core branches of engineering: Chemical, Civil, Electrical, and Mechanical. Each branch has sub-disciplines tying back into one (or more) of these four. There's many types of engineers and plenty of crossover, with the primary difference being the core science involved in their discipline. 

Think of engineering as methods for problem solving. Industrial engineers use these methods to optimize systems; typically with the goal of minimizing costs, maximizing performance, or both. Chemical engineers may utilize chemicals and energy primarily through chemistry while civil engineers may utilize earth sciences to calibrate infrastructure and solve problems for humans and their environment.

Architecture is similar to engineering, and may be considered a subset of engineering, except you take that same problem solving and apply it more towards structures and their spatial design as well as how land should be utilized (e.g. "green space" vs "building space"). One example of work here may be you're minimizing the cost of materials and labor to create a campus within budget and deadlines while meeting a desired quality through many factors like aesthetics, accessibility, and structural integrity.

The good news is you can do a lot with these disciplines and apply their concepts to many other fields. For example, Donald "Don" Norman, who has an electrical engineering degree, created many design concepts for user experience and human-centered design still in use today, as of 2026, across various texts and books like *The Design of Everyday Things* (1988/2013). 

The bad news is you need math and science skills, and plenty of creativity and critical thinking skills, to effectively do those disciplines.

As a reminder, you could easily have several books on each topic here, so if you want to learn more, you are free, and encouraged, to look up other sources. I'll try my best to summarize them, so let's get into it in no particular order.

### **Rubberducking**

I love this method personally. It's a concept attributed to Hunt and Thomas (1999).

Talking about your problems tends to help and sometimes uncovers solutions as you're talking through them. It doesn't have to be a human you talk to either; it can be a rubber duck instead!

Or even a Blåhaj from IKEA.

It's like thinking aloud except you're reframing the subject, explaining it to someone who may not know what you're talking about, and describing what it should do vs what it actually does right now. The fact it's also an inanimate object means you won't hopefully feel social pressure too in case you say something wrong or have hesitation problems. It's not a replacement for learning critical thinking skills, of course, but it does help with blockers.

Try it at least once. That's all I ask.

### **Tolerances**

*Alternatively: Standardization is GOOD*

The concept of tolerances applies in about every industry. Even education. Sometimes your necessary tolerance can be anywhere from "hit with a hammer until it fits" to "if we're even a Planck off, we're in trouble."

Tolerances, from an engineering perspective, are allowable variations for a given product's dimensions/properties. For example, you need a part that is 1 inch long, but you could accidentally make it a touch long (+1/16 inch) or a touch short (-1/16 inch) and it'd still work fine. Messing up the part too much, like making a 1 inch piece 2 inches instead, means that potentially successful product becomes wasted time, resources, and labor.

Tolerances can be set by humans, but are also defined by the material, tools, and environment itself. For example, you may want a cupholder to be exactly 4.257 inch diameter and tolerate very little mistakes (±0.001 inch tolerance), but your tools can only make a product so well (e.g. ±0.01 inch tolerance) and *any* mistake probably means failure.

This may mean your tolerances are outside the scope of verification or measurement. For example, if you're measuring to exactly an inch, but your measurement tool can *only* measure down to 1/32 inch increments, you should NOT establish a tolerance that is smaller than 1/32 inch! If you do, you may need to spend a LOT of time, money, and other resources to get a specialized part or service to verify everything is correct for you. That is *not* fun or easy to do.

From a management perspective, think of tolerances as the allowable margin of error you'll tolerate for your employees and their performance, work, behavior, etc. against established standards. You don't want to be *too* tolerant of issues, but also not have so little tolerance you force nothing less than absolute perfection from imperfect human beings and methods.
- For example, what you tolerate in an education system may be *far* more lenient than in the aerospace or military industry/system. The requirements demanded by the environment and risk involved are vastly different, so what is "tolerated" is different.

### **Interoperability**

Interoperability defines a product's, or system's, ability to communicate with other products and systems (Slater, 2012). It's why standardization is *usually* a good thing because it can enhance interoperability.

For non-technical readers, think of it as two systems, devices, etc. establishing and agreeing on a single language to properly communicate the necessary information with each other. Said communication involves its own form of speaking, listening, and interpreting much like a conversation between people in a human language.

How it does this is typically through sharing data formats and communication protocols, such as a television and cell phone accessing the same software despite being two different devices or a programming language like SQL or Python to execute the same code across different platforms and IDEs. These "languages" are defined through standards, usually set by individuals or organizations, to mitigate inconsistencies and issues. Benefits include adaptability and additional business for all products involved, because it permits more people and devices/technology to work *with* something rather than not.

Translating it into systems instead of products, interoperability could also define how two different organizations of humans cooperate and function together. These organizations, much like software programs and products, also need shared formats and standards to communicate with for reliable information exchanges. For example, it could be a military application like NATO and the US, a medical application like hospitals and insurance, or a corporate application like transmitting files from one organization to another.

If I bring this back to education systems, we can look at the different tools and software used to communicate information. An educator's gradebook, for example, should be able to transmit or package its content into formats other programs can read, such as a database to store information in a secure location or a document a spreadsheet can intake and analyze. If that same gradebook tried to export its data to a program that *couldn't* interpret it, you'd experience issues with your current setup (or new products you're bringing in) and thus need to re-evaluate the interoperability of many products in your education system.

It's also why the advice of reviewing your current technology "stack" every 1-2 years isn't a bad idea; you're able to confirm technology old and new still plays nice with each other. If they don't, then you can proactively solve whatever issues that brings instead of reactively finding out.

### **Physical Building Codes & Regulations**

You could easily fill an entire bookcase on this topic alone. I'll try my best to summarize it.

In terms of background knowledge requirements for physical buildings, you can get by with Algebra and Geometry/Trigonometry for simpler buildings and most residential designs (e.g. Class C and Class B). Calculus (and sciences utilizing Calculus+) and beyond may better solve the problems related to more complex building designs (e.g. Class A). Unless you're the engineer of record, you're likely instead reading and verifying engineering documents from  professional engineers and architects, cost estimates, and schedules to oversee subcontractors and get the building(s) made.

In the United States, as of March 2026, there are two primary codes to follow: IBC (International Building Code) and IRC (International Residential Code). There's also a suite of other codes, such as electrical, plumbing, mechanical, and fire codes, and a separate code for remodeling projects (i.e. "existing buildings"). All of these codes created by the International Code Council are collectively called "I-Codes" (ICC, 2024). 
- For example, unless your educational facilities are hosted on residential property *and* zoned as residential in the municipality, expect to use IBC instead of IRC.

If you're in a position where you need to review physical building codes, there's a trick that helps: *knowing where to look.* I'll tell you right now memorizing these code books in their entirety is reserved for inspectors and code officials, which you are very likely *not* that. For the average person, it is an endeavor in wasted time and madness to memorize every single code detail. Instead of memorizing every detail, you should memorize *where* to find the details. There's nothing wrong with reading building codes from start to finish, but it's probably overwhelming if you're new to their structure, concepts, and terminology. 

Alternatively, you may fully memorize a few specific chapters or several details spread across many chapters, then know how to reference the book for other details depending on what you're working with.
- For example, Chapter 10 Means of Egress and Chapter 11 Accessibility always comes up in your designs, so you should memorize details in these chapters, but Chapter 2 Definitions is basically just a dictionary, so you can search up particular words if they come up and memorize only the most common words.

Your "looking up" process may be something like the following:
- Figure out the specific code required for the area. This is typically by state, but can vary across local jurisdictions as well. 
    - For example, the enforced IRC edition can differ between two adjacent cities.
- Have the links to said code book(s) handy (e.g. [ICC I-Code by Year](https://codes.iccsafe.org/codes/i-codes) website), even if it is read-only access.
    - Typically these are available online, as physical textbooks, or downloadable files.
- Look for the appropriate building codebook you need to reference to access its contents. 
- Look for the chapter with a title that aligns closely to what you need to look up.
- In said chapter, find the section you think your answer is likely to be at.
- Utilize a command, like Ctrl+F (or Cmd+F) to find specific phrases.
- See if the text provides an appropriate answer. If not, repeat the process.

You may also encounter situations where a specific code will reference another code in a different code book, mention where exceptions or outlines are determined by other sections, or talk about guidelines in one section that is in accordance with another section. Think of it as a giant, interconnected web of regulations where one small part of a codebook can reference multiple things at once. Expect to be jumping around quite often between seemingly unrelated areas.

Additionally, some rules and guidelines are accompanied by maps to highlight where a code variation applies. This usually relates to material science, biology, and environmental effects, such as wind speeds, weathering of concrete, seismic design, stress design for snow loads, termite infestations, and so on.

**Remember: Do NOT memorize the entirety of these code books. Do learn how you can best search information within them.**

### **"Shorthand" Building Knowledge Examples**

The biggest shorthand rule for home design is simple: design it so someone would *want* to live in it. You wouldn't want an airport lounge situation (i.e. busy foot traffic) in a living room where you need to relax instead of wait.

The second rule is the furniture inside the home may be the problem rather than the home itself. If simply rearranging furniture solves the problem, then attempt that first.

I've usually designed houses under IRC building codes, including some homes I've lived in. I'll provide you simpler examples of factoids I memorized as I designed floor plans. For reference, IRC 2024 and Chapter 3 Building Planning provide many common details, but I'm naming off several that immediately come to mind and paraphrasing the exact wording (ICC, 2024). These may also change in the future as building codes change, but the relative concepts should persist despite any changes.
- Most interior walls are 2x4 studs at 12 OC or 16 OC
    - "OC" = On-center, measuring the distance from the center of one stud (structural wood plank) to the center of the next nearest stud in the same structural wall.
    - Many tape measurers have red squares/specialized markings on certain measurements to make measuring OC along a wall easier (e.g. a "red square" number marked every 16 inches)
- Most exterior walls are 2x6 (or larger) with studs at 12 OC or 16 OC.
- Habitable space ceiling heights shall be no less than 7 feet height, except for bathrooms, toilet rooms, and laundry rooms with 6 feet 8 inches height, non-habitable basement spaces at 6 feet 8 inches height, and 6 feet 4 inches height for beam, duct, etc. exceptions.
- Concrete slabs are at least ~4 inches thick and require joints spaced no more than 4 feet apart.
- Egress windows are at least 24 inch high by 20 inch wide openings, with a clear opening area of ~6 square feet (minimum of 5.7 square feet net clear opening) and cannot be higher than 44 inches off finished floor.
    - Additionally this formula: Length (inches) x Width (inches) / 144 (i.e. 12 inches squared) = square footage
- 1 pound per square foot = 0.0479 kPa (kilo-Pascals)
- 1 mile per hour = 0.447 m/s (meters per second)
- Standard hallways, and many stairways, in new construction are generally at least 36 to 42 inches wide.
- At least one door, designated as egress, is at least 32 inches wide and 78 inches high.
    - Other doors are generally at least 30 inches wide, but exact details vary widely by municipality.
- When able, design a bedroom on the same floor as the primary entrance in a house to appeal to disabled, older people, and people who do not like stairs much.
- You need a 1/4 inch (quarter-inch) of fall for each 1 foot length for water runoff.
    - This include items like some concrete slabs and sideways, graded landscape, underdeck drainage, and more.

There's plenty more to write about, but I'd rather not make too large a list here. Some items here may not make sense at first until you explore the designs yourself and see the results once they're fully built.

Much like mental math, you want to memorize information that quickly enables decision making and gets through frequently occurring work and problems you encounter. For harder items, or where you'll reference specific formulae, rules, etc. it is expected you'll look it up from time to time.

### **Graphics, Plans, and Schematics**

Shall I tell a story first? Sure, why not.

You have a plan. You get estimators to figure out how much that plan costs to bring it to life and lay out *how* it should be done. Everyone agrees upon the specified work and everything beyond that is a change order (i.e. clients pay more money). Everything seems perfectly fine and we're all good to go!

...At least until you go to the job site. There's staff/machinery lying around doing idle work, you've gone over budget and deadlines, and the crew is pissed at the number of change orders and shifting demands thrown at them, even *with* the clients accepting crazy high prices for all the change orders.

So yea. Learn how to read graphics, plans, and schematics and what can/cannot be reasonably done. Also know when to push back against clearly unreasonable requests. It may just save your wallet and sanity.

Graphics, plans, and schematics are often interchangeable terms. In this case, think of them as blueprints or how something is built. This could be something small, like the design of a screw and its thread placement along its length, or something large, like a skyscraper building. This include many different types, such as topography maps, electrical plans, site plans, floor plans, exploded views of schematics, and so on. There's many free sources available to learn about plans as you encounter them, so I won't list them here for brevity's sake. 

If *you're* designing the facilities where you'll implement education systems, you should have familiarity with how to read plans. While you could be adept enough to design your own plans, understanding how they're written and laid out leaves you the option of contracting out another service to assist you and provides you more time to accommodate changes and verify progress at each step. You might be forced to contract out other services as well because you lack licensure yourself to do it legally.
- For example, on many building plans/designs you may need an engineer/architect of record to "stamp" it for approval before it may be legally constructed.

Understanding plans is basically understanding symbols and how they're drawn. For engineering plans, the exact symbology used depends on the medium plans are drawn in, but they typically remain consistent across mediums. For building plans, the information required and the CAD (computer-aided design) standards are subject to state control (and local reviewing authorities, if applicable). 
- One such standard at the time of writing (March 2026), albeit paid access, is from the [United States National CAD Standard, or NCS](https://www.nationalcadstandard.org/ncs7/content.php) (2025).

Of particular note for my own endeavors were "topo" (topographic) maps and site plans. Knowing how to read topo maps lets you interpret terrain features, map scales, contour lines, locations of vegetation, triangulating locations on a map, and more. Site plans are useful as they provide a high-level overview of an entire site (i.e. a zoned property) and the location of features like building, foliage, water, road, and parking lot placements.

### **Facility Planning and Production Planning & Inventory Control (PPIC)**

*Notice: Primary source for this section is "Facilities Planning" by Tompkins et al. (2010).*

The type of math required to fully derive and prove models here may require at least multivariate Calculus understanding, though much work is done using results from derivations other people made before.

Though it sounds simple and these topics are catered primarily towards manufacturing, it still encompasses quite a bit. Imagine you're planning out a service you want to make and sell something and you have X amount of funds available to set it up. You'll need to consider many things, such as:
- Maximizing ROI (return on investment) and ROA (return on assets)
- How to cut down on unnecessary costs
- Determining demand
- Determining production capacity (and available supply)
- Ways to automate processes vs manually doing it
- How to maintain existing inventory and allocate space to store it.
- Where to acquire raw materials or base components to bring into a facility to then process it into the products you distribute and sell.

You may think "what does this have to do with education systems" and the answer is *a lot of things.* Education systems will encounter problems with resources, capacity, and flow like manufacturing systems will. You still have production, which is delivering quality learning, inventory for resources to make said learning happen, and planning to figure out schedules, where to allocate people, organizing how content is deliver, handling enrollment and student intake, and forecasting demand and costs out in the future. It could be embedded inside existing education systems too, such as the "production line" of a cafeteria to store and process those same items, provide the items they need, get people through queues, and do it all quickly enough to meet deadlines. It could even be perfecting how students may pass along materials from one desk to another desk while applying models for conveyors in a new way.

There's also many parts that directly translate to education systems present in architecture and engineering, such as handling environment constraints, utilizing layout planning models, and design algorithms like CRAFT, MCRAFT, and BLOCPLAN. Educators should strive to optimize how the space in their classroom is utilized, much like how a manufacturer wants to maximize production capabilities in a given space. Perhaps you're reorganizing something simple, like a closet, and could use a high-powered solution like a block stacking model to help you optimize it too.

Recalling the sections on graphics and building codes, you may need to consider other design aspects, such as traffic flow of people (or vehicles, animals, etc.) in physical spaces, the physical constraints of the space you're working in (e.g. a rectangle vs unorthodox shaped room), where to retrieve, transport, and store goods at, and so on.

On PPIC in particular, it ties back into facility planning because how you plan a facility, and its capabilities, determines what you can reasonably forecast and accommodate according to trends and incoming data. Think about it think way: facility planning is determining how you fit everything into place and PPIC ensures the resulting production process is efficient, cost-effective, and meets all demands and requirements.

These topics, and related topics, altogether provide processes to assist with planning, scheduling, and controlling processes and systems.

### **Programming**

Yes, programming is a thing for both engineers and architects and includes languages like SQL, Python, R, Java, COBOL, Rust, and so on. Generally speaking, when dealing with programming languages, you're usually better off prioritizing readability (and therefore maintainability) over performance *unless* you need to meet a minimum performance threshold.

Architects may utilize software and programming for architectural designs. They can manipulate code through programming languages to build plugins and create custom solutions as tools to enhance their work processes and outputs. In this case, it's in service of something else, like geometry or workflow automation, and the programming stays close to the design artifact/software.

Programming also provides the means to service other fields outside of engineering and architecture to accomplish many things. For example, Python with processing algorithms and data science, SQL with transforming and cleaning up data, VBA to automate tasks inside of existing software solutions, Matlab for analysis, and so on. The code itself is a deliverable, or part of a deliverable, to enhance current solutions and/or create new solutions.

While it has countless applications, programming is often used to conduct calculations, speed up processes, automate tasks, or do things that a human cannot do within their own limitations. Modern technology also enables more standalone solutions and scripting for wider audiences, like PowerBI or Excel bringing traditionally engineering work and data to non-engineer professionals.

At the end of the day, programming is simply a means to an end. A tool in a toolkit. Many professionals utilizing programming may not be engineers or architects, but simply people using it to solve a problem they're working on.

### **Economic Analysis**

Most information from this field is found scattered across existing textbooks, such as *Engineering Economic Analysis* by Newnan et al. (2012).

Professionals need to know how money works and get some understanding of the business they're in. It's what affects decisions in the short-term and the long-term, helps determine if a project is even worth putting money into, and determine which options are the best amongst multiple alternatives/options.

Normally this topic is in the realm of finance and business, but engineering and architecture also utilize it alongside many other professionals. While you could get by with many pre-defined formulae and plugging in values for each variable in equations, "engineering-level" economic analysis may expect you to know at least multivariate calculus and beyond to fully understand it and bring it to its full potential.

This topic is important for another reason: it gives you the tools to assign monetary values to just about everything you may do within any given business. From the Metrics chapter, recall that metrics are measures to reveal whether your current system performs as intended or requires changes. That also includes different metrics for economic analysis, such as payback time, return on investment, and net present value, in addition to new tools and formulae to define said metrics.

It also includes delving into topics many younger students wish they knew before they got older, such as explaining taxes, savings, investments, expected costs, depreciation, cash flows, equity, debt, and the time value of money. You may also use this topic to help determine the cost of a constraint or initiative, such as a new union policy or insurance going into place. On cash flows in particular, it's where people may realize, perhaps for the first time, that cash flow is typically negative in the beginning because you're recuperating from your initial investment towards any capital expeditures.

### **Simulation**

For readers familiar with video games, think about games where you need to build a base or a city and manage all of the moving parts in it, such as resource flow, logistics and transportation, and creating products (perhaps in a factory environment). While the video games of today, as of 2026, are not capable of fully automating all the complexities of real-life environments, they do capture a lot of the essence. More exhaustive software and tools, outside of our video game example, specifically designed for simulation capture more of their complexites and nuances for professional use, albeit usually at higher cost due to the requirements to create such technology.

For readers unfamiliar with video games, think about what it's like to go to school, the store, or even to another person's house. You leave from one location, take X amount of time to get there, spend Y time at that other location, and perhaps encounter an issue delaying you by Z amount of time. This is one example a simulation applies; going from point A to point B in order to accomplish some task.

Simple examples can be studied through simulations and we account for many things, such as entities, attribute, logic, decisions, workstations, service points, capacity, processing times, failure/repair cycles, travel paths, types of flow, and many, many, more. This is why I say something like a video game can capture the *essence* of it through models. It'll get the core idea down as it tries to emulates an environment, but the real world is quite messy. In comparison, the most advanced simulations and setups utilize seemingly limitless variables and assumptions to analyze behaviors and actions based on real data.

Within simulations, you can also define multiple metrics as well from all your attributes and data inputs. You can track metrics like utilization rates, throughput, wait times, and queue lengths to further optimize and perform risk analysis.

The beauty of simulations is you can *replicate* scenarios without needing to spend a large amount of money upfront first. While they may not be perfect replications, you can get "good enough" replications within a simulation and perform *thousands, if not more,* of replications in the time it takes to do it once in the real world. For example, you could recreate your work process and simulations can estimate what may happen with just one minor or major change. You could also recreate floor plans and develop models for you, or your users, to experience in a virtual setting, like walking through a house or a flight simulator.

This also extends beyond education systems into other critical industries like medicine and hospitals. For example, a single simulation can model an entire process, start-to-finish, about a patient's journey and see where issues may crop up, given data like service time, interarrival times, chance of issues occurring, risk of failure and failure repair times, and speed of personnel moving throughout the hospital. Additionally, it ties into other existing engineering topics such as optimization and operations research.

Overall, the possibilities for what simulations can do only increases as technology improves.

### **Operations Research (OR) and Data Science (DS)**

If you've ever had an interest in machine learning (ML), then you've probably heard of operations research at least, which is applied mathematics. It's been around for a long time since at least World War 2 and more specifically at least since the work of Morse and Kimball (1951). There's applications in a lot of areas like airlines, logistics, grocery stores, your route from point A to point B, etc. Some examples of where these topics are used are embedded in other topics I've discussed throughout this chapter and some parts in this book.

As for math requirements, I'd say both Data Science and Operations Research requires knowledge in Calculus, Algebra, and Statistics. If you don't have that knowledge, you'll be hard pressed to figure out algorithms, distributions, and any models you encounter and be less effective as a result.

While OR largely covers mathematical optimization, it also focuses on statistics and forecasting as well. The core of OR is inputs and models; these two factors affect what your outputs are and the quality of said outputs. A perfect solution is *possible*, but may take an extremely long, and often unreasonable, time to brute force a solution on any given model.
- For the mathematically inclined reader, look further into P vs NP (polynomial time vs nondeterministic polynomial time) or computational complexity.

The main goal of OR is to get a solution as close to optimal as possible. Fully optimal may take too much time so we aim for 99.9% instead of 100%, like antibacterial soap in a bathroom, because we want a working model that generates a feasible solution in a reasonable amount of time. That self-imposed restriction is also there because some problems don't have the memory capacity to be solved at the scale they demand. Therefore, a model may need tweaking, such as adjusting weights, constraints, and the objective function(s), or even splitting apart one model into multiple models or subsets of a problem.

Data Science (DS) is related to OR and has overlap with it, but is several decades younger by comparison and some perspectives may view DS as a matured and better developed/validated version of OR. Compared to OR, data science strives for accurate models and utilizes real world data to prove the model's value and ensure that model is reproducible, so those perspectives are valid.

Software and technology developments solved many problems existing in OR, so DS (as of writing this in 2026) appears more popular and in demand because machine learning and AI is trending as a "new" problem space. Nevertheless, OR may be better at optimization with heuristics and solvers, whereas DS may be better for general problems regarding analytics.

### **Ergonomics (Human Factors)**

Many objects you're utilizing today utilize ergonomics in some way, shape, or form. It could be your chair, a desk, how people want you to position a keyboard and monitor, the utensils you use in the kitchen, and countless more items. You may've been introduced to it before from a separate source, [like OSHA](https://www.osha.gov/ergonomics), or as part of a training because of its relation to musculoskeletal disorders, fatigue, overexertion, and other conditions (2022).

Ergonomics is studying how people function in their environment or how to fit the job to a person. Its goal is optimizing health of the person and their work productivity. In education systems, it's how you can best accommodate all staff and students in their given environment, whether it is at home or a workplace.

This field isn't limited to engineers and architects and includes other professionals like doctors and designers. The former two professions utilize it because it informs *how* they should design something for human interaction. Humans are, more often than not, using the products afterall.

To put it in an example, let's say you want to design a chair for someone to sit in. First, there's a problem to define: you need to support a human body for prolonged sitting periods and reduce stress on their spine, hips, and legs. Let's also say the hypothesized solution, for your first iteration, is an adjustable, body-conforming chair design. The first iteration is typically a reasonable, educated guess based on the information you know and the assumptions you have going into the problem.

Much like any other project, you're handling scope, resources, and time. You'll still need to figure out what kind of chair you want, its context and use cases, test out other types of chairs (if they exist), and do background research. This is to mitigate the effects of bias going into the design with a picture in your head and helping ground that reality. 
- When in doubt, figure out the user need and use cases *before* spending time and money testing current chairs.

As for a general process to verify a solution after initial background research:
- Anthropometric Data: What body measurement data do I need, like seat height, torso length, hip width, and their size distributions (typically 5% to 95% of a population) to accommodate as many people as is reasonable and feasible.
- Biological/Biomechanical Analysis: What background knowledge do I need before designing, like spinal loads, flexion angles, and so on.
- Trials/Prototypes: Utilizing sensors to detect where the most pressure accumulates at, checking for deficiencies and areas where discomfort occurs, measuring and observing someone's posture in a chair, and so on.
- Iterations: Repeating and refining the design until it reaches acceptable levels.

While you're designing, you may modify your solution partially or entirely during this process. Perhaps a headrest may or may not be needed, armrests may be modified, the tilt and recline may go back less or more, and other factors. You also don't need to go straight into advanced design software; sometimes a simple concept sketch put out into the environment reaches a solution quicker.

During testing, you may also create and utilize benchmarks like adjustability, spinal load, pressure distribution, composition and materials, and more. Certain products, like chairs in the example, may also have formalized, third-party standards like [ANSI/BIFMA X5.1](https://www.bifma.org/page/StandardsShortDesc) (2024) and [BS EN 1335](https://www.en-standard.eu/bs-en-1335-1-2020-a1-2022-office-furniture-office-work-chair-dimensions-determination-of-dimensions/) (2023) for office chairs.

Chairs are just one example out of countless many. You can utilize ergonomics in other places, such as computers, software, consoles, cars, tables, and many more.

### **Push vs Pull Systems**

I'll assume my readers have been to a restaurant before.

Say for example, you go to a restaurant and you place a food order. The staff works behind the scenes to fulfill the order and then bring you the food you ordered. That's a pull system.

Now, say the restaurant places pre-made burgers and hotdogs on a warming rack. Customers can grab these burgers, pay at the appropriate station, then enjoy their meal. That's a push system.

Push systems make goods and services available in advance in anticipation of demand, whereas pull systems prepare goods and services as a response to demand and incoming requests. Pull systems are responsive and a means to reduce overproduction of goods, whereas push systems are predictive and purposely overstock to stay ahead of demand and avoid running short on supply.

You can conduct the logistics behind supplies and food at educational facilities, so that's one example for educational systems. You can also do this for multiple types of facilities related to education and outside of education, like a push system for groceries at a grocery store and books at a bookstore, or a pull system for lean manufacturing processes.

Six Sigma is one way these systems are utilized for process improvement in applications like the Toyota Production System, but can be expanded into other fields like education systems (Ohno, 1988).

## **Bibliography**

1. BIFMA. (2024). *Standards Descriptions*. BIFMA. [https://www.bifma.org/page/StandardsShortDesc](https://www.bifma.org/page/StandardsShortDesc)

1. European Standards. (2023, November 1). *BS EN 1335-1:2020+A1:2022 Office furniture. Office work chair Dimensions. Determination of dimensions.* en-Standard.eu. [https://www.en-standard.eu/bs-en-1335-1-2020-a1-2022-office-furniture-office-work-chair-dimensions-determination-of-dimensions/](https://www.en-standard.eu/bs-en-1335-1-2020-a1-2022-office-furniture-office-work-chair-dimensions-determination-of-dimensions/)

1. Hunt, A., Thomas, D. (1999). *The Pragmatic Programmer: From Journeyman to Master.* Addison Wesley. ISBN 978-0201616224. p. 95, footnote.
    - Archive Link: [https://archive.org/details/isbn_9780201616224](https://archive.org/details/isbn_9780201616224)

1. International Code Council (ICC). (2024). CHAPTER 3 BUILDING PLANNING - 2024 INTERNATIONAL RESIDENTIAL CODE (IRC). Iccsafe.org. [https://codes.iccsafe.org/content/IRC2024V2.0/chapter-3-building-planning](https://codes.iccsafe.org/content/IRC2024V2.0/chapter-3-building-planning)

1. International Code Council (ICC). (2024). *I-Codes.* Codes.iccsafe.org. [https://codes.iccsafe.org/codes/i-codes](https://codes.iccsafe.org/codes/i-codes)

2. Morse, P. M., & Kimball, G. E. (1951). *Methods of Operations Research.* MIT Press. ISBN: 9780262130059

2. *NCS Content - United States National CAD Standard - V7.* (2025). Nationalcadstandard.org. [https://www.nationalcadstandard.org/ncs7/content.php](https://www.nationalcadstandard.org/ncs7/content.php)

2. Newnan, D. G., Eschenbach, T. G., & Lavelle, J. P. (2012). *Engineering Economic Analysis.* ISBN-10: 0199778043.

2. Norman, D. (2013). *The Design of Everyday Things.* MIT Press. (Original work published 1988)

3. Ohno, T. (1988). *Toyota production system: Beyond large-scale production.* Productivity Press.
    - Originally published in Japanese on 1978.

3. OSHA. (2022). Ergonomics - Overview - Occupational Safety and Health Administration. Www.osha.gov; Occupational Safety and Health Administration. [https://www.osha.gov/ergonomics](https://www.osha.gov/ergonomics)

3. Slater, T. (2012). *What is Interoperability?*. Network Centric Operations Industry Consortium (NCOIC).
    - Archive Link: [https://web.archive.org/web/20140714143139/http://www.ncoic.org/what-is-interoperability](https://web.archive.org/web/20140714143139/http://www.ncoic.org/what-is-interoperability)

3. Tompkins, J. A., White, J. A., Bozer, Y. A., & Tanchoco, J. M. A. (2010). *Facilities Planning* (4th ed.). John Wiley & Sons, Inc.

## **[Next Chapter](Z022_Action_Plan.html)**