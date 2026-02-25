---
title: 13. Probability, Statistics, and Analysis
layout: default
nav_order: 15
---
# Probability, Statistics, and Analysis

### [Previous Chapter](Z007x_Math_And_Calculus.html)

## **Short Answer**

> Ludwig Boltzmann, who spent much of his life studying statistical mechanics, died in 1906, by his own hand. Paul Ehrenfest, carrying on the work, died similarly in 1933. Now it is our turn to study statistical mechanics. Perhaps it will be wise to approach the subject cautiously.
- David L. Goodstein, States of Matter (2014)

*Notice: This entire chapter is, at best, a surface level view of each topic covered here. That is intentional.*

The average person will probably not go beyond basic concepts for Probability and Statistics unless they seek it out themselves, is required for a job, are or going through a math-heavy field of study.
- E.g. you may not use statistical *calculations*, but you may utilize statistical *reasoning.*

You might be brushing up on probability and statistics due to the popularity of ML/AI (machine learning and artificial intelligence). **For a lot of use cases and business problems, like applying ready-made solutions, basic statistics is about all you need.** Going beyond, however, still requires advanced math like Calculus, Linear Algebra, and vectorized operations.

Knowing how to do something is great. Knowing where to look up something is good. Not knowing anything about it is a sign.

To encourage people to care about your research, analysis, etc. you must address the questions they need answered. This typically means a clear question with actionable items and inquiring what information needs to be found and used for decisions. 

Most analysis will employ tools, such as software like Excel or a coding language, as your primary means to figure out the answer(s). You'll also find data excels at humbling people and exposing what is *really* happening.

Sometimes analysis and modeling doesn't requiring any math. In fact, it may be counterintuitive to write an entire, custom solution when an existing model you can import solves the problem far faster and more accurately.

Statistical Significance does not imply Practical Significance.

## **Long Answer**

Learning Statistics and Probability typically requires an advanced mathematical foundation before beginning. This is usually 1-2 years of Calculus, with all of its prerequisites, and/or Linear Algebra; often accomplished around late high school/early college age for students (17-21 years old) as of 2025.

Do Statistics and Probability *require* Calculus? For their applied versions, no. For the math and theory behind it, I'd say yes. 

Should you still learn them? Personally, yes.

When I did Statistics courses (yes, not just one) as an undergraduate, they shyed away from Calculus and in-depth theorems and focused more on Algebra. That isn't necessarily *bad* as you can still do multiple things, like z-scores, ANOVA, t-tests, hypothesis testing, linear regression, and normal distributions. You will eventually hit a limit without knowledge of higher math though. 

Intuitive understanding is possible without formal training and one can learn the tricks to implement algorithms and procedures without insight in how they work. Older elementary school students or middle school students (ages 9-10+) could learn about parts of probability before knowing all the math behind it just fine. 

Someone could also have insight into how something should be done, but lack the knowledge of technical tools to solve their problems. When you dive into advanced proofs and theorems, as well as develop and modify ways to solve new problems, Calculus and formal training in math saves a lot of learning time and headaches down the line.

Statistics and Probability I find caters to students in two ways: those who need to understand these fields in-depth (e.g. data scientists, graduates and PhDs in technical fields, etc.) and those who may need to use them in general (basically everyone else). The former absolutely needs a strong math background, whereas the latter can get away with a weaker math background. Both backgrounds, however, should strive to understand *how* and *when* to use Statistics and Probability.

That said, lets go over concepts.

### **Probability vs Statistics**

Probability is the likelihood an event occurs. That's it, but also not it.

There's an inverse relationship between Probability and Statistics. 

Probability uses a model (or hypothesis) to predict what may happen in practice. 

Statistics starts with data obtained from practice (or experiments), observes what *has* happened, and figures out what the model/process is.

People may typically learn Probability before Statistics. Probability doesn't need Statistics, but Statistics does need Probability. Though one may not need the other, they still complement each other. Some curricula may account for this relationship and teach both topics at the same time, such as showing the probablistic object after talking about its theoretical definition.

### **Set Operations and You**

I'm going to assume readers may not be versed with set operations before continuing onwards. They're common in books such as *Introduction to Probability* by Bertsekas and Tsitsiklis as well as *Statistical Inference* by Casella and Berger (2021).
- Aside: These two specific books *do* assume basic training in Calculus.

There are comprehensive lists of set operations on the Internet through sources like [Math Vault](https://mathvault.ca/hub/higher-math/math-symbols/probability-statistics-symbols/#Variables) (2025) and [GeeksforGeeks](https://www.geeksforgeeks.org/maths/set-operations/) (2025). If you wish to read through them, that is fine; you won't need them to read the chapter.
- If those two resources are down in the future, doing a search on the Internet should uncover updated sources.

Why am I calling out set operations in particular? It's because not knowing set operations is like reading an English book without knowing English. You'll still "see" the symbols on paper but you won't "understand" the symbols, their context, and their applications. If you're unable to interpret what's in front of you, the knowledge cannot be properly utilized.

### **The Importance of Probability and Statistics**

For a quick answer: they are *both* important. 

**If you ever need mathematical explanations for problems with uncertainty and random phenomenon, probability and statistics are some of the best tools for the job.**

There's two ways people learn Statistics and Probability. One option is a formal course, such as one offered by a university in a classroom setting. Another option is buying materials like Sauro and Lewis' *Quantifying The User Experience* (2016) or using an alternative/online resource to get only the Statistics knowledge needed for the job. A third option is someone learning from independent sources like [3Blue1Brown](https://www.3blue1brown.com/) (2026) and [StatQuest](https://www.youtube.com/c/joshstarmer) (2025) to discover these topics on their own.
- Aside: I've done all three options.

I'm sure there's other ways besides these three, but these are the most common ways I've seen. For the scope of this book, we'll approach Statistics and Probability as an introductory topic.
- As a warning, many statistical methods come with key assumptions. Do NOT ignore those assumptions when applying these methods!

*Practical* Statistics is about knowing when to apply a statistical test (i.e. a formula/algorithm) to a given scenario. Factors deciding this include correlation vs comparison, the types of users in groups, the number of groups, whether or not you're estimating, binary data (yes/no type answers), and more. Essentially, you're looking at decision trees and determining the appropriate test to use when certain conditions are fulfilled.

After you correctly decide a statistical test or method, what comes next is knowing the proper application. For example, you may know that "z = (x - μ) / σ" is the z-score equation, but if you don't know how to get x (observed value), μ (population mean), and σ (variance), you'll still get an incorrect answer. Statistics is a constant test of your intelligence *and* wisdom when it comes to learning and applying it.

As for concepts in statistics and probability you'll see most often, I'd assume the following in no particular order:
1. Probability Distributions
2. Random Variables and Expectation (i.e. E(X))
3. Sampling and Central Limit Theorem
4. Statistical Inference
5. Conditional Probability & Dependence

There are a few other concepts you may see in practice and workplace settings: descriptive statistics, regression, and correlation vs causation.

Descriptive statistics are the foundations for data science and includes concepts typically introduced to younger students. This includes measures you may've learned at a younger age, such as mean, mode, median, and range. It also includes variability measures like variance and standard deviation as well as frequency distribution measures like histograms and boxplots. Descriptive statistics can solve some problems directly without spending additional time or money developing advanced models.

Regression is fitting a prediction against actual outcomes. The stronger the correlation, or relationship, between variables, the better your prediction is compared to real-world data. At the same time, a strong correlation can produce an incorrect model as well. Regression also has strict assumptions, such as linearity, independence, normally distributed, and homscedasticity, which cannot be violated at the risk of model invalidation. Common applications include prediction, estimation, and forecasting, but model effectiveness still depends on data quality.

The relationship between correlation and causation is pretty straightforward. Firstly, correlation does *not* imply causation. Causation means one variable directly influences another variable, such as one variable increasing because another decreases. Correlation is only describing the relationship, or association, between variables. Correlation and causation *together* serve as scientific evidence; correlation alone cannot be used as evidence for conclusions. A proper conclusion requires correlation alongside context acquired from experimental design, strong controls, and/or domain knowledge to.

### **Why Cover Analysis?**

You may be wondering why a book on teaching and instruction dedicated so much time to math.

Outside of author bias, the actual reason is simple: you need to know math to understand research which influences *every field.* How to read information and communicate findings is critical. Communication is already a skill you should be doing well as a teacher/instructor (assuming the person reading this *is* one, right?).

Now we go onto analysis; an application of all that math with some science and social skills.

The good news about data analysis is you don't *need* a lot of math skills to interpret results. You can see this best through visuals like infographs, dashboards, and more. You still need to know the context behind numbers though.

The bad news about data analysis is you need math skills to get the most out of data and generate effective results. Thankfully, you don't need a lot of hard data for every problem; that's costly and unrealistic for many cases.

### **Data Analysis Primer**

**There's three "laws" of data:**
1. Data are objective. Interpretation is subjective.
2. You can tell whatever story you want with data, if you know how to, for both good and evil.
3. Numbers/data without context are useless.

A lot of analysis isn't really designing the fancy dashboard or displaying results for clients. That's still an important part though because an interface which looks good also affects the perception of it. It still must answer a specific question, or set of questions, someone has when looking through it.

Most analysis comes from cleaning up data, understanding your user's (or student's) needs, understanding business objectives, actually analyzing the data, and storytelling. In other words, you're paving the wa

All of the earlier math concepts are still important because they open up further advanced topics like optimization, linear (and nonlinear) programming, forecasting, regression, and more.

### **What are Databases?**

A database is a repository of data and it's structured in some way, shape, or form. Data consists of facts, figures, quantities, and details collected about the environment. The data itself can be structured, semi-structured, or unstructured. You could also set up a clean, isolated environment through containerization with software like Docker.

Imagine now that you work in a warehourse. There are specialized machines handling logistics inside the warehourse and different machines handling logistics outside the warehouse. For example, you may use forklifts and cranes to transport and manipulate goods inside the warehourse, but you'd stick with trucks and vehicles to move goods outside the warehouse for other purposes. Using the equipment best suited for each environment ensures you remain effective and efficient.
- To any data specialists reading this: "SQL inside the database; Python outside the database" is a decent rule of thumb that hopefully doesn't age poorly.
    - Alternatively, Python is transportation and SQL is transformation in this case.

The average reader today in 2026 is likely familiar with spreadsheets through software like Google Sheets or Excel. That's structured data and organized into tables, worksheets, and cells. While spreadsheets *can* act as databases, it's not well-equipped to do so.

Depending on what type of analysis you're doing, spreadsheets alone may not suffice and you'll need to delve into data warehouses and coding languages. This may be due to capacity restrictions, inability to perform desired functions, data restrictions, or lack of raw processing power. This is where people typically go from spreadsheets to the realm of Python, SQL, and similar programming languages.

### **Cleaning Data**

Let's say you're a teacher or instructor and I give you information on the students you're teaching next year. It may contain what you'd expect to see, like names, grades in subjects, behavioral notes, emails, GPA, and so on.

That same information may also contain multiple formatting issues, missing values, consistency with capitalization errors, spacing problems, and a slew of countless other formatting issues. If you want to work with the information in the future without questioning your sanity, you'll have to *clean* it.

You may not ever work with a coding language in your life or very seldomly do. You may work with coding languages extensively. In either case, around 80% of all analysis work is cleaning data; the process of fixing or removing data. Much data and information you deal with isn't going to be neatly packaged for you. You'll have to mess with it and package it up yourself to do anything meaningful with it. This process is also extremely time consuming and most of the work needed.
- In practice, this is often done by specialists, such as data scientists, data engineers, and software architects, rather than the general populace because of data cleaning's perception as "menial work."

Cleaning data typically involves one, or more, of steps like so:
1. Removing duplicates
2. Filtering outliers
3. Handling missing (NULL) data
4. Fixing dates, times, numbers, etc.
5. Reassigning data types (number, float, text, etc.)
6. Correcting inconsistencies
7. Conversions

There's far more ways to clean it outside of the ones listed above. 

Messy data isn't always your fault either. While human error may lead to messy data, it can also be from external factors such as equipment, outdated information, and issues with software.

### **Transforming Data**

If data cleaning fixes inaccuracies and incompleteness, then data transformation establishes structures for further processing. You completed the quality check on your ingredients and now it's time to make the dish, to put it non-technically.
- There's also data *enrichment*, but I'm lumping it in with data transformation here.

Data transformation is the land of filters, aggregation, normalization, ETL (Extract, Transform, Load), and ELT (Extract, Load, Transform).

If you didn't clean the data from before, transforming data takes the messy data and makes it even messier. If you did clean data beforehand, you can safely expect fewer issues down the line.

Let's say you want to make a cake and you have a recipe. You've already ensured the ingredients are the correct ones, but still need to properly utilize those ingredients. There's plenty of complexity and techniques you could use, so understanding your ingredients and your objective with said ingredients is important. From there, you can identify the techniques you need and evaluate the impact as you finish making the cake.

"Clean," good, and prepared ingredients (data) leads to better cakes (reports). If you're starting with good ingredients every time, you also *consistently* make good cakes. If you can keep ingredients fresh, even when you double or triple the amount you're working with, then you can make even more cakes without sacrificing the taste or flavor. Additionally, if you're familiar with baking techniques and the recipe(s), you'll learn bettery ways to save time and costs for future cakes. Lastly, if you're an expert in baking, you can take what looked like simple cakes before and turn them into visualing stunning showstopper pieces. 

If you know your ingredients (data) are clean and your process transforms ingredients into well-designed cakes (meaningful presentations, reports, etc.), you've got a recipe for success.

### **Interpreting Data**

Rather than regale you with details worthy of an entirely new chapter, I'll keep this section short and link out to other resources explaining this better than myself. **I will say, however, you should have at least a basic understanding of Statistics and Probability *before* delving into scientific (and by extension education) research.**

The biggest requirement is you need to be able to interpret figures, tables, charts, and graphs, but also understand any underlying formulae and algorithms you come across and *why* they're set up that way. After that, looking up specific words as they appear will help you cover some knowledge gaps.

You may also notice some terminology crop up more often, or less often, depending on the field. "Noninferior" is one example you'll find common in medical research vs other fields.

For readers newer to scientific literature, Carey et al developed [ten simple rules for reading a scientific paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC7392212/) which succinctly describe how to *start* reading them properly for even non-technical audiences (2020).

**To copy the headers (rules) verbatim from the source above (Carey et al, 2020):**
1. Pick your reading goal
2. Understand the author’s goal
3. Ask six questions
    - Motivations, what they did and why, what results show, their interpretation of results, and what's next
4. Unpack each figure and table
5. Understand the formatting intentions
6. Be critical
7. Be kind
8. Be ready to go the extra mile
9. Talk about it
10. Build on it

For seasoned and newer readers, there's also terminology to cover. For terminology and specific algorithms, look up the term or symbol as they appear. Depending on the field and context, symbols may hold different meanings so don't immediately assume one symbol means something for every article. 

As for statistics, it's tough to answer this without knowing a specific background, purpose, context, and so on related to the research you're reviewing/conducting. The two primary categories are descriptive statistics, which summarizes the data acquired, and inferential statistics, which makes predictions and draws conclusions about the population in the data. You should expect to see techniques like correlation, regression, confidence intervals, p-values, and ANOVA used quite often.
- For specific tests, like t-tests and z-tests, you're unaware of, treat it like how you would terminology you do not understand and look it up as you reach it.
- Much research uses different methods for different types of data and questions. While some formulae and algorithms itself may stay consistent, expect context to change.

Finally, a lot of research doesn't actually make it to publication. There could be errors made in the process, the committee reviewing the paper decided not to approve it for publication, funding was cut, it wasn't ideal for science, it is (or became) classified, and so on are some of many reasons why it's not published in a peer-reviewed journal. Not being published isn't always an indicator of quality.
- Just because it's not *published* doesn't mean it might not show up in talks, posters, videos, online forums/sites, and so on.

## **Bibliography**

1. Bertsekas, D. P., & Tsitsiklis, J. N. (2008). *Introduction to probability.* Athena Scientific.

2. Carey, M. A., Steiner, K. L., & Petri, W. A. (2020). *Ten simple rules for reading a scientific paper.* PLoS Computational Biology, 16(7). [https://doi.org/10.1371/journal.pcbi.1008032](https://doi.org/10.1371/journal.pcbi.1008032)

2. Casella, G., & Berger, R. L. (2021). *Statistical Inference.* Cengage Learning.

3. GeeksforGeeks. (2025, Oct 6). *Set Operations.* GeeksforGeeks. [https://www.geeksforgeeks.org/maths/set-operations/](https://www.geeksforgeeks.org/maths/set-operations/)

3. Goodstein, D. L. (2014). *States of Matter.* Dover Publications.

4. *List of Probability and Statistics Symbols.* (2020, April 26). Math Vault. [https://mathvault.ca/hub/higher-math/math-symbols/probability-statistics-symbols/](https://mathvault.ca/hub/higher-math/math-symbols/probability-statistics-symbols/)

4. Sanderson, G. (2026). *3Blue1Brown*. 3Blue1Brown. [https://www.3blue1brown.com/](https://www.3blue1brown.com/)

5. Sauro, J., & Lewis, J. (2016). *Quantifying the User Experience: Practical Statistics for User Research.* Morgan Kaufmann.

6. Starmer, J. (2025). *StatQuest with Josh Starmer.* In YouTube. [https://www.youtube.com/channel/UCtYLUTtgS3k1Fg4y5tAhLbw](https://www.youtube.com/channel/UCtYLUTtgS3k1Fg4y5tAhLbw)

## **[Next Chapter](Z008_Source(s)_Of_Truth.html)**