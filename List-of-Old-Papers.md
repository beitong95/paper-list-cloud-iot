Armbrust, Michael, et al. "A view of cloud computing." Communications of the ACM 53.4 (2010): 50-58.
Cattell, Rick. "Scalable SQL and NoSQL data stores." ACM SIGMOD Record 39.4 (2011): 12-27.
Barham, Paul, et al. "Xen and the art of virtualization." ACM SIGOPS Operating Systems Review 37.5 (2003): 164-177.
Ghemawat, Sanjay, Howard Gobioff, and Shun-Tak Leung. "The Google file system." ACM SIGOPS operating systems review. Vol. 37. No. 5. ACM, 2003.
Shvachko, Konstantin, et al. "The hadoop distributed file system." Mass Storage Systems and Technologies (MSST), 2010 IEEE 26th Symposium on. IEEE, 2010.
Dean, Jeffrey, and Sanjay Ghemawat. "MapReduce: simplified data processing on large clusters." Communications of the ACM 51.1 (2008): 107-113.
Chang, Fay, et al. "Bigtable: A distributed storage system for structured data." ACM Transactions on Computer Systems (TOCS) 26.2 (2008): 4.
DeCandia, Giuseppe, et al. "Dynamo: amazon's highly available key-value store." ACM SIGOPS Operating Systems Review. Vol. 41. No. 6. ACM, 2007.
Corbett, James C., et al. "Spanner: Google’s globally distributed database." ACM Transactions on Computer Systems (TOCS) 31.3 (2013): 8.
Wolski, Hiranya Jayathilaka Chandra Krintz Rich. "Response Time Service Level Agreements for Cloud-hosted Web Applications."
Hindman, Benjamin, et al. "Mesos: A Platform for Fine-Grained Resource Sharing in the Data Center." NSDI. Vol. 11. 2011.
Verma, Abhishek, et al. "Large-scale cluster management at Google with Borg." Proceedings of the Tenth European Conference on Computer Systems. ACM, 2015.
Calder, Brad, et al. "Windows Azure Storage: a highly available cloud storage service with strong consistency." Proceedings of the Twenty-Third ACM Symposium on Operating Systems Principles. ACM, 2011.
Beaver, Doug, et al. "Finding a Needle in Haystack: Facebook's Photo Storage." OSDI. Vol. 10. 2010.
Malewicz, Grzegorz, et al. "Pregel: a system for large-scale graph processing." Proceedings of the 2010 ACM SIGMOD International Conference on Management of data. ACM, 2010.
Lakshman, Avinash, and Prashant Malik. "Cassandra: a decentralized structured storage system." ACM SIGOPS Operating Systems Review 44.2 (2010): 35-40.
Zaharia, Matei, et al. "Spark: cluster computing with working sets." Proceedings of the 2nd USENIX conference on Hot topics in cloud computing. Vol. 10. 2010.
Vavilapalli, Vinod Kumar, et al. "Apache hadoop yarn: Yet another resource negotiator." Proceedings of the 4th annual Symposium on Cloud Computing. ACM, 2013.
Xin, Reynold S., et al. "Shark: SQL and rich analytics at scale." Proceedings of the 2013 ACM SIGMOD International Conference on Management of data. ACM, 2013.
Toshniwal, Ankit, et al. "Storm@ twitter." Proceedings of the 2014 ACM SIGMOD international conference on Management of data. ACM, 2014.
Boykin, Oscar, et al. "Summingbird: A framework for integrating batch and online mapreduce computations." Proceedings of the VLDB Endowment 7.13 (2014): 1441-1451. 


 
1. Virtualization 
Stephen Soltesz, Herbert Pötzl, Marc E. Fiuczynski, Andy Bavier, Larry Peterson, “Container-based Operating System Virtualization: A Scalable, High-performance Alternative to Hypervisors,” Eurosys 2007. 
it would be useful if students read another type of virtualization like containers. 
 2. MapReduce itself 
Andrew Pavlo, Erik Paulson, Alexander Rasin, Daniel J. Abadi, David J. DeWitt, Samuel Madden, Michael Stonebraker, “A Comparison of Approaches to Large-Scale Data Analysis,” SIGMOD ‘09
Michael Stonebraker, Daniel Abadi, David J. DeWitt, Sam Madden, Erik Paulson, Andrew Pavlo, and Alexander Rasin, “MapReduce and Parallel DBMSs: Friends or Foes?,” Communications of ACM, 2010
I think students should read claims and complains from other side like Parallel DBMS community.
 3. Hadoop eco-systems
Patrick Hunt, Mahadev Konar, Flavio P. Junqueira, Benjamin Reed, “ZooKeeper: Wait-free coordination for Internet-scale systems,” USENIX ATC 10
Ashish Thusoo et al, “Hive - A Petabyte Scale Data Warehouse Using Hadoop,” ICDE 2010
Christopher Olston, Benjamin Reed, Utkarsh Srivastava, Ravi Kumar, Andrew Tomkins. “Pig Latin: A Not-So-Foreign Language for Data Processing,” SIGMOD 2008
These are add-on functionality on top of Hadoop.
Azza Abouzeid , Kamil Bajda-Pawlikowski,  “HadoopDB: an architectural hybrid of MapReduce and DBMS technologies for analytical workloads, VLDB Endowment 2009
This is how to collaborate Hadoop (mapreduce) with existing DBMS.
Bikas Saha et al, Apache Tez: A Unifying Framework for Modeling and Building Data Processing Applications, SIGMOD 2015
Complex DAG WF engine on Hadoop
4. Cloud Data Storage
Jason Baker et al, “Megastore: Providing Scalable, Highly Available Storage for Interactive Services,” CIDR 11
Megastore tried to take both scalability from NoSQL and consistency from RDBMS -- this is in the middle between both systems.
Sage A. Weil et al, “Ceph: A Scalable, High-Performance Distributed File System,” – OSDI 06
Ceph is a good example of "transition from academic research to open source project"
Daniel Ford, “Availability in Globally Distributed Storage Systems,” OSDI 10
This contains google's deep considerations on failure and availability of their infrastructure and this might be good one after reading GFS paper.
 5. Resource Management for Big Data Analytics Systems.
M. Schwarzkopf, A. Konwinski, M. Abd-El-Malek, and J. Wilkes, "Omega: flexible, scalable schedulers for large compute clusters" Eurosys 2013
This is google's resource manager like Yarn and Mesos.
Markus Weimer et al, REEF: Retainable Evaluator Execution Framework, SIGMOD 2015
resource manager for graph computation and machine learning and it is also Apache incubating open-source project. Note that there exist two versions of REEF paper. SIGMOD 2015 version contains more sufficient information than VLDB 2013 version.
 6. Spark ecosystem
Michael Armbrus et al, Spark SQL: Relational Data Processing in Spark, SIGMOD 2015.
SQL-like programming API for Spark.
7. Stream Processing
Sanjeev Kulkarni et al, Twitter Heron: Stream Processing at Scale, SIGMOD 2015
This is a replacement for Storm@Twitter, providing better scalability, performance, debug-environments, and manageability. Also, this paper provides direct comparison with Storm.