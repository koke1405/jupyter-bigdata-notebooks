# jupyter-bigdata

Jupyter environment for the [big data course][1].

When running this environment without access to SURFsara's HDFS you can download the required data files from the following locations: 

* [2008.csv.gz](http://beehub.nl/surfsara-hadoop/public/2008.csv.gz). Originals source: [http://stat-computing.org/dataexpo/2009/the-data.html](http://stat-computing.org/dataexpo/2009/the-data.html)
* [shakespeare.txt](http://beehub.nl/surfsara-hadoop/public/shakespeare.txt)
* [tweets.json](http://beehub.nl/surfsara-hadoop/public/tweets.json)

When running without access to HDFS, download the files above to your own computer and upload them to the notebook environment. The paths in the notebooks need to be changed to the new location and the kinit cells can be skipped. 

[1]: http://hpc.uva.nl/Workshops/article/107/8-Data-intensive-Computing-with-Spark-Hadoop
