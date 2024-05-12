# Microsoft Active Directory
Source: [Learn Microsoft Active Directory (ADDS) in 30mins by  Andy Malone MVP](https://www.youtube.com/watch?v=85-bp7XxWDQ&t=304s)

## The Basics

-	Identity platform
    - Present credentials (e.g. username and password)
    -	Given permissions to resources
-	In essence, it is a database of objects (users, groups, devices)
-	Two ways to look at it
    -	Logical perspective
        -	How the structure is laid out
    -	Physical perspective
        -	The actual database
        -	Important to have it backed up/replicated to another server
-	Active Directory Domain Services (ADDS)
    -	The directory service of Windows Server 2016, 2019, and 2022
-	Organizational Units (OUs)
    -	Act as folders
        -	Can be made for locations, departments, functions, etc.
-	Objects have attributes
    -	Attributes for a user = first name, last name, email address, etc.
-	Schema
    -	Complete set of object types
-	Reasons to replicate the master copy of Active Directory
    -	Disaster recovery
    -	Performance/load balancing
-	Domain Controllers (DCs)
    -	Servers with Active Directory installed
-	Intra-site Replication
    -	Replicate automatically
    -	High-speed bandwidth
    -	Within one site
-	Inter-site Replication
    -	Used for remote sites without high-speed bandwidth
    -	Between sites
-	Child Domains
    -	Often used by large corporations to create boundaries between different locations and/or departments
    -	Helps to improve security


