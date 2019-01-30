# Case Study Assignement
## Case 1: PlentyOfFish Architecture
![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/images/pof.png "PlentyOfFish")
### What market does that company serve? (What do they do?) And have they always served that market?
PlentyOfFish is an online dating service where they match potentail people with others to have dates.
### What Operating System(s) are used?
The OS that they use is Windows
### Why do you think those were used?
They are using windows because it is much easier and popular operating system to get people that want to match with another person.
### What programming languages/frameworks are used?
They are using ASP.NET as their primary web framework. It is written in C#
### Why do you think they were used?
They use asp.net to develop since it is easier to deal with massive amounts of views and does not stress out their servers as much since they only run 2 web servers
### What storage and what database technologies are used?
Thier systme is a web server with 8 GB of ram and 2 hardrives that run windows x64 server 2003. While thier database servers connect through Akamai at 1 TB/day. 6 TB storage arry to handle uploads every month.
### What is the current stock price and what was the IPO of the company? (if traded publicly.)
PoF is estimated to be worth around 1 Billion dollars. This is due to their very good advertasing revenue.
### What major obstacle (cost, system performance, QPS, etc, etc) was the company trying to overcome by implementing this technology stack?
The site is run by a small group and has had slow perfermance in terms of data speed. They were able to solve thier issue with more RAM which was bottlenecking thier servce.
### What can you learn from this article relating to technology architecture?
Some of the things that I learned from this reading is that you do not need a huge organization to run a well built application. RAM is a very important component in order to run a fast website. Ad revenue bottlenecks the growth of a company after a certain point. In order go make PoF larger chaning to a paid model will help the company earn more revenue.

## Case 2: Stack Overflow Architecture
![alt text](https://github.com/giancarlobarillas/itmt-430-/blob/master/images/stack.png "
StackOverflow")
### What market does that company serve? (What do they do?) And have they always served that market?
Stack Overflow is a question and answer site for technology. It has always served this purpose because it was designed by two developers who wanted to solve problems
### What Operating System(s) are used?
They use Windows to run their systems
### Why do you think those were used?
It is probably easier for thie web and database tier to work together.
### What programming languages/frameworks are used?
They are using JQuery, SQL, LINQ, and ASP.NET
### Why do you think they were used?
These are all fast languages to build a platform such as this. The two developer took the avaiable languages and devloped an simple site that can handle millions of views and pages.
### What storage and what database technologies are used?
On thier web tier they use 500 GB datacenters hard drives mirrored, 8 GB Ram and 500 GB RAID 1 mirror array. On thier database teir they use 48 GB of RAM. They use LINQ to SQL to access database information
### What is the current stock price and what was the IPO of the company? (if traded publicly.)
Stack overflow is estimated to be worth around 3 Billion dollars today.
### What major obstacle (cost, system performance, QPS, etc, etc) was the company trying to overcome by implementing this technology stack?
Like with most sites speed is the priority. Upgrading ram is essential to any webist trying to improve speeds. Another issue that stack overflow had was slow preformance that was due to poorly optimized equipment. They found out that by keeping thier drivers up to date they could also increase preformance.
### What can you learn from this article relating to technology architecture?
RAM is so important to websited especially on the database side. Another important equipment to consider is CPU speeds. This can cause a linear improvement in terms of query time.