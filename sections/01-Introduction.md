
Introduction
============

## Contents

- [What is this Cookbook](01-Introduction.md#what-is-this-cookbook)
- [Data Engineer vs Data Scientist](01-Introduction.md#data-engineer-vs-data-scientist)
  - [Data Engineer](01-Introduction.md#data-engineer)
  - [Data Scientist](01-Introduction.md#data-scientist)
  - [Machine Learning Workflow](01-Introduction.md#machine-learning-workflow)
  - [Machine Learning Model and Data](01-Introduction.md#machine-learning-model-and-data)
- [My Data Science Platform Blueprint](01-Introduction.md#my-data-science-platform-blueprint)
  - [Connect](01-Introduction.md#connect)
  - [Buffer](01-Introduction.md#buffer)
  - [Processing Framework](01-Introduction.md#processing-framework)
  - [Store](01-Introduction.md#store)
  - [Visualize](01-Introduction.md#visualize)
- [Who Companies Need](01-Introduction.md#who-companies-need)

## What is this Cookbook

I get asked a lot:
"What do you actually need to learn to become an awesome data engineer?"

Well, look no further. You'll find it here!

If you are looking for AI algorithms and such data scientist things,
this book is not for you.

**How to use this Cookbook:**
This book is intended to be a starting point for you. It is not a training! I want to help you to identify the topics to look into to become an awesome data engineer in the process.

It hinges on my Data Science Platform Blueprint. Check it out below. Once you understand it, you can find in the book tools that fit into each key area of a Data Science platform (Connect, Buffer, Processing Framework, Store, Visualize).

Select a few tools you are interested in, then research and work with them.

Don't learn everything in this book! Focus.

**What types of content are in this book?**
You are going to find five types of content in this book: Articles
I wrote, links to my podcast episodes (video & audio), more than 200
links to helpful websites I like, data engineering interview questions
and case studies.

**This book is a work in progress!**
As you can see, this book is not finished. I'm constantly adding new
stuff and doing videos for the topics. But, obviously, because I do this
as a hobby, my time is limited. You can help make this book even
better.

**Help make this book awesome!**
If you have some cool links or topics for the cookbook, please become a
contributor on GitHub: <https://github.com/andkret/Cookbook>. Fork the
repo, add them, and create a pull request. Or join the discussion by
opening Issues. Tell me your thoughts, what you value,
what you think should be included, or correct me where I am wrong.
You can also write me an email any time to
plumbersofdatascience\@gmail.com anytime.

**This Cookbook is and will always be free!**
I don't want to sell you this book, but please support what you like and
join my Patreon: <https://www.patreon.com/plumbersofds>.
Or send me a message and support through PayPal: <https://paypal.me/feedthestream>

Check out this podcast episode where I talk in detail why I decided to
share all this information for free: [\#079 Trying to stay true to
myself and making the cookbook public on
GitHub](https://youtu.be/k1bS5aSPos8)



## If You Like This Book & Need More Help:
Check out my Data Engineering Academy and personal Coaching at LearnDataEngineering.com

**Visit learndataengineering.com:** [Click Here](https://learndataengineering.com)

- New content every week!
- Step by step course, from researching job postings to creating and doing your project, to job application tips.
- Full AWS Data Engineering example project (Azure in development).
- 1+ hours Ultimate Introduction to Data Engineering course.
- Data Engineering Fundamentals course.
- Data Platform & Pipeline Design course.
- Apache Spark Fundamentals course.
- Choosing Data Stores Course.
- Private Member Slack Workspace (lifetime access).
- Weekly Q&A live stream & Archive.
- Currently over 24 hours of videos.


## Support This Book For Free!
- **Amazon:** [Click Here](https://www.amazon.com/shop/plumbersofdatascience) buy whatever you like from Amazon using this link* (Also check out my complete podcast gear and books)


## How To Contribute
If you have some cool links or topics for the cookbook, please become a contributor.

Simply pull the repo, add your ideas and create a pull request.
You can also open an issue and put your thoughts there.

Please use the "Issues" function for comments.



Data Engineer vs Data Scientist
-------------------------------


| Podcast Episode: #050 Data Engineer, Scientist or Analyst - Which One Is For You?
|-----------------------------------------------------------------------------------
| In this podcast we talk about the diﬀerences between data scientists, analysts and engineers. Which are the three main data science jobs. All three are super important. This makes it easy to decide
| [Watch on YouTube](https://youtu.be/64TYZETOEdQ) \ [Listen on Anchor](https://anchor.fm/andreaskayy/episodes/050-Data-Engineer-Scientist-or-Analyst-Which-One-Is-For-You-e45ibl)


### Data Engineer

Data Engineers are the link between the management's data strategy
and the data scientists who need to work with data.

What they do is build the platforms that enable data scientists to do
their magic.

These platforms are usually used in five different ways:

-   Data ingestion and storage of large amounts of data.

-   Algorithm creation by data scientists.

-   Automation of the data scientist's machine learning models and
    algorithms for production use.

-   Data visualization for employees and customers.

-   Most of the time these guys start as traditional solution architects
    for systems that involve SQL databases, web servers, SAP
    installations and other "standard" systems.

But, to create big data platforms, the engineer needs to be an expert in
specifying, setting up, and maintaining big data technologies like:
Hadoop, Spark, HBase, Cassandra, MongoDB, Kafka, Redis, and more.

What they also need is experience on how to deploy systems on cloud
infrastructure like at Amazon or Google, or on-premise hardware.


| Podcast Episode: #048 From Wannabe Data Scientist To Engineer My Journey
|------------------|
|In this episode Kate Strachnyi interviews me for her humans of data science podcast. We talk about how I found out that I am more into the engineering part of data science.  
| [Watch on YouTube](https://youtu.be/pIZkTuN5AMM) \ [Listen on Anchor](https://anchor.fm/andreaskayy/episodes/048-From-Wannabe-Data-Scientist-To-Engineer-My-Journey-e45i2o)|

### Data Scientist

Data scientists aren't like every other scientist.

Data scientists do not wear white coats or work in high-tech labs full
of science fiction movie equipment. They work in offices just like you
and me.

What differs them from most of us is that they are math experts. They
use linear algebra and multivariable calculus to create new insight from
existing data.

How exactly does this insight look?

Here's an example:

An industrial company produces a lot of products that need to be tested
before shipping.

Usually such tests take a lot of time because there are hundreds of
things to be tested -- all to make sure that your product is not broken.

Wouldn't it be great to know early if a test fails ten steps down the
line? if you knew that you could skip the other tests and just trash the
product or repair it?

That's exactly where a data scientist can help you, big time. This field
is called predictive analytics, and the technique of choice is machine
learning.

Machine what? Learning?

Yes, machine learning, it works like this:

You feed an algorithm with measurement data. It generates a model and
optimises it based on the data you fed it. That model basically
represents a pattern of how your data looks. You show that model
new data, and the model will tell you if the data still represents the
data you have trained it with. This technique can also be used for
predicting machine failure in advance with machine learning. Of course,
the whole process is not that simple.

The actual process of training and applying a model is not that hard. A
lot of work for the data scientist is to figure out how to pre-process
the data that gets fed to the algorithms.

In order to train an algorithm, you need useful data. If you use just any data
for the training the produced model will be very unreliable.

An unreliable model for predicting machine failure would tell you that
your machine is damaged even if it is not. Or even worse: It would tell
you the machine is ok even when there is a malfunction.

Model outputs are very abstract. You also need to post-process the model
outputs to receive the outputs you desire

![The Machine Learning Pipeline](/images/Machine-Learning-Pipeline.jpg)


### Machine Learning Workflow

![The Machine Learning Workflow](/images/Machine-Learning-Workflow.jpg)

Data Scientists and Data Engineers. How does that all fit together?

You have to look at the data science process, how stuff is created and how data
science is done. How machine learning is
done.

The machine learning process shows that you start with a training phase, a phase where you basically train the algorithms to create the right output.

In the learning phase, you have the input parameters (basically the configuration of the model), and you have the input data.

What you do is train the algorithm. While training the algorithm modifies the training
parameters, it also modifies the used data. Then you get an output.

Once you get an output, you evaluate. Is that output okay, or is that output not the desired output?

If the output is not what you were looking for, then you continue with the training phase.

You may retrain the model hundreds, thousands, hundred thousands of times. Of course, all this is being done automatically.

Once you are satisfied with the output, you put the model into production. In production, it is no longer fed with training
data; it's fed with the live data.

It evaluates the input data live and puts out live results.

So, you went from training to production, and then what?

What you do is monitor the output. If the output keeps making sense, all good!

If the output of the model changes and it's on longer what you have expected, it means the model doesn't work anymore.

You need to trigger model retraining.

Once you are again satisfied with the output, you put it into production again. It replaces the one in production.

This is the overall process of machine learning. It's how the learning part of data science works.


### Machine Learning Model and Data

![The Machine Learning Model](/images/Machine-Learning-Model.jpg)

Now, that's all very nice.

When you look at it, you have two very important places where you have data.

You have in the training phase two types of data:
data that you use for the training; data that basically configures the model, the hyperparameter configuration.

Once you're in production, you have the live data streaming in, data from from an app, from
a IoT device, logs, or whatever.

A data catalog is also important. It explains which features are available and how different data sets are labeled.

These are all different types of data. Now, here comes the engineering part.

The Data Engineer's part is making this data available, available to the data scientist and the machine learning process.

So, when you look at the model, on the left side you have your hyperparameter configuration. You need to store and manage these configurations somehow.

Then you have the actual training data.

There's a lot going on with the training data.

Where does it come from? Who owns it? Which is basically data governance.

What's the lineage? Have you modified this data? What did you do? What was the basis, the raw data?

You need to access all this data somehow, in training and in production.

In production, you need to have access to the live data.

All this is the data engineer's job. Making the data available.

First, an architect needs to build the platform. This can also be a good data engineer.

Then, the data engineer needs to build the pipelines. How is the data coming in, and how does the platform
connect to other systems.

How is that data then put into the storage? Is pre-processing for the algorithms necessary? The data engineer will do it.

Once the data and the systems are available, it's time for the machine learning part.

It is ready for processing, for the data scientist.

Once the analytics is done, the data engineer needs to build pipelines to make it then accessible again, for instance for other analytics processes, for APIs, for front ends, and so on.

All in all, the data engineer's part is a computer science part.

That's why I love it so much. :)


## My Data Science Platform Blueprint

I have created a simple and modular big data platform
blueprint. It is based on what I have seen in the field and
read in tech blogs all over the internet.

Why do I believe it will be super useful to you?

Because, unlike other blueprints, it is not focused on technology.

Following my blueprint will allow you to create the big data platform
that fits exactly your needs. Building the perfect platform will allow
data scientists to discover new insights.

It will enable you to perfectly handle big data and allow you to make
data-driven decisions.

The blueprint is focused on the five key areas: Connect, Buffer, Processing Frameworks, Store, and Visualize.

![Data Science Platform Blueprint](/images/Data-Science-Blueprint-New.jpg)

Having the platform split like this turns it into a modular platform with
loosely coupled interfaces.

Why is it so important to have a modular platform?

If you have a platform that is not modular, you end up with something
that is fixed or hard to modify. This means you can not adjust the
platform to changing requirements of the company.

Because of modularity, it is possible to specifically select tools for your use case. It also allows you to replace every component, if you need it.

Now, lets talk more about each key area.

### Connect

Ingestion is all about getting the data in from the source and making it
available to later stages. Sources can be everything from tweets to server
logs, to IoT sensor data (e.g. from cars).

Sources send data to your API Services. The API is going to push the
data into temporary storage.

The temporary storage allows other stages simple and fast access to
incoming data.

A great solution is to use messaging queue systems like Apache Kafka,
RabbitMQ or AWS Kinesis. Sometimes people also use caches for
specialised applications like Redis.

A good practice is that the temporary storage follows the
publish-subscribe pattern. This way APIs can publish messages and
Analytics can quickly consume them.

### Buffer

In the buffer phase you have pub/sub systems like Apache Kafka, Redis, or other Cloud tools like Google pub/sub or AWS Kinesis.

These systems are more or less message Queues.
You put something in on one side and take it out on the other.

The idea behind buffers is to have an intermediate system for the incoming data.

How this works is, for instance, you're getting data in from from an API.
The API is publishing into the message queue. Data is buffered there until it is picked up by the processing.

If you don't have a buffer, you can run into problems when writing directly into a store or you're processing the data directly. You can always have peaks of incoming data that stall the systems.

Like, it's lunch break and people are working with your app way more than usual.
There's more data coming in very very fast, faster than the analytics of the storage can handle.

In this case, you would run into problems, because the whole system would stall. It would therefore take long to process the data, and your customers would be annoyed.

With a buffer, you buffer the incoming data. Processes for storage and analytics can take out only as much data as they can process. You are no longer in danger of overpowering systems.

Buffers are also really good for building pipelines.

You take data out of Kafka, pre-process it, and put it back into Kafka.
Then, with another analytics process, you take the processed data back out and put it into a store.

Ta-da! A pipeline.

### Processing Framework

The analyse stage is where the actual analytics is done in
the form of stream and batch processing.

Streaming data is taken from ingest and fed into analytics. Streaming
analyses the "live" data, thus generating fast results.

As the central and most important stage, analytics also has access to
the big data storage. Because of that connection, analytics can take a
big chunk of data and analyse it.

This type of analysis is called batch processing. It will deliver you
answers for the big questions.

For a short video about batch and stream processing and their use cases, click on the link below:

[Adding Batch to a Streaming Pipeline](https://www.youtube.com/watch?v=o-aGi3FmdfU)

The analytics process, batch or streaming, is not a one-way process.
Analytics can also write data back to the big data storage.

Oftentimes, writing data back to the storage makes sense. It allows you
to combine previous analytics outputs with the raw data.

Analytics give insights when you combine
raw data. This combination will often allow you to create even more
useful insights.

A wide variety of analytics tools are available. Ranging from MapReduce
or AWS Elastic MapReduce to Apache Spark and AWS lambda.

### Store

This is the typical big-data storage where you just store everything. It
enables you to analyse the big picture.

Most of the data might seem useless for now, but it is of utmost
importance to keep it. Throwing data away is a big no-no.

Why not throw something away when it is useless?

Although it seems useless for now, data scientists can work with the
data. They might find new ways to analyse the data and generate valuable
insights from it.

What kind of systems can be used to store big data?

Systems like Hadoop HDFS, Hbase, Amazon S3 or DynamoDB are a perfect fit
to store big data.

Check out my podcast how to decide between SQL and NoSQL:
<https://anchor.fm/andreaskayy/embed/episodes/NoSQL-Vs-SQL-How-To-Choose-e12f1o>

### Visualize

Displaying data is as important as ingesting, storing, and analysing it.
Visualizations enable business users to make data-driven decisions.

This is why it is important to have a good visual presentation of the
data. Sometimes you have a lot of different use cases or projects using
the platform.

It might not be possible to build the perfect UI that fits
everyone's needs. What you should do in this case is enable others to build the
perfect UI themselves.

How to do that? By creating APIs to access the data and making them
available to developers.

Either way, UI or API, the trick is to give the display stage direct
access to the data in the big-data cluster. This kind of access will
allow the developers to use analytics results as well as raw data to
build the perfect application.


## Who Companies Need

For a company, it is important to have well-trained data
engineers and data scientists. Think of the data scientist as a
professional race car driver. A fit athlete with talent and driving
skills like you have never seen before.

What he needs to win races is someone who will provide him the perfect
race car to drive. It is the data engineer/solution architect who will design and build the race car.

Like the driver and the race car engineer, the data scientist and the data engineer need to work closely together. They need to know the different big-data tools inside out.

That's why companies are looking for people with Spark experience. Spark is the common ground between the data engineer and the data scientist that drives innovation.

Spark gives data scientists the tools to do analytics and helps
engineers to bring the data scientist's algorithms into production.
After all, those two decide how good the data platform is, how good the
analytics insight is, and how fast the whole system gets into a
production-ready state.
