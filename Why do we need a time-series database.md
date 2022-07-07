# Why do we need a time-series database?

Time series databases have been steadily growing in popularity and have been [outpacing all other database models by a wide margin over the past two years](https://db-engines.com/en/ranking_categories).

## What is a time series database?

With a time series database (TSDB), it's possible to add, process, and track massive quantities of [time series data](https://aiven.io/blog/time-series-or-event-data-get-less-confused). They do this efficiently and continuously, with lightning speed and precision. Other types of databases also work for these workloads, and have indeed been used in the past, TSDBs haven specific algorithms and architecture to meet the requirements of speed and high volumes.

A time series database stores data as pairs of time(s) and value(s). Storing data this way makes it easy to analyze sequences of points recorded in order over time. A TSDB can handle concurrent series, measuring many different variables or metrics in parallel.

Early time series databases were mostly used for processing volatile financial data and streamlining securities trading. The world’s changed a lot since they were first introduced, and many new use cases have emerged as technology has continued to evolve.

For example, the Internet of Things (IoT) concept employs sensors that constantly collect and stream data. IoT technology is used for multiple purposes, from powering industrial applications to predicting sales demand, from weather monitoring to wearable fitness devices. The amount of data they produce is staggering.

Well, it can be staggering for more traditional databases, which were designed for different purposes. Luckily, there are time series databases, and they are getting better and better at dealing with the growing demand of this data type.

## What are the benefits of a time series database?

There’s a reason more and more developers and organizations are using time series databases. They deliver a number of benefits, which we’ll now briefly explore.

### 1. More accurate and meaningful time series measurement

A time series database makes it easy to measure how datasets change over time. You can concurrently view past, present, and future datasets for reporting that is more accurate and meaningful.

### 2. Resource-efficient data storage

By the very nature of the data type, processing it can require massive amounts of storage, which can be difficult to manage. It's also very expensive. Time series databases have tooling to aggregate data into predetermined time periods and to eliminate any data streams as needed. There are also compression algorithms that optimize data storage.

### 3. Lightning-fast data queries

A TSDB can also make it easy to query and retrieve data based on specific periods. Imagine that you can't remember the title of a book you recently read, but you know it was three months ago. Time series databases can help you figure out what the book was without having to use a bunch of wildcard searches.

Using a time series database, you can quickly find information based on timeframe.

## Common time series database use cases

### 1. Store and access IoT data

Most IoT deployments — like connected water, energy, and temperature meters — involve constant data collection and reporting at regular intervals. Time series analysis can provide timestamped data points for identifying patterns, average usage, and inefficiencies.

For example, a connected pH meter connected to a TSDB might tell a technician tasked with maintaining a specific pH level that a certain vat of water is becoming too acidic. IoT endpoints also collect massive amounts of data, requiring highly scalable time series databases.

### 2. Monitor web services, applications and infrastructure

TSDBs can [measure the performance of a company's applications and services](https://aiven.io/blog/metrics-and-graphs-with-m3-and-grafana). For example, the open source monitoring system [Prometheus](https://aiven.io/blog/5-1-reasons-to-extend-your-prometheus-with-m3) is a time series database that enables developers to keep tabs on performance trends over time. This enables them to easily detect when problems are occuring, which then allows them to plan maintenance and rapidly respond to incidents to sustain an optimal user experience.

Some web and mobile applications store the events within their app in a TSDB (such as a button click, playing a video or sharing some content). With this data they can map a user’s journey, identify frustrations or performance bottlenecks and enhance the user experience.

### 3. Understand financial trends

Using time series data to accurately predict financial trends is very difficult. However, a TSDB can provide a wealth of contextual data to help analysts. Let’s take the stock market as an example; a sudden increase in airline stock may coincide with holiday travel. Or an executive leadership purge may spook investors, causing a stock to temporarily tumble. Time series databases make it easy to cross-reference data, providing a richer, clearer picture.

### 4. Process self-driving vehicle data

Self-driving cars typically collect about [4,000 GB](https://www.information-age.com/tconnected-car-data-explosion-123473363) of data per day. This is beyond the scope of what a typical relational database can process. Time series databases ingest data and queries faster, and compress data more strongly.

As a result, they are ideal for processing massive volumes of real-time data that can be used to improve the safety of self-driving vehicles.

### 5. Sales forecasting

Retail stores must continuously predict future sales based on past ones, so that they can restock appropriately. Thanks to time series databases, retailers can use statistical models combined with historical data. Cross-referenced with consumer behavior trends, they can predict future patterns and make informed decisions about which products to keep in stock and when.

For instance, retailers are now using forecasting to plan ahead and restock bicycles, which are now experiencing a shortage due to the pandemic. Retailers are using data to predict when new products will become available again, what the demand will be like, and what alternative transportation options consumers are buying in lieu of bicycles e.g., trikes, rollerblades, etc.
