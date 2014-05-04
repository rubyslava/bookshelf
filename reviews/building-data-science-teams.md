# [Building Data Science Teams](http://www.amazon.com/Building-Data-Science-Teams-Patil-ebook/dp/B005O4U3ZE?tag=rubyslava-20)

**@danielharcek**

> Measure everything you can, and think about what the data you’ve collected means.

## The Book

Building data science teams is a article published in September 2011, printed as a short brochure for Strata conference, you can get it for free as a Kindle ebook from Amazon as well. [Dj Patil](https://twitter.com/dpatil) summarizes his experiences of building data science teams mainly in LinkedIn corporation and gives overview what is data science about. Even if the material is of older data, at the time of this review, most of the content is still relevant, some tools and concepts are even industry standards.

The book consists of following sections:

* Being Data Driven
* The Roles of a Data Scientist
* What Makes a Data Scientist
* Building the LinkedIn Data Science Team
* Reinvention

### Being Data Driven

Author tries to give definition of what it is to be data driven. I found the definition rather superficial, but that could be expected. The metric how to measure the _data-driveness_ of a company is _using data effectively_. In other words, the point is to use data to create data products which help the company to suceed or to accomplish it’s mission.
Second nature of data driven companies is the following loop: Questions -> Experiments -> Collecting Data -> Doing Analysis -> Building products around findings. 
This chapter contains also examples of sucessfull data-science applications within different industries. It's a good source of inspiration.
As a example of a platform for handling streaming data, author give [S4](http://incubator.apache.org/s4/) from Yahoo, but it seems this days [Storm](http://storm.incubator.apache.org/) and [Spark](http://spark.apache.org/streaming/) are getting much more attention.
DJ Patil urges to liberalize the data and allow everyone to experiment on top of the datasets. People shall be curious _about why the data has changed or is not changing_.

### The Roles of a Data Scientist

This chapter is the most extensive. Author lists usual roles when data scientist fit in, or which can strongly benefit from being data driven. Each role has a concise explanation of it's context, expected tasks and interactions within the company ecosystem.

Roles covered are:
* Decision sciences and business intelligence
* Product and marketing analytics
* Fraud, abuse, risk and security
* Data services and operations
* Data engineering and infrastructure
* Organizational and reporting alignment

Interesting example how data can support company strategy is using data to _drive blogging as a marketing strategy_ as Mint, OkCupi, Linkedin and Facebook sucessfuly do.  

Author also discuss different models how to integrate data science roles within the company. I like at most the _hub-and-spoke_ model of a central team, but it’s members are embedded within actual teams itself. He also shares three lessons he learned when building the teams, in short, keeping people together to eliminate impact of trivial issues, to democratize the data and train people to fish, and to stay in regular contact and communication. To me, all of these are pretty much about sharing the knowledge (communicate) effectively. 

### What Makes a Data Scientist

Author shares characteristics which to look for when looking for data scientists. I consider _curiosity_ important in general for every single role. The most important one - in relation to data scientists, to me is _storytelling_. Ability to summarize the findings, create a story and communicate if effectively. Anyone should be able to make a decision based on data scientists report.

He claims that everyone has a chance to become a data scientist. "People often assume that data scientists need a background in computer sci- ence. In my experience, that hasn’t been the case: my best data scientists have come from very different backgrounds. The inventor of LinkedIn’s People You May Know was an experimental physicist."

#### Hiring a talent
This chapter also contains a essay on how to hire and develop the talent of new hires. Principles - time, trust, communication -  desribed are generic and applicable to any kind of team, even a non-tech team. **It’s worth reading for anyone, especially to those leading teams and hiring**. From my perspective, the essence is effective communication and learning to anticipate each other’s needs. This is a key to having highly functional and coherent teams. Trust is a underlying principle to that.

### Building the LinkedIn Data Science Team

> A data science team isn’t just people: it’s tooling, processes, the interaction between the team and the rest of the company, and more.

LinkedIn approach was to create a full product team which _includes people working in design, web development, engineering, product marketing, and operations. They all understand and work with data, and I consider them all data scientists. We intentionally kept the distinction between different roles in the group blurry._
This is how data science became a part of building and adding a value to the company. Automation is a crucial component which allows to do the creative work. Another crucial part is to have a culture of prioritization.

> everyone in the group needs to be able to ask about the priority of incoming requests. Everything can’t be urgent.

This is often missing, and prioritization does not work well.

## Closure

This piece is definitely worth reading for anyone interested in data science introduction, especially for people  being exposed to contact with data science teams. It's not a technical reading, but it might be worth to read it for technical people to understand the business needs which feed the data science gold-fever.


