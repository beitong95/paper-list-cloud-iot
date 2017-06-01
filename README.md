Cloud and Big Data/Stream Analytics
-----------------------------------

`Spark vs. MapReduce -- who's the winner?`
* Clash of the Titans: MapReduce vs. Spark for Large Scale Data Analytics, VLDB 2015

`Resource Management for Big Data Framework` – Executing big data framework on transient instances (aka spot) – same idea, different approaches.
Yan et al, SoCC'16, TR-Spark: Transient Computing for Big Data Analytics, (paper)
Yang et al, Eurosys'17, Pado: A Data Processing Engine for Harnessing Transient Resources in Datacenters, (paper)
Harlap et al, Eurosys 2017, Proteus: agile ML elasticity through tiered reliability in dynamic resource markets(paper)

`Resource Management` – figure out the best cloud configurations for analytics.
NSDI 17 -- CherryPick: Adaptively Unearthing the Best Cloud Configurations for Big Data Analytics

`Newbies`
SoCC 2016 -- ReStream: Accelerating Backtesting and Stream Replay with Serial-Equivalent Parallel Processing
SoCC 2016 -- STYX: Stream Processing with Trustworthy Cloud-based Execution
StreamScope: Continuous Reliable Distributed Processing of Big Data Streams, NSDI 2016

Cloud IoT
`What it is and where it goes`
The Cloud is Not Enough: Saving IoT from the Cloud, HotCloud 2015
Integration of Cloud computing and Internet of Things: A Survey, Future Generation Computer Systems 2016.
Enabling the Internet of Things, IEEE Computer, 2015
Internet of Things (IoT): A Vision, Architectural Elements, and Future Directions, Future Generation Computer Systems 2013

`Cloud IoT – Infrastructure`
Beam: Ending Monolithic Applications for Connected Devices, In ATC 2016

`Cloud IoT – Applications #1`
Where's The Bear?- Automating Wildlife Image Processing Using IoT and Edge Cloud Systems, IoTDI 2017
Experiences Creating a Framework for Smart Traffic Control using AWS IOT, UCC 2016
The Data Furnace: Heating Up with Cloud Computing, HotCloud 2011

`Indoor/Outdoor Air Quality Sensing with Clouds`
AirCloud: A Cloud-based Air-Quality Monitoring System for Everyone, Sensys 2014
AirSense: An Intelligent Home-based Sensing System for Indoor Air Quality Analytics, Ubicomp 2016

`The famous Cloudlet Applications`
Towards Wearable Cognitive Assistance, Mobisys 2014
Just-in-time Provisioning for Cyber Foraging, Mobisys 2013


Fog/Edge Computing
`Its definition, vision, and challenges`
Finding your Way in the Fog: Towards a Comprehensive Definition of Fog Computing, ACM Sigcomm CCR 2014
Fog Computing: Principles, Architectures, and Applications, arXiv, https://arxiv.org/abs/1601.02752
Fog computing and its role in the internet of things, MCC 2012
The Emergence of Edge Computing, IEEE Computer, 2017
Edge-centric Computing: Vision and Challenges, ACM Sigcomm CCR 2015
Edge Computing: Vision and Challenges -- IEEE Transactions on Internet of Things, 2016

`Creating Edge Infrastructure`
Towards Deploying Decommissioned Mobile Devices as Cheap Energy-Efficient Compute Nodes, HotCloud 2017

Mobile Cloud
`A Survey Paper`
Mobile cloud computing: A Survey, Future Generation Computer Systems 2013

`Simplified development for mobile/cloud apps`
Customizable and Extensible Deployment for Mobile/Cloud Applications, OSDI 2014

`Augmented execution of mobile applications on the clouds`
CloneCloud: Elastic Execution between Mobile Device and Cloud, Eurosys 2011

Cloud Functions

`Open Source version of Lambda`
Serverless Computation with OpenLambda, In HotCloud 2016
`General-purpose parallel computation on Cloud Function and its application`
Fouladi et al, Encoding, Fast and Slow: Low-Latency Video Processing Using Thousands of Tiny Threads, NSDI 2017
`This is the PyWren paper – not officially published yet.`
Occupy the Cloud: Distributed Computing for the 99%, arXiv 2017
http://pywren.io/
`System Infrastructure for Cloud Function`
Picocenter: Supporting long-lived, mostly-idle applications in cloud environments, In Eurosys 2016.
`These are not a research paper, but worthwhile to read`
The Economics of Microservices, IEEE Cloud Computing, 2016
Be Wary of the Economics of `Serverless` Cloud Computing, IEEE Cloud Computing 2017

Cloud + Machine Learning, AI, and more.

`TensorFlow – this is super hot now.`
OSDI 16 -- TensorFlow: A system for large-scale machine learning, (paper), (slide), and (google tech report)

`Elastic Resourec Management for Large Scale Machine Learning`
SIGMOD 2015 -- Resource Elasticity for Large-Scale Machine Learning

`ML Infrastructure at Industry`
Large-Scale Machine Learning at Twitter, SIGMOD 2012

`Deep Neural Net Cluster`
Watcharapichat et al, Ako: Decentralised Deep Learning with Partial Gradient Exchange, In SoCC 2016

`Cloud + ML (DNN) + Edge Computing`
Kang et al, Neurosurgeon: Collaborative Intelligence Between the Cloud and Mobile Edge, In ASPLOS 2016

`Cloud + Voice + GPU + FPGA`
Sirius Implications for Future Warehouse-Scale Computers, IEEE Micro Top Pics, 2016

`Deep Learning as a Service`
DjiNN and Tonic: DNN as a Service and Its Implications for Future Warehouse Scale Computers, In ISCA 2015

`Large Scale Video Analytics`
Optasia: A Relational Platform for Efficient Large-Scale Video Analytics, In SoCC 2016


Cloud + GPU/FPGA
`GPU resource management`
Heterogeneous GPU reallocation, HotCloud 2017

`Memcached on GPU`
MemcachedGPU: Scaling-up Scale-out Key-value Stores, SoCC 2015

`Cloud GPU Processing for Game Servers`
dJay : Enabling High-density Multi-tenancy for Cloud Gaming Servers with Dynamic Cost-Benefit GPU Load Balancing, SoCC 2015

`Cloud + Deep Learning + GPU`
GeePS: Scalable Deep Learning on Distributed GPUs with a GPU-specialized Parameter Server, Eurosys 2016

`Spark meets GPU lol!`
SWAT: A Programmable, In-Memory, Distributed, High-Performance Computing Platform, HPDC 2016
`Spark meets FPGA lol!`
When Apache Spark Meets FPGAs: A Case Study for Next-Generation DNA Sequencing Acceleration, HotCloud 2016

`Deploying FPGA accelerators in data centers`
Programming and Runtime Support to Blaze FPGA Accelerator Deployment at Datacenter Scale, SoCC 2016

"GPU Result Reuse"
Supporting Dynamic GPU Computing Result Reuse in the Cloud, HotCloud 2015

"GPU processing from a local cluster to clouds"
Parallel patterns for heterogeneous CPU/GPU architectures: Structured parallelism from cluster to cloud, Future Generation Computer Systems, 2014
