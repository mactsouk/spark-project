    export SPARK_HOME="/spark"

```./spark/bin/spark-submit --class org.apache.spark.examples.SparkPi --master spark://spark:7077 $SPARK_HOME/examples/jars/spark-examples*.jar 100```

    $SPARK_HOME/bin/run-example SparkPi 100
