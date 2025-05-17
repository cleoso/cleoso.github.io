---
layout: essay
type: essay
title: "Aspire 25 Fincial Web Application"
# All dates must be YYYY-MM-DD format!
date: 2025-05-08
published: true
labels:
  - Next.js
  - Bootstrapped
  - Web Application
  - JavaScript
  - Vercel
---

<img width="200px" class="" src="">

**UI Frameworks**

<h3> Project Aspire 25 </h3>

Part of our ICS 414 Software Engineering course II at UH Manoa, we have a client that wanted to have a comprehensive web application where it allowed respected users in the company to execute financial audits, projections, and more. The web application would replace their pen and paper operations. The client had very specific requirements. The web application should reflect the real world and the work that each member of the company. Therefore, the client had requested that roles be implmeneted to reflect their corporate structure. There woudl be an auditor, executive, admin, and analyst. Each role had a different data permisison for what each role is able to do, what each role is able to read and or write.

The auditor would be able to edit some data in the financial statements that are collected in database on the backened. But they were only able to write and read the outcomes of their inputs. Not the already existing data that is in the system. The executive role is able to toggle stress test on or off, toggle the total, and details about the graphs. Therefore, they are only able to read graphed and charted resultes in the SM. The admin is abel to asssign roles to users (similar to onboarding), creating new user, and deleteing existing users. They are able to read any user accounts and any data from the digital accounts that are made in order to provide new and existing users access to certain information. Finally, the analyst is able to write anything that has a green box in FC, stress test, and workpapers S1-S5B. Analysts are also able to read the SM. 

Given these roles we are given financial data, via excel sheet, where we need to connect to a backend database in order for the website to have data for each role to manipulate. This was the critical part of the web application as it was the bases for where work is going to be done. 

<h3>Obstacles</h3>

Although we had a diverse group set we had to determine how we would align in how we will deliver results, agree on conduct, and communication channels. With a large group of seven we had to discuss the project as a whole. Communication was key to our success, without communication of questions or concerns we would not have been able to have a understanding of the issues that we had, but moreover the client had. For example, we had to determine roles for each user on the account, it was not clear to us what each role was able to see from a front end side and what those roles were able to clearly edit. We had to ask the client and the professor in order to get a better scope of the roles and how the web application would be executing those tasks. 

Secondly, we had to determine the schema of the data within the application. When given roles data is being manipulated and for the most part much of the data is simulation based on real data collected. Therefore, it is important that the data that was provided, via excel data sheets, was not altered when running simulations or audits for example. Furthermore, the integerity of the data needs to be attached to the roles so that when the application renders the data for users its not corrupted by these simulation.

<h3>A Template of success</h3>

Regardless of some of the obstacles that we faced both internally and challenges faced by the project alone our team was successful in collectivley breaking down the project as a whole. 

First we decided that the project was going to be bootstrapped, using the next.js libraries to build the application. Secondly, we would deploy the application on Vercel. Before we began coding, we as a team decided to develop key issues in the beginning with requirements that the client had about the function of web application. This laid foundation for where we will start. 

Afterwards we were able to delegate some work to be done. The issues tab for each milstone allowed our team to better get an understadning of the techncial challenges that we faced each step of the way. For each milestone we had to deliver an update to the client direclty about the progresssion of the applciation. Each milstone the client was able to make a suggestion about what could be tweeked and either veto some solutions that the team brought. 

Nonetheless, after each milestone we provided the client with significant updates and by the end of the semester we had a fully functioning web application. However, here is what I would say our team could have done better. Ticket formation, when developing issues in our github project it was difficult to understand the issues were and how it needed to be fixed. In cases where one of our team members were gone due to other obligations or emergency, when another team member was going to take over their issue at times the issues would be vauge. This causes much confusion where specificity wouldn't. This backlogged some issues especially when the issue was holding back from another issue being started. 

