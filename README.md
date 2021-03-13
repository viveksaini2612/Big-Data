# Big-Data



What is data? 


We know Data is collection of facts, numbers, words, measurements and observations or descriptions of things which is collected together for reference or analysis. Usually, data is different types of information that usually formatted in a particular manner. Data can be stored in papers in real life but inside electronic devices, it is stored as bits and bytes.  

                                     

How do we store data? 
To use or refer, we need to save and store the data and for that we need physical devices called Electronic Storage Media (Any electronic device that can be used to hold data temporarily or permanently). This includes but is not limited to internal and external hard drives, CDs, DVDs, Floppy Disks, USB drives, ZIP disks, magnetic tapes and SD cards.  


    

The largest storage device for most of the computers is Hard disk or SSD whose available capacity is 15TB.  As for an individual it might be sufficient but for industrial and marketing purposes or for storing huge data it is not sufficient as there exist a large data. 

Existence of Big data-  
Big Data is also data but with a huge size. Big Data is a term used to describe a collection of data that is huge in volume and yet growing exponentially with time. The data is too large to fit in main memory of any computer or any hard disk.  

The Newyork Stock Exchange generates about one terabyte of new trade data per day. 
No alt text provided for this image
The statistic shows that 500+terabytes of new data get ingested into the databases of social media site Facebook, every day. This data is mainly generated in terms of photo and video uploads, message exchanges, putting comments etc. 
No alt text provided for this image
A single Jet engine can generate 10+terabytes of data in 30 minutes of flight time. With many thousand flights per day, generation of data reaches up to many Petabytes. 
Almost all industries have their specific cases where they have big data management problems to solve. The data quality and validity vary from source to source, and thus are difficult to store as well as to process. This issue has led to the development of several stream processing engines/platforms by different companies such as Yahoo, LinkedIn, etc. 

By 2025, it’s estimated that 463 exabytes of data will be created each day globally – that’s the equivalent of 212,765,957 DVDs per day! 
As computers advance, the technologies used to store data do too, right along with higher requirements for storage space. Because people need more and more space, want it faster, cheaper, and want to take it with them, new technologies have to be invented.

Characteristics of Big data- 
1) VOLUME: VOLUME is one thing which we should consider while dealing with big data as the name itself related to size which is enormous. Infact, the size of data plays a major role while determining it as big data or not. 

2) VARIETY : VARIETY refers to the nature and source of data. Data may be of any type i.e. photo, video, text, audio, PDF etc. This variety of unstructured data possess certain issues for storage, mining and analyzing data. 

3) VELOCITY : VELOCITY refers to the speed of generation of data, how fast the data is generated and processed to meet the demands, determines real potential in the data. It deals with the speed at which data flows in from sources like networks, applications and business processes etc. 

4) VERACITY : VERACITY refers to inconsistencies and uncertainty in data, that is data which is available can sometimes get messy and quality and accuracy are difficult to control. It might result in inaccurate analysis and couldn’t convey information. 

5) VALUE : After having the 4 V’s into account there comes one more important V which stands for Value!                                                                                         The bulk of Data having no Value is of no good to the company, unless you turn it into something useful. Data in itself is of no use or importance but it needs to be converted into something valuable to extract Information. 

Hadoop- 
To eliminate the V’s from characteristics of big data, the way followed by many companies is Distributed file system. HDFS master slave topology is one of the methods implemented by Hadoop.  

Apache Hadoop is an open source, Java-based, software framework and parallel data processing engine. It enables big data analytics processing tasks to be broken down into smaller tasks that can be performed in parallel by using an algorithm (like the MapReduce algorithm), and distributing them across a Hadoop cluster. 

A Hadoop cluster is a collection of computers, known as nodes, that are networked together to perform these kinds of parallel computations on big data sets. Unlike other computer clusters, Hadoop clusters are designed specifically to store and analyze mass amounts of structured and unstructured data in a distributed computing environment. 


HDFs- 
HDFS has 2 daemons which run for storing data. 

Name Node: This is the daemon that runs on all the masters. Name node stores the metadata like filename, number of replicas, the number of blocks, block IDs and location of blocks, etc. This metadata in the master is used for faster retrieval of data. Name node memory should be high as per the requirement. 
Data Node: This is the daemon that runs on the slave. These are an actual worker node that stores the data. 
No alt text provided for this image
The Client contacts HDFS Master- Name Node to access the files in cluster. Data storage in HDFS is managed by number of HDFS Slave-Data Nodes. Slave-Data nodes are actually worker nodes which will do the assigned works by master node. 

Data Nodes can be deployed on commodity hardware and need not to be deployed on very reliable hardware since the data in the slave nodes are replicated in other data nodes. So in case of failure in one hardware data can be retrieved from other data nodes placed in different hardware. 

Advantages of Hadoop cluster-  
Hadoop clusters are easily scalable and can quickly add nodes to increase throughput, and maintain processing speed, when faced with increasing data blocks. 
The use of low cost, high availability commodity hardware makes Hadoop clusters relatively easy and inexpensive to set up and maintain. 
Hadoop clusters replicate a data set across the distributed file system, making them resilient to data loss and cluster failure. 
 

 
