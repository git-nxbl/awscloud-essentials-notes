## Module 1: Introduction to the Cloud

### What is Cloud Computing?

* **Definition**: Delivery of computing services (servers, storage, databases, networking) over the internet.
* **Types of Cloud**:

  * **Public Cloud**: Resources shared with other customers.
  * **Private Cloud**: Dedicated resources for a single organization.
  * **Hybrid Cloud**: Combination of both public and private.

### AWS Overview

* **AWS (Amazon Web Services)**: A cloud services platform providing compute power, storage, and databases.
* **Global Infrastructure**:

  * **Regions**: Geographical areas that host AWS data centers.
  * **Availability Zones (AZs)**: Multiple, isolated locations within each region for redundancy and high availability (typically 3+ AZs per region).

### AWS Shared Responsibility Model

* **AWS Responsibilities (Security *of* the Cloud)**:

  * Secures physical infrastructure (e.g., locks, access control).
  * Secures network layer and hypervisor (virtualization) layer.
* **Customer Responsibilities (Security *in* the Cloud)**:

  * Full control over the **Operating System** (OS):

    * Responsible for patching, securing, and managing OS.
    * AWS has no access or backdoor into customer systems.
  * **Applications**:

    * Customers are responsible for securing and managing their apps.
  * **Data**:

    * Customers control access, encryption, and privacy.
    * Data can be open, restricted, or encrypted based on use case.
* **Key Concept**: The **Shared Responsibility Model** defines the clear division of tasks between AWS and the customer, varying depending on the services used.
