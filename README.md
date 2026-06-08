## Linux Fundamentals for Data Engineering
*A hands-on walkthrough of server access, user management, PostgreSQL setup, and essential Linux commands*
## Introduction
One of the most important skills for someone new to data engineering is learning how to interact with Linux servers. Whether it's cloud servers, databases, or data pipelines, most data infrastructure is running on Linux. Navigating a Linux environment is no longer an option for data engineers, but a prerequisite skill they must master if they are to succeed (Byrone_Code, 2026). In this article, I will take you through what I did in the hands-on assignment, where I had to connect to a remote server, install PostgreSQL, make a database and execute some basic Linux commands. For every step, I will clarify its meaning and importance in data engineering. You will have a firm grasp of the basics of Linux that you can use in your own data engineering journey by the end of this article.

## 1. Connecting to a Remote Server Using SSH
The most important thing any data engineer should learn is how to connect to a remote server. More realistically, we are not processing jobs on our laptop, or running pipelines, or storing data on a local database. The program used to log on to these servers is called Secure Shell or SSH. SSH provides a secure login to a remote system and the ability to control the system using the command line. The basic syntax is:

```bash
ssh username@server_ip_address
```
In my case, I had to log on to the assignment server as follows:
```bash
ssh root@159.65.222.96
```
![SSH Login](screenshots/successful_login.png)





