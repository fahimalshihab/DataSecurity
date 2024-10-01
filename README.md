![image](https://github.com/user-attachments/assets/ab24cbf1-189a-4238-bd54-f76712eacf71)

# What Is Data Security ?
<b>Data security is the process of safeguarding digital information throughout its entire life cycle to protect it from corruption, theft, or unauthorized access..</b> It covers everything—hardware, software, storage devices, and user devices; access and administrative controls; and organizations’ policies and procedures.

## Why is data security important?
Data security is not only important for your own business’s sake, but it’s also a legal requirement. The Data Protection Act 2018 states that businesses have a legal obligation to ensure that personal data is kept secure and protected against unauthorised access. This act also outlines how long you can legally hold personal information and what purposes you can use it for.


![image](https://github.com/user-attachments/assets/2930c9dc-5c6c-4a7c-a72f-9ac590c8e4a6)


<b>The image shows the annual number of data compromises and individuals impacted in the United States from 2005 to 2023.</b>






So, as a business, your HR department is legally responsible for the safety of the data you store related to your employees. Without a data security plan in place, it would be impossible for your business to comply with the law.

By implementing data security measures, organizations can:

* **Protect Sensitive Information:** Safeguard personal, financial, and confidential data from unauthorized access or theft.
* **Prevent Data Tampering:** Ensure data integrity and prevent unauthorized modifications.
* **Protect the Company's Reputation:** Maintain customer trust and avoid negative publicity associated with data breaches.
* **Ensure Legal and Regulatory Compliance:** Adhere to data privacy laws and regulations.
* **Maintain Customer Trust and Confidence:** Build strong relationships with customers by demonstrating a commitment to data protection.
* **Gain a Competitive Advantage:** Differentiate your business from competitors by prioritizing data security.
* **Avoid Additional Costs:** Prevent costly data breaches and the associated expenses of recovery and remediation.

### Key Elements of Data Security

The CIA triad (Confidentiality, Integrity, and Availability) are the three fundamental principles of data security:

* **Confidentiality:** Ensure that only authorized individuals can access sensitive data.
* **Integrity:** Protect data from unauthorized modifications or corruption.
* **Availability:** Ensure that data is accessible when needed and not disrupted by outages or attacks.




# Data Security Technologies:

### **Encryption**
* **How it works:** Encrypts data using algorithms to make it unreadable.
* **Purpose:** Prevents unauthorized access to sensitive data, even if it's breached.
* **Key points:** Requires encryption keys for decryption, ensures data confidentiality.

### **Authentication**
* **How it works:** Verifies user identity through credentials (e.g., usernames, passwords).
* **Purpose:** Restricts access to authorized individuals.
* **Key points:** Includes multi-factor authentication and breached password detection for enhanced security.

### **Data Masking**
* **How it works:** Replaces sensitive data with dummy values.
* **Purpose:** Protects sensitive information from unauthorized exposure during development or testing.
* **Key points:** Allows for application development using real data without compromising security.

### **Tokenization**
* **How it works:** Replaces sensitive data with random tokens.
* **Purpose:** Provides an additional layer of security by separating sensitive data from its original form.
* **Key points:** Similar to encryption but with a focus on token replacement.

### **Data Erasure**
* **How it works:** Permanently deletes data from storage devices.
* **Purpose:** Ensures data is not recoverable after it's no longer needed.
* **Key points:** Prevents data breaches and complies with data retention regulations.

### **Data Resilience**
* **How it works:** Implements measures to recover from data loss or corruption.
* **Purpose:** Ensures business continuity and data availability in the face of incidents.
* **Key points:** Includes backups, disaster recovery plans, and redundancy.

### **Physical Access Controls**
* **How it works:** Restricts physical access to data storage facilities.
* **Purpose:** Prevents unauthorized physical access to data.
* **Key points:** Uses security personnel, key cards, biometric authentication, and other physical security measures.

By effectively combining these technologies, organizations can create a robust data security framework that protects their valuable assets from various threats.

## Data Base
From all this, we can clearly see the immense importance of data. But how does it actually work?

**What is a database?**
A database is a collection of information that is stored digitally in a computer, on a server, or in the cloud. Databases can be very simple or quite complicated, depending on the structure and organization of the data. The database system is typically composed of the information itself and a database management system (DBMS), allowing users to easily access, update, analyze, and manage the information

According to DB-Engines’ latest ranking, the most popular DBMSes today include: 

- Oracle
- MySQL
- Microsoft SQL Server
- PostgreSQL
- MongoDB
- Redis
- IBM Db2
- Elasticsearch
- SQLite
- Microsoft Access

**Databases can be classified into two primary types:**



<b>Relational</b> and <b>NoSQL Databases</b>. NoSQL is then further divided into four types: Document-oriented, Key-Value, Wide-Column, and Graph databases.


![image](https://github.com/user-attachments/assets/0f7ea61d-6c2c-4844-a17d-b425874349d0)


# Relational Databases (also known as SQL Databases)

## Overview

A relational database (RDB) is a method of organizing data into tables, rows, and columns to show relationships between data points. This structure makes it straightforward to access, create, read, modify, and delete data using a querying language—such as SQL.

## Structure

Each table, also known as a relation, has rows (records) and columns (fields), where each row represents an entity, and each column represents an attribute of that entity.

## Relationships

You can establish relationships between entities through primary and foreign keys by guaranteeing data integrity and enabling complex queries.

## Strengths of Relational Databases

* The structured, table-like schema is easy to understand.
* Follow ACID (Atomicity, Consistency, Isolation, Durability) properties which makes them reliable.
* SQL language is standardized, widely used, and applicable to a variety of database management systems.

## Weaknesses of Relational Databases

* Can be difficult to scale out on multiple servers (horizontal scaling).
* Each table requires a predefined schema which means all data inserted into the table must follow the same structure. This is not optimal when dealing with complex data structures.



# NoSQL Databases

## Overview

NoSQL databases were developed as an alternative to traditional SQL databases, especially useful when working with large or fast-moving data that may not fit neatly into a table.

## Characteristics

NoSQL databases use various data models for accessing and managing data, optimized for applications needing flexible data models, handling large volumes of data, and achieving low latency. They accomplish this by relaxing some of the data consistency restrictions found in relational databases, making them ideal for dynamic, high-performance applications that require scalability and speed.

## Data Models

Instead of tables, NoSQL databases use more flexible data models, such as:

* Key-value pairs
* Documents
* Graphs

## Strengths of NoSQL Databases

* **Flexible and scalable**: Ideal for handling large amounts of unstructured or semi-structured data.
* **Highly scalable and fault-tolerant**: Scale horizontally across multiple servers.
* **Well-suited for use cases**: Such as social media, e-commerce, and big data analytics.

## Weaknesses of NoSQL Databases

* **Lack of standardized query language**: Each type of NoSQL database has its own method for querying data, making these systems more challenging to learn, integrate, and communicate with.
* **Not well-suited for complex transactions or querying relationships between data**.


# SQL VS NOSQL
![image](https://github.com/user-attachments/assets/2bdc071b-b456-4a95-8a41-f88c00a27fae)



# Database Security: Common Threats and Challenges

## Overview

Many software misconfigurations, vulnerabilities, or patterns of carelessness or misuse can result in breaches. The following are among the most common types or causes of database security attacks.

## Common Database Security Threats

### Insider Threats

An insider threat is a security threat from any one of three sources with privileged access to the database:

* A malicious insider who intends to do harm.
* A negligent insider who makes errors that make the database vulnerable to attack.
* An infiltrator, an outsider who somehow obtains credentials via a scheme, such as phishing or by gaining access to the credential database itself.

### Human Error

Accidents, weak passwords, password sharing, and other unwise or uninformed user behaviors continue to be the cause of nearly half (49%) of all reported data breaches.

### Exploitation of Database Software Vulnerabilities

Hackers make their living by finding and targeting vulnerabilities in all kinds of software, including database management software. All major commercial database software vendors and open source database management platforms issue regular security patches to address these vulnerabilities, but failure to apply these patches in a timely fashion can increase your exposure.

### SQL or NoSQL Injection Attacks

A database-specific threat, these involve the insertion of arbitrary SQL or non-SQL attack strings into database queries that are served by web applications or HTTP headers. Organizations that don’t follow secure web application coding practices and perform regular vulnerability testing are open to these attacks.

### Buffer Overflow Exploitation

Buffer overflow occurs when a process attempts to write more data to a fixed-length block of memory than it is allowed to hold. Attackers can use the excess data, which is stored in adjacent memory addresses, as a foundation from which to start attacks.

### Malware

Malware is software that is written specifically to take advantage of vulnerabilities or otherwise cause damage to the database. Malware can arrive via any endpoint device connecting to the database’s network.

### Attacks on Backups

Organizations that fail to protect backup data with the same stringent controls that are used to protect the database itself can be vulnerable to attacks on backups.
