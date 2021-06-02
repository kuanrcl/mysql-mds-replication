# Inbound replication from MySQL Database to MySQL Database Service in OCI

![Oracle Workshop](images/banner.png)

## Description

Access and navigate Oracle cloud dashboard
Create an Oracle Compute Instance and install MySQL Database
Create MySQL Database Cloud Instance
Replicate MySQL Database from the Compute instance into MySQL Database Cloud
Run OLAP workloads on MySQL Database Cloud powered by Heatwave engine

## Who Should Do This Workshop
- You want to **build a hybrid cloud** for your existing MySQL infrastructure
- You want to **learn Oracle Cloud Infrastructure**.
- You want to explore **Oracle Cloud and its Free Tier**.
- Estimated Workshop Time: 120 minutes.

## Content

[Get Started: Sign Up for your Oracle Cloud Free Tier](Lab0/README.md)

- Create Your Free Trial Account
- Sign in to Your Account

[Lab 1: Create a Compartment, a Virtual Cloud Network and allow traffic through MySQL Database Service port](Lab1/Lab1.md)

- Learn how to create a compartment to host resources in your OCI tenancy
- Learn how to create a Virtual Cloud Network with internet connectivity
- Add ingress rules in the security list to allow traffic through MySQL Database Service ports

[Lab2: Create the Replication Source](Lab2/Lab2.md)

- Learn how to create a Compute Instance in a specific compartment
- Learn how to use Cloud Shell to connect to a compute instance via ssh
- Learn basic MySQL commands to connect to a local database server and to list schemas


[Lab3: Create MySQL DB System (MDS) to use as Replica](Lab3/Lab3.md)

- Learn how to deploy and configure a Standalone MySQL Database Service.
- Learn how to create the Administrator user for the MDS

[Lab4: Create a MySQL Router Instance to connect MDS with the Replication Source](Lab4/Lab4.md)

- Learn how to create a compute instance in a specific compartment
- Learn how to use Cloud Shell to connect to a compute instance via ssh
- Modify the MySQL Router configuration to point to Replication Source and test the connection

[Lab5: Create the Replication Channel](Lab5/Lab5.md)

- Learn how to create an MDS Replication Channel in OCI to use inbound replication
- Learn how to check the status of the replication

---

## Let's Get Started

Sign Up for your Oracle Cloud Free Tier to [**Get Started!**](./Lab0/README.md)

## Ready to go? Jump directly to the first Lab!

[**Go to Lab1!**](./Lab1/README.md)
