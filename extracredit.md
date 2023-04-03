### Extra Credit Database: InfluxDB

InfluxDB is an open source database accessible through this website: https://www.influxdata.com/products/influxdb-overview/. It is a time-series database and its hosting models are cloud, local, and client/server. To access it through Java, you need to connect it using the Influx client and use the InfluxDBClientFactory Class's create() method to make the connection.

The **time series data model** is mainly used for time-stamped data and tracking change over time. It is different from other data models we've discussed as it's focused on time-stamped data, versus capturing more generic data or graphs/columns. For example, time series data models could be used to track events or measurements, monitoring data and events/clicks, etc. 

Sources:
https://www.influxdata.com/time-series-database/
https://www.influxdata.com/blog/getting-started-java-influxdb/#:~:text=Making%20a%20connection&text=In%20a%20Java%20application%2C%20use,in%20with%20your%20user%20ID.
https://www.influxdata.com/products/influxdb-overview/