# Getting started
1. Download and extract Spark: [download](https://spark.apache.org/downloads.html)
2. Add to your `.bashrc`
    ```sh
    # This is where you extracted Spark
    export SPARK_HOME="$HOME/spark/spark-2.4.6-bin-hadoop2.7/"
    export PATH=$SPARK_HOME/bin:$PATH
    export PYTHONPATH=$SPARK_HOME/python/:$PYTHONPATH
    ```
3. Install pyspark
    ```sh
    pip install pyspark
    ```
4. Start notebook server:
    ```sh
    jupyter notebook
    ```
