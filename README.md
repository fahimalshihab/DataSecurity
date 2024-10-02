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

# SQL or NoSQL Injection Attacks
### What is SQL injection (SQLi)?
SQL injection (SQLi) is a web security vulnerability that allows an attacker to interfere with the queries that an application makes to its database. This can allow an attacker to view data that they are not normally able to retrieve. This might include data that belongs to other users, or any other data that the application can access. In many cases, an attacker can modify or delete this data, causing persistent changes to the application's content or behavior.

### What is the impact of a successful SQL injection attack?
A successful SQL injection attack can result in unauthorized access to sensitive data, such as:

**Passwords.**
**Credit card details.**
**Personal user information.**

SQL injection attacks have been used in many high-profile data breaches over the years. These have caused reputational damage and regulatory fines. In some cases, an attacker can obtain a persistent backdoor into an organization's systems, leading to a long-term compromise that can go unnoticed for an extended period.

### SQL injection examples
There are lots of SQL injection vulnerabilities, attacks, and techniques, that occur in different situations. Some common SQL injection examples include:

- Retrieving hidden data, where you can modify a SQL query to return additional results.
- Subverting application logic, where you can change a query to interfere with the application's logic.
- UNION attacks, where you can retrieve data from different database tables.
- Blind SQL injection, where the results of a query you control are not returned in the application's responses.

### How to prevent SQL injection
You can prevent most instances of SQL injection using parameterized queries instead of string concatenation within the query. These parameterized queries are also know as "prepared statements".

The following code is vulnerable to SQL injection because the user input is concatenated directly into the query:

```
String query = "SELECT * FROM products WHERE category = '"+ input + "'";
Statement statement = connection.createStatement();
ResultSet resultSet = statement.executeQuery(query);
```
You can rewrite this code in a way that prevents the user input from interfering with the query structure:

```
PreparedStatement statement = connection.prepareStatement("SELECT * FROM products WHERE category = ?");
statement.setString(1, input);
ResultSet resultSet = statement.executeQuery();
```
You can use parameterized queries for any situation where untrusted input appears as data within the query, including the WHERE clause and values in an INSERT or UPDATE statement. They can't be used to handle untrusted input in other parts of the query, such as table or column names, or the ORDER BY clause. Application functionality that places untrusted data into these parts of the query needs to take a different approach, such as:

- Whitelisting permitted input values.
- Using different logic to deliver the required behavior.

For a parameterized query to be effective in preventing SQL injection, the string that is used in the query must always be a hard-coded constant. It must never contain any variable data from any origin. Do not be tempted to decide case-by-case whether an item of data is trusted, and continue using string concatenation within the query for cases that are considered safe. It's easy to make mistakes about the possible origin of data, or for changes in other code to taint trusted data.


# What is Data Encryption?

Encryption in cyber security is the conversion of data from a readable format into an encoded format. Encrypted data can only be read or processed after it's been decrypted.

###  How does encryption work?
When information or data is shared over the internet, it goes through a series of network devices worldwide, which form part of the public internet. As data travels through the public internet, there is a chance it could be compromised or stolen by hackers. To prevent this, users can install specific software or hardware to ensure the secure transfer of data or information. These processes are known as encryption in network security.

## Common Encryption Techniques

Encryption is the process of converting plaintext into ciphertext, making it unreadable to unauthorized parties. There are two primary methods:

### Symmetric Encryption
* **Same key for encryption and decryption:** This means both the sender and receiver use the same secret key to encrypt and decrypt data.
* **Advantages:** Fast and efficient.
* **Disadvantages:** Secure key distribution is a challenge. If the key is compromised, the entire communication is compromised.

**Examples:**
* **DES (Data Encryption Standard):** An outdated symmetric algorithm.
* **3DES (Triple Data Encryption Standard):** A more secure version of DES, but also becoming outdated.
* **AES (Advanced Encryption Standard):** The current standard for symmetric encryption, known for its strength and efficiency.

### Asymmetric Encryption
* **Different keys for encryption and decryption:** A public key is used for encryption, and a private key is used for decryption.
* **Advantages:** Secure key distribution, as the public key can be shared publicly.
* **Disadvantages:** Slower than symmetric encryption.

**Examples:**
* **RSA (Rivest-Shamir-Adleman):** One of the most widely used asymmetric algorithms.
* **ECC (Elliptic Curve Cryptography):** A newer algorithm that offers similar security to RSA but with smaller key sizes.

### Hybrid Encryption
* **Combination of symmetric and asymmetric:** A symmetric key is used for encrypting the actual data, and an asymmetric key is used to encrypt the symmetric key. This provides the speed of symmetric encryption with the security of asymmetric encryption.

### Other Encryption Techniques
* **Hashing:** Creates a fixed-size digital fingerprint of data. While not technically encryption, it can be used for data integrity verification.
* **Steganography:** Hides data within other data, making it difficult to detect that encryption is taking place.

**Choosing the right encryption technique depends on factors such as:**
* **Security requirements:** How sensitive is the data?
* **Performance needs:** How fast does the encryption need to be?
* **Key management:** How will the keys be distributed and managed?

By understanding these techniques, you can make informed decisions about protecting your data.


## What is hashing?
Hashing is the process of converting data — text, numbers, files, or anything, really — into a fixed-length string of letters and numbers. Data is converted into these fixed-length strings, or hash values, by using a special algorithm called a hash function.


![image](https://github.com/user-attachments/assets/713fc466-208d-4356-acb6-2a4c83dc963d)


### What Are Hashing Algorithms Used For?
- **Password storage:** Hashing is used to store passwords securely by converting them into a scrambled format, making it difficult for hackers to steal them.
- **Digital signatures:** Hashing is used to create digital signatures, which can be used to verify the authenticity and integrity of a message or document.
- **Document management:** Hashing can be used to authenticate data by generating a hash value that can be compared to the original to determine if the document has been modified.
- **File management:** Hashing can be used to index data, identify files, and delete duplicates, saving time and resources.

### Hashing Algorithm Examples 
It may be hard to understand just what these specialized programs do without seeing them in action. 

Imagine that we'd like to hash the answer to a security question. We've asked, "Where was your first home?" The answer we're given is, "At the top of an apartment building in Queens." Here's how the hashes look with:

**MD5: 72b003ba1a806c3f94026568ad5c5933**


**SHA-256: f6bf870a2a5bb6d26ddbeda8e903f3867f729785a36f89bfae896776777d50af**

Now, imagine that we've asked the same question of a different person, and her response is, "Chicago." Here's how hashes look with:

**MD-5: 9cfa1e69f507d007a516eb3e9f5074e2**


**SHA-256: 0f5d983d203189bbffc5f686d01f6680bc6a83718a515fe42639347efc92478e**


Notice that the original messages don't have the same number of characters. But the algorithms produce hashes of a consistent length each time. 

And notice that the hashes are completely garbled. It's nearly impossible to understand what they say and how they work. 

Database Management with Hashing
================================

Hashing can greatly simplify the process of searching for data in large databases. Instead of relying on index structures, hashing allows you to search for a data record using a search key and hash function.

### How Hashing Works in Database Management

Hash files store data in **buckets**, and each bucket can hold multiple **records**. Hash functions are used to map **search keys** to the location of a record within a bucket.

### Hashing Methods in Database Management Systems (DBMS)

There are two hashing methods you can use in a DBMS:

#### 1. Static Hashing

* A search key and hash function always lead to the same address.
* The number of buckets remains fixed.
* When adding a new record, a hash key is used to automatically generate an address for the record and store it.
* The same key is used to locate the record when accessing, updating, or deleting it.

#### 2. Dynamic Hashing (Extendible Hashing)

* Allows for data buckets to be created and removed as needed.
* Prevents bucket overflow, which occurs when a bucket doesn’t have enough space for a new record.
* Provides more flexibility and scalability than static hashing.

### Benefits of Hashing in Database Management

* Faster search times
* Improved data retrieval efficiency
* Reduced storage requirements
* Simplified data management and maintenance

### Use Cases for Hashing in Database Management

* Large-scale data storage and retrieval systems
* High-performance database applications
* Real-time data processing and analytics systems
* Distributed database systems

**Here some recent Security Vulnerabilities, CVEs (Sql injection)**

**SQL Injection Vulnerabilities**
=====================================

### CVE-2024-47062
* **Published:** 2024-09-20
* **Last Update:** 2024-09-26
* **Max CVSS Base Score:** 9.4
* **EPSS Score:** 0.05%
* **Summary:** Navidrome is vulnerable to SQL injection due to improper parameter handling, allowing attackers to access information and inject arbitrary SQL code.

### CVE-2024-46626
* **Published:** 2024-10-02
* **Last Update:** 2024-10-02
* **Max CVSS Base Score:** N/A
* **EPSS Score:** N/A
* **Summary:** OS4ED openSIS-Classic v9.1 contains a SQL injection vulnerability via a crafted payload.

### CVE-2024-46510
* **Published:** 2024-09-30
* **Last Update:** 2024-09-30
* **Max CVSS Base Score:** 7.6
* **EPSS Score:** 0.04%
* **Summary:** ESAFENET CDG v5 contains a SQL injection vulnerability via the id parameter in the NavigationAjax interface.

### CVE-2024-46472
* **Published:** 2024-09-27
* **Last Update:** 2024-09-30
* **Max CVSS Base Score:** 8.6
* **EPSS Score:** 0.04%
* **Summary:** CodeAstro Membership Management System 1.0 is vulnerable to SQL Injection via the parameter 'email' in the Login Page.

### CVE-2024-46382
* **Published:** 2024-09-19
* **Last Update:** 2024-09-25
* **Max CVSS Base Score:** 7.5
* **EPSS Score:** 0.08%
* **Summary:** A SQL injection vulnerability in linlinjava litemall 1.8.0 allows a remote attacker to obtain sensitive information via the goodsId, goodsSn, and name parameters in AdminGoodscontroller.java.

### CVE-2024-46374
* **Published:** 2024-09-18
* **Last Update:** 2024-09-20
* **Max CVSS Base Score:** 9.8
* **EPSS Score:** 0.04%
* **Summary:** Best House Rental Management System 1.0 contains a SQL injection vulnerability in the delete_category() function of the file rental/admin_class.php.

### CVE-2024-46103
* **Published:** 2024-09-20
* **Last Update:** 2024-09-26
* **Max CVSS Base Score:** 9.8
* **EPSS Score:** 0.04%
* **Summary:** SEMCMS 4.8 is vulnerable to SQL Injection via SEMCMS_Main.php.

### CVE-2024-45999
* **Published:** 2024-10-01
* **Last Update:** 2024-10-01
* **Max CVSS Base Score:** N/A
* **EPSS Score:** 0.04%
* **Summary:** A SQL Injection vulnerability was discovered in Cloudlog 2.6.15, specifically within the get_station_info() function located in the file /application/models/Oqrs_model.php.

### CVE-2024-45771
* **Published:** 2024-09-06
* **Last Update:** 2024-09-09
* **Max CVSS Base Score:** 9.8
* **EPSS Score:** 0.04%
* **Summary:** RapidCMS v1.3.1 was discovered to contain a SQL injection vulnerability via the password parameter at /resource/runlogin.php.

### CVE-2024-45622
* **Published:** 2024-09-02
* **Last Update:** 2024-09-03
* **Max CVSS Base Score:** 9.8
* **EPSS Score:** 0.05%
* **Summary:** ASIS (aka Aplikasi Sistem Sekolah using CodeIgniter 3) 3.0.0 through 3.2.0 allows index.php username SQL injection for Authentication Bypass.

### CVE-2024-45265
* **Published:** 2024-08-26
* **Last Update:** 2024-09-05
* **Max CVSS Base Score:** 9.8
* **EPSS Score:** 0.09%
* **Summary:** A SQL injection vulnerability in the poll component in SkySystem Arfa-CMS before 5.1.3124 allows remote attackers to execute arbitrary SQL

Source : https://www.cvedetails.com/vulnerability-list/opsqli-1/sql-injection.html
