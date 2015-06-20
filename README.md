# PyData-London2015



Repo for the talk:
[Financial Risk Management: Analytics and Aggregation with the PyData stack](http://london.pydata.org/schedule/presentation/13/)




## Setup environment

I've create a conda environment. If you go to the repository's root directory.

    conda env create
    source activate pyldn
    pip install -r requirements.txt
    #if you want to use PostgreSQL
    conda install -c https://conda.binstar.org/anaconda psycopg2


## References

  1. for VaR Filtered Historical Simulation

    Giovani Barone-Adesi, Frederick Bourgoin and Kostas Giannopoulos (1998) “Don’t look back”, Risk, 11, August, pp100-104

    John Hull and Alan White, “Incorporate Volatility Updating into the Historical Simulation Method for Value-at-Risk”, Journal of Risk, 1998

  2. for Apache Spark

    [Estimating Financial Risk with Spark Sandy Ryza (Cloudera)](https://spark-summit.org/east-2015/talk/estimating-financial-risk-with-spark)

    [Embracing Spark as the Scalable Data Analytics Platform - Matthew Glickman - Goldman Sachs - Video](https://www.youtube.com/watch?v=9yiwhfmEfi0)

    [Fast Data Analytics with Spark and Python](http://www.slideshare.net/BenjaminBengfort/fast-data-analytics-with-spark-and-python)

    [Introducing DataFrames in Spark for Large Scale Data Science](http://www.slideshare.net/databricks/introducing-dataframes-in-spark-for-large-scale-data-science)
