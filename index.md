# Riki Otaki
<div style="display: flex; align-items: center;">
  <div>
    <strong>PhD Student</strong><br>
    Computer Science Department, University of Chicago<br>
    rotaki [at] uchicago [dot] edu<br>
    John Crerar Library Building, 5730 South Ellis Avenue, Chicago IL 60637
  </div>
  <div style="margin-left: 30px;">
    <img src="profile.jpeg" alt="Riki Otaki" style="width: 150px; height: 150px; border-radius: 5px;" />
  </div>
</div>

---

I am currently a third-year Ph.D. student in Computer Science at the University of Chicago under the mentorship of Prof. [Aaron J. Elmore](https://people.cs.uchicago.edu/~aelmore). My research centers on database systems, with particular interests in developing resource-adaptive query execution engines tailored for cloud-native databases and enhancing the performance of disk-based storage systems to compete with in-memory systems. Additionally, I have a keen interest in query optimization, transaction processing, and indexing techniques. I am passionate about building efficient and scalable systems that can adapt to varying workloads and resource constraints.

Prior to my doctoral studies at UChicago, I completed my Bachelor's degree in Aerospace Engineering at the University of Tokyo.

## Publications

* **Riki Otaki**, Jun Hyuk Chang, Aaron J. Elmore, and Goetz Graefe

  Enhancing Transaction Processing through Indirection Skipping

  Under submission, 2025

* **Riki Otaki**, Jun Hyuk Chang, Charles Benello, Aaron J. Elmore, and Goetz Graefe

  [Resource-Adaptive Query Execution with Paged Memory Management](https://vldb.org/cidrdb/papers/2025/p2-otaki.pdf)

  Conference on Innovative Data Systems Research (**CIDR**), 2025

* Rui Liu, Jun Hyuk Chang, **Riki Otaki**, Zhe Heng Eng, Aaron J. Elmore, Michael J. Franklin, and Sanjay Krishnan

  [Towards Resource-adaptive Query Execution in Cloud Native Databases](https://www.cidrdb.org/cidr2024/papers/p34-liu.pdf)

  Conference on Innovative Data Systems Research (**CIDR**), 2024

## Recent Projects

* **Robust Pointer Swizzling techniques (2024-)**

  To bridge the performance gap between disk-based and in-memory database systems, I have focused on reducing inefficiencies in disk page retrieval. I developed Logical ID with Physical Address Hinting (LIPAH), a novel pointer-swizzling technique that enhances page access performance within the buffer pool manager. LIPAH is simpler and more robust than existing techniques, allowing for lazy updates of invalid pointers to new addresses. Currently, I am extending LIPAH to other components within the database system to further enhance performance.

* **Fine-grained Control of Query Execution for Resource-adaptive Databases (2022-)**
  
  Developing a resource-adaptive query engine in Rust designed to boost the performance of cloud-based databases. This project prioritizes the dynamic execution of queries under fluctuating resource capacities. Our current focus areas include the suspension and resumption of queries, adjusting resource allocations in run-time, and query re-optimizations. The ultimate goal is to enhance the control over query execution, ensuring more accurate and efficient use of resources.

* **Designing Journal Storage for Optuna, a Hyperparameter Optimization Library (2022)**
  
  Contributed to the development of a journal log storage system for Optuna, a highly-regarded hyperparameter optimization library. 
  This system enhances large-scale distributed optimization tasks by eliminating the need for centralized database management and ensuring efficient recovery during worker node failures. [Article](https://medium.com/optuna/distributed-optimization-via-nfs-using-optunas-new-operation-based-logging-storage-9815f9c3f932)

* **Benchmarking Concurrency Control Protocols for OLTP Workloads (2021)**
  
  Implemented and optimized various advanced concurrency control protocols (SILO, S2PL, MVTO) in C++, focusing on improving performance for OLTP workloads. Conducted detailed performance assessments under diverse operational scenarios using a comprehensive TPC-C benchmark suite to validate these improvements. [Repository](https://github.com/rotaki/tpcc-runner)

## Teaching

* TA 2024 Spring: CMCS 23500/33500 "Introduction to Database Systems"

## Education

* University of Chicago, Sep 2022 - Present

  PhD in Computer Science, Advisor: Prof. [Aaron Elmore](https://people.cs.uchicago.edu/~aelmore/)

* University of Tokyo, Mar 2017 - Mar 2022

  Bachelor in Aerospace Engineering, Advisor: Prof. [Takehisa Yairi](https://ailab.t.u-tokyo.ac.jp/en/)

* Uppsala University, Aug 2019 - Jun 2020

  Exchange Student

## Miscellaneous