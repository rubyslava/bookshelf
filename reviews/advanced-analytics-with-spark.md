[Advanced Analytics with Spark](http://www.amazon.com/Advanced-Analytics-Spark-Patterns-Learning-ebook/dp/B00VKTMQCK?tag=rubyslava-20)
============

@sevo_jakub
---------------


**TL;DR Several case studies for different data analysis tasks implemented using Spark. Applications of Read-Evaluate-Print Loop interface in the distributed environment. Great introductory tutorials with practical advices and references for further reading.**

The book demonstrates the application of Spark in many data analysis domains. It emphasizes the utility of application of the same code in the exploratory analysis of the data at scale and application of acquired knowledge and created models in production. One of the most important Spark features presented in the book is the availability of REPL (Read-Evaluate-Print Loop) environment known from other languages, such as R or Python, popular in data science community. Spark however allows one to use this environment for interactive analysis not only on a single machine, but it allows transparently distribute the workload to the whole cluster.

The application of Spark is demonstrated on multiple attractive topics and applications of data analysis and machine learning such as music recommendation using collaborative filtering, network traffic anomaly detection using data clustering or estimating investment risk using Monte Carlo simulation. These case studies provide simple tutorials for implementation of different data analysis tasks in Spark but at the same time provide basic theoretical and practical introduction to the method itself. Every case study focuses on the processed dataset at hand, but references to related materials and next steps are provided for further study. 

@adamliesko
---------------

**TL;DR If you are looking for an intro to data science, data analysis and machine learning at scale - this is the right book. Sure, there are others, maybe more popular books from O'Reilly considering these topics, but the authors of those are using R and Python and the books are  not focused on the performance and scalability. For closer details regarding Spark you can also take a look at this introductory Spark book - [Learning Spark](http://shop.oreilly.com/product/0636920028512.do)**

This book presents 9 case studies of data analysis applications in various domains. The topics are diverse and the authors always use real world datasets. Beside learning Spark and a data science you will also have the opportunity to gain insight about topics like taxi traffic in NYC, deforestation or neuroscience. Without any previous exposure or contact with machine learning readers might struggle to understand certain chapters, so I think it's good idea to actually try those examples yourself while reading and Google for further details about the used methods. Many of the chapters end only with basic models, which barely outperform the baselines, so if you want to, there is a lot of space for their improvement and further work. 

Spark itself provides it's users with APIs in three languages - Java, Scala and Python. This books successfully covers each one of these, although you can feel slight preference of a Scala throughout the book. For Scala starters - they always explain some of the special constructs or syntax features which is in fact a nice thing. Introduction and Appendix chapters provides basic information about the Spark core, RDDs (Resilient distributed datasets) or options of running Spark - whether in cluster (Mesos, YARN, Spark's own) or standalone settings. Throughout the book you can find some really worthy tips about Spark or data analysis - like using other serializer than the Java's default (they recommend kryo), overview of data cleansing and whole machine learning pipeline. To sum up, I recommend this book to every data scientist - because it demonstrates advanced topics like workload distribution and scaling on an enjoyable examples. 


