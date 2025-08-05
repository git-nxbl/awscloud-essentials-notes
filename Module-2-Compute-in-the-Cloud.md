## Module 2: Compute in the Cloud

### Amazon EC2 Overview

* **Amazon EC2 (Elastic Compute Cloud)**: Provides scalable, resizable compute capacity in the cloud.
* **Benefits**:

  * More **flexible**, **cost-effective**, and **faster** than on-premises servers.
  * **On-demand** compute capacity — launch, scale, and terminate instances as needed.
  * Pay only for compute time used — **no upfront investment**.

### EC2 Flexibility & Use Cases

* Launch **as many or as few virtual servers** as needed.
* Configure **security, networking, and storage** for each instance.
* **Scale resources up or down** based on demand:

  * Handle traffic spikes.
  * Run compute-heavy tasks.
* Accelerates **development and deployment** of applications.

### EC2 Instance Types & Families

* **Instance Types**: Different configurations of CPU, memory, storage, and networking.
* Grouped into **Instance Families** to match various workload needs:

#### 1. General Purpose

* Balanced compute, memory, and networking.
* Ideal for:

  * Web servers
  * Code repositories
  * Versatile use cases where workload needs are unclear

#### 2. Compute Optimized

* High-performance CPU for **compute-intensive tasks**.
* Ideal for:

  * Gaming servers
  * Scientific modeling
  * Machine learning inference
  * High-performance computing (HPC)

#### 3. Memory Optimized

* High memory-to-vCPU ratio for **memory-intensive tasks**.
* Ideal for:

  * Large in-memory databases
  * Real-time big data analytics

#### 4. Accelerated Computing

* Use **hardware accelerators** (GPUs, FPGAs, etc.) for specialized tasks.
* Ideal for:

  * Graphics processing
  * Floating-point calculations
  * Pattern matching
  * Machine learning training

#### 5. Storage Optimized

* High, fast, local storage throughput.
* Ideal for:

  * Data warehousing
  * Distributed file systems
  * Heavy read/write access to local storage

---

### Interacting with AWS Services

#### APIs in AWS

* **Everything in AWS is an API call**.
* **API (Application Programming Interface)**: Defined way to interact with AWS services.
* Used to **provision**, **configure**, and **manage** cloud resources.

#### Methods to Call AWS APIs

##### 1. AWS Management Console

* **Web-based UI** to manage AWS services visually.
* Good for:

  * Beginners
  * Test environments
  * Billing and monitoring
* Limitations:

  * Manual, error-prone, not ideal for production.

##### 2. AWS CLI (Command Line Interface)

* **Text-based interface** to run AWS commands.
* Enables **scripting and automation**.
* Examples:

  * `aws ec2 run-instances` — Create EC2 instance
  * `aws ec2 describe-availability-zones` — List AZs
* Can be used in:

  * Local terminal
  * **AWS CloudShell** — Cloud-based terminal with CLI pre-installed

##### 3. AWS SDK (Software Development Kit)

* Use programming languages to interact with AWS (e.g., Python, Java).
* Enables integration in apps and scripts.
* Example:

  * Python script using **Boto3** to list EC2 instances

#### Key Concept

* Whether using the **Console**, **CLI**, or **SDK**, **AWS APIs are always being called** behind the scenes.

