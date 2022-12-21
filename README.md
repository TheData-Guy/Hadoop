# Hadoop

![](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0e/Hadoop_logo.svg/1280px-Hadoop_logo.svg.png)


## What is Hadoop ?

Hadoop is the solution to above Big Data problems. It is the technology to store massive datasets on a cluster of cheap machines in a distributed manner. Not only this it provides Big Data analytics through distributed computing framework.

It is an open-source software developed as a project by Apache Software Foundation. Doug Cutting created Hadoop. In the year 2008 Yahoo gave Hadoop to Apache Software Foundation. Since then two versions of Hadoop has come. Version 1.0 in the year 2011 and version 2.0.6 in the year 2013. 


## Why Hadoop is Important ?

In today’s fast-paced world we hear a term – Big Data. Nowadays various companies collect data posted online. This unstructured data found on websites like Facebook, Instagram, emails etc comprise Big Data. Big Data demands a cost-effective, innovative solution to store and analyze it. Hadoop is the answer to all Big Data requirements. So, let’s explore why Hadoop is so important. 

### Managing Big Data 
- As we are living in the digital era there is a data explosion. The data is getting generated at a very high speed and high volume. So there is an increasing need to manage this Big Data. As we can see from the below chart chart that the volume of unstructured data is increasing exponentially. Therefore in order to manage this ever-increasing volume of data, we require Big Data technologies like Hadoop.
 
 
     ![](https://www.datanami.com/wp-content/uploads/2022/01/DataSphere.png)
 
### Exponential Growth of Big Data Market 
- The Big Data Market size was valued at USD 162.6 billion in 2021 and is projected to grow 273.4 USD billion by 2026, at a Compound Annual Growth Rate (CAGR) of 11.0% during the forecast period.
    
     ![](https://www.marketsandmarkets.com/Images/big-data-market.jpg)
     
As the market for Big Data grows there will be a rising need for Big Data technologies. Hadoop forms the base of many big data technologies. The new technologies like Apache Spark and Flink work well over Hadoop. As it is an in-demand big data technology, there is a need to master Hadoop. As the requirements for Hadoop professionals are increasing, this makes it a must to learn technology.


###  Robust Hadoop Ecosystem
- Hadoop has a very robust and rich ecosystem which serves a wide variety of organizations. Organizations like web start-ups, telecom, financial and so on are needing Hadoop to answer their business needs.

     ![](https://www.oreilly.com/api/v2/epubs/9781788995092/files/assets/a64fec28-e2b2-42f0-96cf-098fe8385316.png)
     
### Research Tool
- Hadoop has come up as a powerful research tool. It allows an organization to find answers to their business questions. Hadoop helps them in research and development work. Companies use it to perform the analysis. They use this analysis to develop a rapport with the customer.Applying Big Data techniques improve operational effectiveness and efficiencies of generating great revenue in business. It brings a better understanding of the business value and develops business growth. Communication and distribution of information between different companies are feasible via big data analytics and IT techniques. 

### Ease of Use 
- Creators of Hadoop have written it in Java, which has the biggest developer community. Therefore, it is easy to adapt by programmers. You can have the flexibility of programming in other languages too like C, C++, Python, Perl, Ruby etc. If you are familiar with SQL, it is easy to use HIVE. If you are ok with scripting then PIG is for you. 

Hadoop framework handles all the parallel processing of the data at the back-end. We need not worry about the complexities of distributed processing while coding. We just need to write the driver program, mapper and reducer function. Hadoop framework takes care of how the data gets stored and processed in a distributed manner. After Spark Processing Framework it becomes More Eaiser.

### Hadoop is Presend Everywhere
- There is no industry where Big Data has not reached. Big Data has covered almost all domains like healthcare, retail, government, banking, media, transportation, natural resources and so on.

   ![](https://1.bp.blogspot.com/-Wu1iCYTv-U4/Xj2uAFpLw0I/AAAAAAAADow/1JErQq1K7og2wZYDxIDr_cLtfXsgaTE9QCLcBGAsYHQ/s1600/Applications-of-big-data-in-real-life.jpg)


### A Maturing Technolog 

- Hadoop is evolving with time. The new version of Hadoop i.e. Hadoop 3.0 is coming into the market. It has already collaborated with HortonWorks, Tableau, MapR, and even BI experts to name a few. New actors like Spark, Flink etc. are coming on the Big Data stage. These technologies promise the lightening speed of processing. These technologies also provide a single platform for various kinds of workloads. It is compatible with these new players. It provides robust data storage over which we can deploy technologies like Spark and Flink.

- The advent of Spark has enhanced the Hadoop ecosystem. The coming of Spark in the market has enriched the processing capability of Hadoop. Spark creators have designed it to work with Hadoop’s distributed storage system HDFS. It can also work over HBase and Amazon’s S3. Even if you work on Hadoop 1.x you can take advantage of Spark’s capabilities.

### Hadoop has a Better Career Scope 

- Hadoop excels in processing a wide variety of data. We have various components of Hadoop ecosystem providing batch processing, stream processing, machine learning, Big Data Analytics and so on. Learning it will open gates to a variety of job roles like:

 * Big Data Migration Engineer.
 * Big Data Backend Developer.
 * Database Engineer.
 * Big Data Architect.
 * Hadoop Developer
 * Cloud Data Engineer.


## Features Of Hadoop That Made It The Most Popular :

- Hadoop is Open Source. 
  * Hadoop is an open-source project, which means its source code is available free of cost for inspection, modification, and analyses that allows enterprises to modify the code as per their requirements.

- Hadoop cluster is Highly Scalable.
  * Hadoop cluster is scalable means we can add any number of nodes (horizontal scalable) or increase the hardware capacity of nodes (vertical scalable) to achieve high computation power. This provides horizontal as well as vertical scalability to the Hadoop framework.
 
 - **Hadoop provides Fault Tolerance**.
    * Fault tolerance is the most important feature of Hadoop. HDFS in Hadoop 2 uses a replication mechanism to provide fault tolerance.

- Hadoop provides High Availability.
  * This feature of Hadoop ensures the high availability of the data, even in unfavorable conditions. Due to the fault tolerance feature of Hadoop, if any of the DataNodes goes down, the data is available to the user from different DataNodes containing a copy of the same data.

- Hadoop is Faster in Data Processing.
  * Hadoop stores data in a distributed fashion, which allows data to be processed distributedly on a cluster of nodes. Thus it provides lightning-fast processing capability to the Hadoop framework.

- Hadoop is based on Data Locality concept.
  * Hadoop is popularly known for its data locality feature means moving computation logic to the data, rather than moving data to the computation logic. This features of Hadoop reduces the bandwidth utilization in a system.

## Hadoop Core Components 
 - Hadoop has Three Major Core Components :
   *  Hadoop Distributed File System(HDFS).
   *  MapReduce.
   *  Yarn 


## Hadoop Distributed File System(HDFS)

- Hadoop Distributed File system – HDFS is the world’s most reliable storage system. HDFS is a Filesystem of Hadoop designed for storing very large files running on a cluster of commodity hardware. It is designed on the principle of storage of less number of large files rather than the huge number of small files.

- Hadoop HDFS provides a fault-tolerant storage layer for Hadoop and its other components. HDFS Replication of data helps us to attain this feature. It stores data reliably, even in the case of hardware failure. It provides high throughput access to application data by providing the data access in parallel.

 ### HDFS Core Components :
 
 #### 1. NameNode 
 - NameNode is the centerpiece of the Hadoop Distributed File System. It maintains and manages the file system namespace and provides the right access permission to the clients.It is also Known as Master Node.
 - The NameNode stores information about blocks locations, permissions, etc. on the local disk in the form of two files:
   *  Fsimage: Fsimage stands for File System image. It contains the complete namespace of the Hadoop file system since the NameNode creation.
   * Edit log: It contains all the recent changes performed to the file system namespace to the most recent Fsimage. 
 
 #### Functions of HDFS NameNode
 - It executes the file system namespace operations like opening, renaming, and closing files and directories.
 - NameNode manages and maintains the DataNodes.
 - It determines the mapping of blocks of a file to DataNodes.
 - NameNode records each change made to the file system namespace.
 - It keeps the locations of each block of a file.
 - NameNode takes care of the replication factor of all the blocks.
 - NameNode receives heartbeat and block reports from all DataNodes that ensure DataNode is alive.
 - If the DataNode fails, the NameNode chooses new DataNodes for new replicas.

 #### 2.DataNode
 - DataNodes are the slave nodes in Hadoop HDFS. DataNodes are inexpensive commodity hardware. They store blocks of a file.
 - DataNode is responsible for serving the client read/write requests.
 - Based on the instruction from the NameNode, DataNodes performs block creation, replication, and deletion.
 - DataNodes send a heartbeat to NameNode to report the health of HDFS.
 - DataNodes also sends block reports to NameNode to report the list of blocks it contains.
 
###  What is Secondary NameNode?

-  Secondary NameNode works as a helper node to primary NameNode but doesn’t replace primary NameNode.
-  When the NameNode starts, the NameNode merges the Fsimage and edit logs file to restore the current file system namespace. Since the NameNode runs continuously for a long time without any restart, the size of edit logs becomes too large. This will result in a long restart time for NameNode.
-  Secondary NameNode downloads the Fsimage file and edit logs file from NameNode.
-  It periodically applies edit logs to Fsimage and refreshes the edit logs. The updated Fsimage is then sent to the NameNode so that NameNode doesn’t have to re-apply the edit log records during its restart. This keeps the edit log size small and reduces the NameNode restart time.

- If the NameNode fails, the last save Fsimage on the secondary NameNode can be used to recover file system metadata. The secondary NameNode performs regular checkpoints in HDFS.


### What are Blocks in HDFS Architecture?
 
  ![](https://media.geeksforgeeks.org/wp-content/uploads/20200618125555/3164-1.png)

- Internally, HDFS split the file into block-sized chunks called a block. The size of the block is 128 Mb by default. One can configure the block size as per the requirement.

- For example, if there is a file of size 400 Mb, then HDFS will create Three blocks of size 128 Mb and one block of size 16 Mb.

### What is Replication Management?
 - For a distributed system, the data must be redundant to multiple places so that if one machine fails, the data is accessible from other machines.

- In Hadoop, HDFS stores replicas of a block on multiple DataNodes based on the replication factor.

- The replication factor is the number of copies to be created for blocks of a file in HDFS architecture.

- If the replication factor is 3, then three copies of a block get stored on different DataNodes. So if one DataNode containing the data block fails, then the block is accessible from the other DataNode containing a replica of the block.

## MapReduce

- MapReduce is the processing layer of Hadoop. MapReduce programming model is designed for processing large volumes of data in parallel by dividing the work into a set of independent tasks. 

### How does MapReduce works ?

- MapReduce is a programming paradigm or model used to process large datasets with a parallel distributed algorithm on a cluster . In Big Data Analytics, MapReduce plays a crucial role. When it is combined with HDFS we can use MapReduce to handle Big Data.

- The basic unit of information used by MapReduce is a key-value pair. All the data whether structured or unstructured needs to be translated to the key-value pair before it is passed through the MapReduce model.

- MapReduce model as the name suggests has two different functions; Map-function and Reduce-function. The order of operation is always Map|Shuffle|Reduce.

   ![](https://k21academy.com/wp-content/uploads/2021/10/Presentation1.jpg)


 ####  Map stage 
 - Map stage is the crucial step in the MapReduce framework. Mapper will give a structure to the unstructured data. For example, if I have to count the songs and music files in my laptop as per genre in my playlist, I will have to analyze the unstructured data. The mapper makes key-value pairs from this dataset. So, in this case, the key is genre and value is the music file. Once all this data is given to the mapper, we have a whole dataset ready with the key-value pair structure.

- So the mapper will work on one key-value pair at a time. One input may produce any number of outputs. Basically, Map-function will process the data and make several small chunks of data.

#### Reducer Stage :
 
- The Shuffle stage and the Reduce stage together are called the Reduce stage. Reducer will take the output from the mapper as an input and make the final output as specified by the programmer. This new output will be saved to the HDFS. The Reducer will take all the key-value pairs from the mapper and check the association of all keys with value. All the values associated with a single key will be taken and it will provide an output of any number of key-value pairs.
- By understanding the Map and Reduce stages, we understand that MapReduce is a sequential computation. For any Reducer to work, the Mapper must have completed the execution. If that is not the case, the Reducer stage won’t run. Since, the Reducer will have access to all the values, we can say that it will find all values with the same key and perform computations on them. So what actually happens is, since reducers are working on different keys, they are made to work simultaneously and parallelism is achieved.


## Yet Another Resource Negotiator (Yarn)
- Apache Yarn – “Yet Another Resource Negotiator” is the resource management layer of Hadoop. The Yarn was introduced in Hadoop 2.x.

- Yarn allows different data processing engines like graph processing, interactive processing, stream processing as well as batch processing to run and process data stored in HDFS (Hadoop Distributed File System). Apart from resource management, Yarn also does job Scheduling.

- Yarn extends the power of Hadoop to other evolving technologies, so they can take the advantages of HDFS (most reliable and popular storage system on the planet) and economic cluster. To learn installation of Apache Hadoop 2 with Yarn follows this quick installation guide.

- Apache yarn is also a data operating system for Hadoop 2.x. This architecture of Hadoop 2.x provides a general purpose data processing platform which is not just limited to the MapReduce.

- It enables Hadoop to process other purpose-built data processing system other than MapReduce. It allows running several different frameworks on the same hardware where Hadoop is deployed.

### Yarn Architecture

  ![](https://www.edureka.co/blog/wp-content/uploads/2018/06/Components-of-YARN-1.png)
 
 #### Resource Manager
 
  - It is the master daemon of Yarn. Resource Manager manages the global assignments of resources (CPU and memory) among all the applications. It arbitrates system resources between competing applications.

 #### Node Manager 
 
 - It is the slave daemon of Yarn. NM is responsible for containers monitoring their resource usage and reporting the same to the ResourceManager. Manage the user process on that machine. Yarn NodeManager also tracks the health of the node on which it is running. The design also allows plugging long-running auxiliary services to the NM; these are application-specific services, specified as part of the configurations and loaded by the NM during startup.

#### Application Master 

- One application master runs per application. It negotiates resources from the resource manager and works with the node manager. It Manages the application life cycle.
