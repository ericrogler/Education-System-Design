---
title: 29. Engineering & Architecture
layout: default
nav_order: 21
---
# Engineering & Architecture

### [Previous Chapter](Z021_Design_Systems_EdTech.html)

## **Short Answer**

> 
    “Any idiot can build a bridge that stands, but it takes an engineer to build a bridge that barely stands.”
- Anonymous
  - *Finding the source for this quotation is a Herculean task, so if someone does know the original source, let me know.*

---
There's a lot of things to consider when designing educational systems.

 Two of these things are engineering and architecture as you may deal with physical buildings with physical humans and explore how and why to improve your processes.

## **Long Answer**

I'll identify four core branches of engineering: Chemical, Civil, Electrical, and Mechanical. Each branch has sub-disciplines tying back into one (or more) of these four. There's many types of engineers and plenty of crossover, with the primary difference being the core science involved in their discipline. 

Think of engineering as a method for problem solving. Industrial engineers (my degree, so expect some bias), use that method to optimize systems; typically with the goal of minimizing costs, maximizing performance, or both. Meanwhile, chemical engineers may utilize chemicals and energy primarily through chemistry while civil engineers utilize earth sciences to design infrastructure and habitats.

Architecture is similar to engineering, except you take that problem solving and apply it to structures and land usage. You're now minimizing the cost of materials and labor to fit within budget and deadlines while meeting a desired quality through many factors, like aesthetics, accessibility, and structural integrity.

The good news is you can do a lot with these disciplines and apply their concepts to many other fields. For example, Donald "Don" Norman, who has an electrical engineering degree, created many design concepts for user experience and human-centered design (The Frankline Institute, 2014) still in use today, as of 2026, across various texts and books like *The Design of Everyday Things* (1988/2013). 

The bad news is you need math and science skills, and enough creativity and critical thinking skills, to effectively do those disciplines.

This chapter is going to have many technical terms. That's intentional. This is the chance for me to talk about a lot of engineering and architecture concepts, because I have education and work experience with these kinds of things. For readers, think of this chapter as topics from these fields you can use to design educational systems.
- No I'm not saying any of this as professional engineering or architecture advice. That requires someone with a stamp and a legally protected title, like Professional Engineer or Professional Architect. I did, however, have a Class A General Contractor license.
- i.e. Expect me to highlight Industrial Engineering concepts in particular.

As a reminder, you could easily have several books on each topic here, so if you want to learn more, you are free to look up other sources. I'll try my best to summarize them, so let's get into it in no particular order.

### **Physical Building Codes**

You could easily have an entire bookcase on this topic alone. I'll try my best to summarize it.

In terms of background knowledge requirements for general contractor work, **you can get by with Algebra for simpler buildings and most residential designs (Class C and Class B), but Calculus (and sciences utilizing Calculus+) and beyond is desired for complex building designs (Class A).** Unless you're the engineer of record, you're likely reading and verifying engineering documents, cost estimates, and schedules instead of doing all the math work yourself.

In the United States, as of March 2026, there are two primary codes to follow: IBC (International Building Code) and IRC (International Residential Code). There's also a suite of other codes, such as electrical, plumbing, mechanical, and fire codes and a code for remodeling projects. All of these codes created by the International Code Council are collectively called "I-Codes" (ICC, 2024). 
- Additionally, unless your educational facilities are hosted on residential property *and* zoned as residential in the municipality, expect to use IBC instead of IRC.

If you're in a position where you need to review physical building codes, there's a trick even a General Contractor (Class A) uses: *knowing* where to look. I'll tell you right now memorizing these code books in their entirety is reserved for inspectors and code officials, which you are very likely *not* that. It is an endeavor in wasted time and madness to memorize every single code detail. Instead of memorizing every detail, you should memorize *where* to find the details. There's nothing wrong with reading building code from start to finish, but it may be overwhelming if you're new to their structure and terminology. 

Alternatively, you may fully memorize a few specific chapters or several details spread across many chapters, then know how to reference the book for other details depending on what you're working with.
- For example, Chapter 10 Means of Egress and Chapter 11 Accessibility always comes up in your designs, so you should memorize details in these chapters, but Chapter 2 Definitions is basically just a dictionary, so you can search up particular words if they come up and memorize only the most common words.

Therefore, it may look something like this:
- Figure out the specific code required for the area. This is typically by state, but can vary across local jurisdictions as well. 
    - For example, the enforced IRC edition can differ between two adjacent cities.
- Have the links to said code book(s) handy (e.g. [ICC I-Code by Year](https://codes.iccsafe.org/codes/i-codes) website), even if it is read-only access.
    - Typically these are available online, as physical textbooks, or downloadable files.
- Look for the appropriate building codebook you need to reference to access its contents. 
- Look for the chapter with a title that aligns closely to what you need to look up.
- In said chapter, find the section you think your answer is likely to be at.
- Utilize a command, like Ctrl+F (or Cmd+F) to find specific phrases.
- See if the text provides an appropriate answer. If not, repeat the process.

You may also encounter situations where a specific code will reference another code in a different code book, mention where exceptions or outlines are determined by other sections, or talk about guidelines in one section that is in accordance with another section. Think of it as a giant, interconnected web where one small part of a codebook can reference multiple things at once, so expect to be jumping around quite often between seemingly unrelated areas.

Additionally, some rules and guidelines are accompanied by maps to hightlight where a code variation applies. This usually relates to material science, biology, and environmental effects, such as wind speeds, weathering of concrete, seismic design, stress design for snow loads, termite infestations, and so on.

**Remember: Do NOT memorize the entirety of these code books. Do learn how you can best search information within them.**

### **"Shorthand" Building Knowledge Examples**

Most houses I've lived in I've remodeled myself utilizing IRC. I'll provide you simpler examples of factoids I memorized as I designed floor plans. For reference, IRC 2024 and Chapter 3 Building Planning provide many common details, but I'm naming off several that immediately come to mind and paraphrasing the exact wording (ICC, 2024).
- Most interior walls are 2x4 with studs at 12 OC or 16 OC
    - "OC" = On-center, measuring the distance from the center of one stud (structural wood plank) to the center of the nearest stud.
    - Many tape measurers have red squares/specialized markings on certain measurements to make measuring OC along a wall easier (e.g. a "red square" number every 16 inches)
- Most exterior walls are 2x6 (or larger) with studs at 12 OC or 16 OC.
- Egress windows
- Habitable space ceiling heights shall be no less than 7 feet height, except for bathrooms, toilet rooms, and laundry rooms with 6 feet 8 inches height, non-habitable basement spaces at 6 feet 8 inches height, and 6 feet 4 inches height for beam, duct, etc. exceptions.
- Concrete slabs are at least 4 inches thick and require joints spaced no more than 4 feet apart.
- Egress windows are at least 24 inch high by 20 inch wide openings, with a clear opening area of ~6 square feet (5.7 square feet exactly) and cannot be higher than 44 inches off finished floor.
- 1 pound per square foot = 0.0479 kPa (kilo-Pascals)
- 1 mile per hour = 0.447 m/s (meters per second)
- Hallways, and stairways, in new construction are generally at least 36 to 42 inches wide.
- At least one door, designated as egress, is at least 32 inches wide and 78 inches high.
    - Other doors are generally at least 30 inches wide, but exact details vary widely by municipality.

There's plenty more to write about, but I'd rather not make too large a list here. 

Much like mental math, you want to memorize information that quickly enables decision making and gets through frequently occurring, but minor, work. For harder items, or where you'll reference specific formulae, it is expected you'll look it up from time to time.

### **Graphics**

Graphics relates to schematics and blueprints or how something is built. This could be something small, like the design of a screw and its thread placement, or something large, like a skyscraper building.

If you're designing the facilities where you'll implement education systems, you should have passing familiarity with how to read plans. While you could be adept enough to design your own plans, understanding how they're written leaves you the option of contracting out another building service to assist on the project and you knowing how to verify progress at each step.
- Even if you're the designer, you'll need an engineer/architect of record to "stamp" it for approval before it may be utilized in practice.

Understanding plans is basically understanding symbols and how they're drawn. For engineering plans, the exact symbology used depends on the software plans are drawn in, but they typically remain consistent across software tools. For example, SolidWorks has a  For building plans, the information required and the CAD (computer-aided design) standards are subject to state control (and local reviewing authorities, if applicable). 
- One such standard at the time of writing (March 2026), albeit paid access, is from the [United States National CAD Standard, or NCS]((https://www.nationalcadstandard.org/ncs7/content.php)) (2025).

This include many different types of graphics, such as topography maps, electrical plans, site plans and floor plans, exploded views, and so on. There's many free sources available to learn about plans as you encounter them, so I won't list them here for brevity's sake. 

Of particular note for my own endeavors were "topo" (topographic) maps and site plans. Knowing how to read topo maps has use inside and outside of work and lets you interpret terrain features, map scales, contour lines, locations of vegetation, triangulating locations on a map, and more. Site plans are useful as they provide a high-level overview of an entire site (i.e. a zoned property) and the location of features like building, foliage, water, road, and parking lot placements.

### **Facility Planning and Production Planning & Inventory Control (PPIC)**

*Notice: Primary source for this section is "Facilities Planning" by Tompkins et al. (2010)*

The level of math required for full understanding of this topic is multivariate Calculus.

Though it sounds simple and these topics are catered primarily towards manufacturing, it still encompasses quite a bit. Imagine you're planning out a facility and you have X amount of funds available to set it up. You'll need to consider many things, such as:
- Maximizing ROI (return on investment) and ROA (return on assets)
- How to cut down on unneccessary costs
- Determining demand
- Determining production capacity (and available supply)
- Ways to automate processes vs manually doing it
- How to maintain existing inventory and allocate space to store it.
- Where to acquire raw materials or base components to bring into a facility to then process it.

You may think "what does this have to do with education systems" and the answer is *a lot of things.* Education systems will encounter problems with resources, capacity, and flow like manufacturing systems will. You still have production, which is delivering quality learning, inventory for resources to make said learning happen, and planning to figure out schedules, where to allocate people, organizing how content is deliver, handling enrollment and student intake, and forecasting demand and costs out in the future. It could even be perfecting how students may pass along materials from one desk to another desk while applying models for conveyors in a new way.

There's also many parts that directly translate to education systems and are present in architecture and engineering, such as handling environment constraints and utilizing layout planning models and design algorithms like CRAFT, MCRAFT, and BLOCPLAN. Educators should strive to optimize how the space in their classroom is utilized, much like how a manufacturer wants to maximize production capabilities in a given space. Perhaps you're reorganizing something simple, like a closet, and could use a high-powered solution like a block stacking model to help you optimize it too.

Recalling the sections on graphics and building codes, you may need to consider other design aspects, such as traffic flow of people (or vehicles, animals, etc.), the physical constraints of the space you're working in (e.g. a rectangle vs unorthodox shape), where to retrieve, transport, and store goods at, and so on.

On PPIC in particular, it ties back into facility planning because how you plan a facility, and its capabilities, determines what you can reasonably forecast and accommodate according to trends and incoming data. Think about it think way: facility planning is determing how you fit everything into place and PPIC ensures the resulting production process is efficient, cost-effective, and meets all demands and requirements.

These topics, and related topics, altogether provide processes to assist with planning, scheduling, and controlling processes and systems.

### **Programming**

Yes, programming is a thing for both engineers and architects, and includes languages like SQL, Python, R, Java, COBOL, and so on.

Architects may utilize software and combine architecture with programming, because it's what design software does. They might not design the software itself, but they can utilize programming languages to build plugins and create custom solutions as tools to enhance their work processes and outputs. It's in service of something else, like geometry or workflow automation, and the programming stays close to the design artifact/software.

Engineer, and by extension developer, programming is more technical in nature, as it provides the means to service other fields and accomplish many things. For example, Python with processing algorithms and data science, SQL with transforming and cleaning up data, VBA to automate tasks inside of existing software solutions, Matlab for analysis, and so on. The code itself is a deliverable, or a part of it, rather than a tool to enhance current solutions or create new solutions.

Generally speaking, programming is used to conduct calculations, speed up processes, automate tasks, or do things that a human cannot do within their own limits. Modern technology enabled more standalone solutions and scripting, like PowerBI or Excel bringing traditionally engineering work and data to non-engineer audiences.

At the end of the day, programming is simply a means to an end. A tool in a toolkit. Many professionals utilizing programming aren't actually engineers or architects, but people using it to figure out what problem they're actually trying to solve.

### **Economic Analysis**

Professionals need to know how money works. It's what affects decisions in the short-term and the long-term, helps determine if a project is even worth putting money into, and determine which options are the best amongst multiple alternatives/options.

Normally this topic is in the realm of finance and business, but engineering and architecture also utilize it. While you could get by with many pre-defined formulae and plugging in valuables for each variable in equations, engineering economic analysis will expect you to know multivariate calculus to fully understand it.

From the Metrics chapter, recall that metrics are measures to reveal whether your current system performs as intended or requires changes. In this topic, that includes different metrics, such as payback time, return on investment, and net present value, in addition to new tools and formulae to define said metrics.

It also includes delving into topics I've found students in high school wish they knew before they got older, such as explaining taxes, savings, investments, expected costs, depreciation, cash flows, equity, debt, and the time value of money. You may also use this topic to help determine the cost of a constraint or rule, such as a new union policy going into place. On cash flows in particular, it's where people may realize, perhaps for the first time, that cash flow is typically negative in the beginning because you're recuperating from your initial investment.

This topic is important for another reason: it gives you the tools to assign monetary values to everything you may do within an engineering (or architectural) context. When I was in college learning about engineering, many optimizations and systems were explained without delving too deeply into financials, at least in undergraduate studies, so this topic shored up that gap.

### **Simulation**

For readers familiar with video games, think about the games where you need to build a base or a city and manage all of the moving parts in it, such as resource flow, logistics and transportation, and creating products (perhaps in a factory environment). While the video games of today, as of 2026, are not capable of fully automating all the complexities of real-life environments, they do capture a lot of the essence.

For readers unfamiliar with video games, think about what it's like to go to school, the store, or even to another person's house. You leave from one location, take X amount of time to get there, spend Y time at that other location, and perhaps encounter an issue delaying you by Z amount of time. This is one example a simulation applies; going from point A to point B in order to accomplish some task.

Simple examples can be studied through simulations and we account for many things, such as entities, attribute, logic, decisions, workstations, service points, capacity, processing times, failure/repair cycles, travel paths, types of flow, and many, many, more. This is why I say something like a video game can capture the *essence* of it through models. It'll get the core idea down as it tries to emulates an environment, but the real world is quite messy. In comparison, the most advanced simulations and setups utilize seemingly limitless variables and assumptions to analyze behaviors and actions based on real data.

Within simulations, you can also define multiple metrics as well from all your attributes and data inputs. You can track metrics like utilization rates, thoroughput, wait times, and queue lengths to further optimize and perform risk analysis.

The beauty of simulations is you can *replicate* scenarios without needing to spend a large amount of money upfront first. While they may not be perfect replications, you can get "good enough" replications within a simulation and perform *thousands, if not more,* of replications in the time it takes to do it once in the real world. For example, you could recreate your work process and simulations can estimate what may happen with just one minor or major change. You could also recreate floor plans and develop models for you, or your users, to experience in a virtual setting, like walking through a house or a flight simulator.

This also extends beyond education systems into other critical industries like medicine and hospitals. A single simulation can cover one process, start-to-finish, about a patient's journey and see where issues may crop up, given data like service time, interarrival times, chance of issues occurring, and speed of personnel moving throughout the hospital. Additionally, it ties into other existing engineering topics such as optimization and operations research.

Overall, the possibilities for what simulations can do only increases as technology improves.

### **Operations Research (OR) and Data Science (DS)**

If you've ever had an interest in machine learning (ML), then you've probably heard of operations research at least, which is applied mathematics. It's been around for a long time since at least World War 2 and has applications in a lot of areas, like airlines, logistics, grocery stores, your route from point A to point B, etc. Some examples of where these topics are used are embedded in other topics I've discussed throughout this chapter and some parts in this book.

As for math requirements, I'd say both Data Science and Operations Research requires knowledge in Calculus, Algebra, and Statistics. If you don't have that knowledge, you'll be hard pressed to figure out algorithms, distributions, and any models you encounter and be less effective.

While OR largely covers mathematical optimization, it also branches out and focuses on statistics and forecasting as well. The core of OR is inputs and models; these two factors affect what your outputs are and the quality of said outputs. A perfect solution is possible, but may take an extremely long time to brute force a solution on any given model.

The main goal of OR is to get a solution as close to optimal as possible. Fully optimal takes too much time so we aim for 99.9% instead of 100%, like antibacterial soap in a bathroom, because we want a working model that generates a solution in a reasonable amount of time. That self-imposed restriction is also there because some problems don't have the memory capacity to be solved at the scale they demand. Therefore, a model may need tweaking, such as adjusting weights, constraints, and the objective function(s), or even splitting apart one model into multiple models or subsets of a problem.

Another field, Data Science (DS) is the umbrella OR falls under, but some perspectives view DS as a matured and better developed/validated version of OR. Compared to OR, Data science strives for accurate models and utilizes real world data to prove the model's value and ensure that model is reproducible, so those perspectives are valid. 

Software and technology developments solved many problems existing in OR, so DS (as of writing this in 2026) appears more popular and in demand (as of 2026) because machine learning and AI is also trending. Nevertheless, I think OR is better at optimization with heuristics and solvers, whereas DS is better for general problems regarding analytics.

### **Ergonomics (Human Factors)**

Many objects you're utilizing today have ergonomics considered in some way, shape, or form. It could be your chair, the desk, how people want you to position a keyboard and monitor, the utensils you use in the kitchen, and countless more. You may've been introduced to it before from a separate source, [like OSHA](https://www.osha.gov/ergonomics), or as part of a training because of its relation to musculoskeletal disorders, fatigue, overexertion, and so on (2022).

Ergonomics is studying how people function in their environment or how to fit the job to a person. Its goal is optimizing health of the person and their work productivity. In education systems, it's how you can best accommodate all staff and students in their given environment, whether it is at home or a workplace.

This field isn't limited to engineers and architects and includes other professionals like doctors and designers. The former two professions utilize it because it informs *how* they should design something for human interaction.

To put it in an example, let's say you want to design a chair for someone to sit in. First, there's a problem to define: to support a human body for prolonged sitting periods and reduce stress on spine, hips, and legs. The hypothesized solution, for your first iteration, is an adjustable, body-conforming chair design.

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

Now, say the restaurant places pre-made burgers and hotdogs on a warming rack where customers can grab one, pay at the appropriate station, then enjoy their meal. This is a push system.

Push systems make goods and services available in advance in anticipation of demand, whereas pull systems prepare goods and services as a response to demand and incoming requests.

You can conduct the logistics behind supplies and food at educational facilities, so that's one example for educational systems. You can also do this for multiple types of facilities related to education and outside of education, like a push system for groceries at a grocery store and books at a bookstore, or a pull system for lean manufacturing processes.

The advantages for each system also differ. Pull systems are responsive and a means to reduce overproduction of goods, whereas push systems are predictive and purposely overstock to avoid running short on supply.

Six Sigma is one way these systems are utilized for process improvement if you're interested in more about processes like these (6Sigma, 2018).

## **Bibliography**

1. 6Sigma.us. (2018, March 26). *In Lean Six Sigma, Pull Don’t Push.* SixSigma.us. [https://www.6sigma.us/lean-six-sigma-articles/lean-six-sigma-pull-dont-push/](https://www.6sigma.us/lean-six-sigma-articles/lean-six-sigma-pull-dont-push/)

1. BIFMA. (2024). *Standards Descriptions*. BIFMA. [https://www.bifma.org/page/StandardsShortDesc](https://www.bifma.org/page/StandardsShortDesc)

1. European Standards. (2020). *BS EN 1335-1:2020+A1:2022 Office furniture. Office work chair Dimensions. Determination of dimensions.* en-Standard.eu. [https://www.en-standard.eu/bs-en-1335-1-2020-a1-2022-office-furniture-office-work-chair-dimensions-determination-of-dimensions/](https://www.en-standard.eu/bs-en-1335-1-2020-a1-2022-office-furniture-office-work-chair-dimensions-determination-of-dimensions/)

1. International Code Council (ICC). (2024). CHAPTER 3 BUILDING PLANNING - 2024 INTERNATIONAL RESIDENTIAL CODE (IRC). Iccsafe.org. [https://codes.iccsafe.org/content/IRC2024V2.0/chapter-3-building-planning](https://codes.iccsafe.org/content/IRC2024V2.0/chapter-3-building-planning)

1. International Code Council (ICC). (2024). *I-Codes.* Codes.iccsafe.org. [https://codes.iccsafe.org/codes/i-codes](https://codes.iccsafe.org/codes/i-codes)

2. *NCS Content | United States National CAD Standard - V7.* (2025). Nationalcadstandard.org. [https://www.nationalcadstandard.org/ncs7/content.php](https://www.nationalcadstandard.org/ncs7/content.php)

2. Norman, D. (2013). *The Design of Everyday Things.* MIT Press. (Original work published 1988)

3. OSHA. (2022). Ergonomics - Overview | Occupational Safety and Health Administration. Www.osha.gov; Occupational Safety and Health Administration. [https://www.osha.gov/ergonomics](https://www.osha.gov/ergonomics)

3. The Franklin Institute. (2014, January 15). *Donald Norman.* Fi.edu. [https://fi.edu/en/awards/laureates/donald-norman](https://fi.edu/en/awards/laureates/donald-norman)

3. Tompkins, J. A., White, J. A., Bozer, Y. A., & Tanchoco, J. M. A. (2010). *Facilities Planning* (4th ed.). John Wiley & Sons, Inc.

## **[Next Chapter](Z022_Action_Plan_Week_1.html)**