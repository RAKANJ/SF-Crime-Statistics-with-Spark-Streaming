# SF-Crime-Statistics-with-Spark-Streaming
Part of Streaming Processing Course.

Step 3
Write the answers to these questions in the README.md doc of your GitHub repo:

How did changing values on the SparkSession property parameters affect the throughput and latency of the data?
    -affect how many rows are processed per second.

What were the 2-3 most efficient SparkSession property key/value pairs? Through testing multiple variations on values, how can you tell these were the most optimal?
    -spark.default.parallelism
    -spark.streaming.kafka.maxRatePerPartition
    -spark.sql.shuffle.partitions
