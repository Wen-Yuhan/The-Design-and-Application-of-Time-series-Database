# Why do we need a time-series database?

Time-series databases have been steadily growing in popularity and have greatly surpassed all other database models in the past two years. 

Why do we need a time-series database? And why it is getting more and more popular these days? In this article, I’ll try to take a deeper look at time-series databases. 

### What is time series data?

Time-series data is a series of data points indexed/listed in time order, and is used to describe how a phenomenon changes over time. This type of data reflects the state or extent to which something has changed over time. 

For example, the change of China's GDP from 1949 to 2009 is the time series data. Time series data can be subdivided into quarterly data and monthly data, among which the quarterly time series model is representative, because its data has the same change rule as the four seasons. Although the change cycle is not the same, the overall change trend changes according to the cycle. 

We are now living in an era of information explosion. Every person produces countless information every day. At the 2021 China Mobile Global Partner Conference, Liang Hua, chairman of Huawei, said that in today's era, each of the world's 7 billion people generates up to 1.5GB of data per day. You have to remember that in 1992, the whole world produced only 100GB of data a day. 

While the amount of information is increasing, the types of information are also increasing rapidly: with the development of the Internet, many new industries came into being, such as artificial intelligence, Internet of things, unmanned driving, etc. Besides, some traditional industries like financial industry and electric power industry, are also seeking for transformation, thus the concept of "Internet Plus" is in the ascendant. Therefore, all kinds of data are generated, which traditional databases can not handle perfectly.

In this case, the traditional database seems to be inadequate, and time-series database came into being.

### What is a time series database?

Time Series Database is used for ingesting, processing, and storing time series data. 

While other databaxxses can handle time series data to some extent when the data size is small, TSDB can handle the ingestion, compression, and aggregation of time-series data more effectively.

A time-series database is a computer system that is designed to store and retrieve data records that are part of a “time series,” which is a set of data points that are associated with timestamps.  The timestamps provide a critical context for each of the data points in how they are related to others.  Time series data is often a continuous flow of data like measurements from sensors and intraday stock prices.  A time-series database lets you store large volumes of timestamped data in a format that allows fast insertion and fast retrieval to support complex analysis on that data.

In short, a time-series database is a database specifically designed to store and process time series data, supporting efficient reading and writing, highly compressed storage, interpolation, and aggregation of time series data.

With a time series database (TSDB), it's possible to add, process, and track massive quantities of time series data. They do this efficiently and continuously, with lightning speed and precision. Other types of databases also work for these workloads, and have indeed been used in the past, TSDBs haven specific algorithms and architecture to meet the requirements of speed and high volumes.

A time series database stores data as pairs of time(s) and value(s). Storing data this way makes it easy to analyze sequences of points recorded in order over time. A TSDB can handle concurrent series, measuring many different variables or metrics in parallel.

Early time series databases were mostly used for processing volatile financial data and streamlining securities trading. The world’s changed a lot since they were first introduced, and many new use cases have emerged as technology has continued to evolve.

For example, the Internet of Things (IoT) concept employs sensors that constantly collect and stream data. IoT technology is used for multiple purposes, from powering industrial applications to predicting sales demand, from weather monitoring to wearable fitness devices. The amount of data they produce is staggering.

Well, it can be staggering for more traditional databases, which were designed for different purposes. Luckily, there are time series databases, and they are getting better and better at dealing with the growing demand of this data type.

### What are the benefits of a time series database?

There’s a reason more and more developers and organizations are using time series databases. They deliver a number of benefits, which we’ll now briefly explore.

#### More accurate and meaningful time series measurement

A time series database makes it easy to measure how datasets change over time. You can concurrently view past, present, and future datasets for reporting that is more accurate and meaningful.

#### Resource-efficient data storage

By the very nature of the data type, processing it can require massive amounts of storage, which can be difficult to manage. It's also very expensive. Time series databases have tooling to aggregate data into predetermined time periods and to eliminate any data streams as needed. There are also compression algorithms that optimize data storage.

#### Lightning-fast data queries

A TSDB can also make it easy to query and retrieve data based on specific periods. Imagine that you can't remember the title of a book you recently read, but you know it was three months ago. Time series databases can help you figure out what the book was without having to use a bunch of wildcard characters.

### What can time-series database do?

#### Store and access IoT data

Most IoT deployments — like connected water, energy, and temperature meters — involve constant data collection and reporting at regular intervals. Time series analysis can provide timestamped data points for identifying patterns, average usage, and inefficiencies.

For example, a connected pH meter connected to a TSDB might tell a technician tasked with maintaining a specific pH level that a certain vat of water is becoming too acidic. IoT endpoints also collect massive amounts of data, requiring highly scalable time series databases.

#### Monitor web services, applications and infrastructure

TSDBs can measure the performance of a company's applications and services. For example, the open source monitoring system Prometheus is a time series database that enables developers to keep tabs on performance trends over time. This enables them to easily detect when problems are occuring, which then allows them to plan maintenance and rapidly respond to incidents to sustain an optimal user experience.

Some web and mobile applications store the events within their app in a TSDB (such as a button click, playing a video or sharing some content). With this data they can map a user’s journey, identify frustrations or performance bottlenecks and enhance the user experience.

#### Understand financial trends

Using time series data to accurately predict financial trends is very difficult. However, a TSDB can provide a wealth of contextual data to help analysts. Let’s take the stock market as an example; a sudden increase in airline stock may coincide with holiday travel. Or an executive leadership purge may spook investors, causing a stock to temporarily tumble. Time series databases make it easy to cross-reference data, providing a richer, clearer picture.

#### Process self-driving vehicle data

Self-driving cars typically collect about 4000 GB of data per day. This is beyond the scope of what a typical relational database can process. Time series databases ingest data and queries faster, and compress data more strongly.

As a result, they are ideal for processing massive volumes of real-time data that can be used to improve the safety of self-driving vehicles.

#### Sales forecasting

Retail stores must continuously predict future sales based on past ones, so that they can restock appropriately. Thanks to time series databases, retailers can use statistical models combined with historical data. Cross-referenced with consumer behavior trends, they can predict future patterns and make informed decisions about which products to keep in stock and when.

For instance, retailers are now using forecasting to plan ahead and restock bicycles, which are now experiencing a shortage due to the pandemic. Retailers are using data to predict when new products will become available again, what the demand will be like, and what alternative transportation options consumers are buying in lieu of bicycles e.g., trikes, rollerblades, etc.

### The development trend of time series database

The chart below shows trend of the last 24 months about DBMS according to DB-engines. We can find that the time-series database has been the most active and increasing over time.

![image-20220707171143945](https://github.com/Wen-Yuhan/The-Design-and-Application-of-Time-series-Database/blob/main/images/image-20220707171143945.png)

And here is a list of time-series databases compiled by DB-Engines. The highest-ranked chronological database is InfluxDB, while TDengine created by TAOS Data ranks 13.

![image-20220707171841637](https://github.com/Wen-Yuhan/The-Design-and-Application-of-Time-series-Database/blob/main/images/image-20220707171841637.png)

### Summary

Time-series database is a new concept, that is being explored by many companies. Although here are more and more use cases for time series databases, we’re just getting started when it comes to realizing their full promise.

At present, there isn't a database that dominates the time-series database market. Considering time-series database has broad development prospects, there are a lot of business opportunities waiting for elites with ability, wisdom and courage to seize.

### Reference

+ https://aiven.io/blog/an-introduction-to-time-series-databases
+ https://new.qq.com/omn/20211104/20211104A03ZQW00.html
+ https://zhuanlan.zhihu.com/p/350041920
