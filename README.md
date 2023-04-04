# Testing-Documentation


Performance Testing:-
The goals of performance testing include evaluating application output, processing speed, data transfer velocity, network bandwidth usage, maximum concurrent users, memory utilization, workload efficiency, and command response times.
Types of Performance Testing:
1.	Capacity Testing.
2.	Load Testing.
3.	Volume Testing.
4.	Stress Testing.
5.	Soak Testing.


1. Capacity Testing:
Capacity Testing ensures that the application and environment can smoothly handle the maximum number of users or transactions according to the performance requirements defined in your Service-Level Agreement (SLA).
Capacity Testing is aimed at testing the maximum capacity of your system in terms of traffic, while still being able to deliver optimal user experience.
Examples: Homepage load times, webpage response times, transaction durations (e.g., – account login, search, and payment times)

2. Load Testing:
⦁	The load testing is done by changing the user loads for the resources and verifying the performance of the resources.
⦁	The primary focus of this testing is on ‘users’.
⦁	The server is stressed to the maximum limit.
⦁	A simple example can be creating a large number of files.
Locust is a Python-based testing tool used for load testing and user behavior simulation
 It supports running multiple load tests over a distributed system, therefore it can be used to simulate millions of users. Locust also provides a nice graphical user interface for viewing data metrics about our API performance.

3.Volume Testing:
⦁	The volume testing is done to verify the database performance against a large volume of data in the DB.
⦁	The primary focus of this testing is on ‘data’.
⦁	The database is stressed to the maximum limit.
⦁	A simple example can be creating a huge sized file.
Volume Testing is a type of non-functional testing. This testing is done to check the data volume handled by the database. Volume testing also called flood testing is non-functional testing that is done to check the software or app for its performance against huge data of the database.
The database is stretched to a threshold point by adding a large amount of data to it and then the system is tested for its response.
1.	Check for the correctness of the data storage methods.
2.	Check if the system has the necessary memory resources or not.
3.	Check if there’s any risk of data volume greater than a specified limit.
4.	Check and observe the system’s response to the data volume.
5.	Check if the data is getting lost during volume testing.
6.	Check that if data is overwritten, then it is done so with prior information.
7.	Identify the areas that extend beyond the normal range like a lot of attributes (searchable), huge no. of lookup tables, a lot of location mappings, etc.
8.	As mentioned earlier, create a baseline first by getting results for the normal volume and then move ahead with stressing.

4.Stress Testing:
 Stress testing is also known as Endurance Testing or Torture Testing. 
Stress testing is particularly important for critical software but is used for all types of software. Stress testing emphasizes robustness, availability, and error handling under a heavy load rather than what is correct behavior under normal situations.
 Stress testing is defined as a type of software testing that verifies the stability and reliability of the system. 
This test particularly determines the system on its robustness and error handling under extremely heavy load conditions
. It even tests beyond the normal operating point and analyses how the system works under extreme conditions. 
Stress testing is performed to ensure that the system would not crash under crunch situations.
Types of Stress Testing:-
⦁	Server-client Stress Testing: In this stress testing, testing is carried out across all clients from the server.
⦁	Product Stress Testing: Product stress testing concentrates on discovering defects related to data locking and blocking, network issues, and performance congestion in a software product.
⦁	Transaction Stress Testing: Transaction stress testing is performed on one or more transactions between two or more applications. It is carried out for fine-tuning and optimizing the system.
⦁	Systematic Stress Testing: Systematic stress testing is integrated testing that is used to perform tests across multiple systems running on the same server. It is used to discover defects where one application data blocks another application.
⦁	Analytical Stress Testing: Analytical stress testing is performed to test the system with abnormal parameters or conditions that are unlikely to happen in a real scenario. It is carried out to find defects in unusual scenarios like a large number of users logged at the same time or a database going offline when it is accessed from a website.

5. Soak Testing:
It is also known as a type of Load Testing.
Soak testing (otherwise known as endurance testing, capacity testing, or longevity testing) involves testing the system to detect performance-related issues such as stability and response time by requesting the designed load on a system.
Soak testing is mainly used to identify and optimize potential problems, such as memory leaks, resource leaks, or degradation that could happen over time, to avoid impaired performance or system errors. While stress tests will help the development team to test the system to its limits, soak testing takes the system to its limits over a sustained period of use.
