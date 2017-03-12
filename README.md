# hadoop-streaming
Exercises and examples developed for the Hadoop with Python tutorial


DESCRIPTION

In this tutorial, students will learn how to use Python with Apache Hadoop to store, process, and analyze incredibly large data sets. Hadoop has become the standard in distributed data processing, but has mostly required Java in the past. Today, there are a numerous open source projects that support Hadoop in Python and this tutorial will show students how to use them.

Working with Hadoop using Python instead of Java is entirely possible with a conglomeration of active open source projects that provide Python APIs to Hadoop components. This tutorial will survey the most important projects and show that not only is Hadoop with Python possible, but that it also has some advantages over Hadoop with Java.

The reasons for using Hadoop with Python instead of Java are not all that different than the classic Java vs. Python arguments. One of the most important differences is not having to compile your code by instead using a scripting language. This makes more interactive development of analytics possible, makes maintaining and fixing applications in production environments simpler in many cases, makes for more succinct and easier to read code, and so much more. Also, by integrating Python with Hadoop, you get access to the world-class data analysis libraries such as numpy, scipy, nltk, and scikit-learn that are best-in-breed both inside of Python and outside.

Students will be surprised at how quickly they can get up and running with Hadoop when using Python. In this tutorial, we will talk about the following libraries and approaches and will guide students through a series of exercises:

* Interacting with files in the Hadoop Distributed File System with the snakebite Python module to store potentially petabytes of data
* Writing MapReduce jobs with the mrjob Python module to analyze large amounts of data over potentially thousands of nodes
* Writing MapReduce jobs with Apache Pig (a higher-level data flow language) in conjunction with Python user-defined functions

In addition to these topics, we'll briefly cover the state of Python support for other Hadoop ecosystem projects, such as HBase, Hive, Spark, Storm, Flume, Accumulo, and a few others.
