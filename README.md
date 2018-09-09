# F**k Apttus
> The driving force for me to set up this article is, DON'T MAKE THE WRONG DECISION in CPQ AGAIN for all the Salesforcers, I'd paid a lot.
> This is only my personal opinion, not related to the company I'd worked (PwC) or working (EF).

## Introduction
>Some of the history of CPP -> CPQ history.

**BigMachines** is a software company, founded in **2000** by **Godard Abel** and Christopher Shutts, Oracle Corporation announced it was acquiring BigMachines on **10/24/2013** ($400M+). Oracle kept the product, now called CPQ Cloud.
Name: BigMachines CPP 6.2.0 (Configure, Price, Propose CPP)
First Release: 3/31/2006
Latest Release: 7/22/2015, after that BMI leave Force.com Platform.

**Apttus** founded in **2006**, Apttus is the category-defining Quote-to-Cash software company that drives the vital business process between the buyer’s interest in a purchase and the realization of revenue.

**Godard Abel** founded **SteelBrick** in **2014**, the global team from 5 to 200 employees and increased bookings by 37x in less than 2 years. Salesforce acquired SteelBrick on **2/1/16** ($400M+), now called Salesforce CPQ
![Godard Abel](https://media.licdn.com/dms/image/C4E03AQHJCbLb0BaCxA/profile-displayphoto-shrink_800_800/0?e=1542240000&v=beta&t=4Gf8tsWFgol6aWk5QzM_uWsUNBlsUcofuSmB2I5tX5E)

My strong feeling after my 4 years worked with Apttus, if I have a choice I won't work with Apttus for a second project, unfortunately, I have to work for them one by one as the huge marketing demands.

# Culture and work philosophy
Which I believe is the most important for a company, like Salesforce Honesty, Open, Share, Collaborate and Innovative, that why Salesforce.
In Apttus you can't find a document which describes the feature well, the culture is very protective and old, also very hard to find help from Apttus, you have to pay for the premier supports every time (and without a Premier support SLA)


# Solution Maturity
1. None knows the Package components, in our Org, installed 12 packages just to make the CPQ features work, and there are no ways for you to upgrade them in LIVE safely, believer me no human can guarantee to upgrade such complex package safely, and once upgrade failure, there is no way to rollback, better no upgrade after installation. if you like to upgrade, good luck for you,
2. None knows how to quote as none understand the components, price always depending on how stupid/smart (none smart when you start talking price with Apttus) the customer is (good luck to you).
3. Never close a case in time no matter have primer support or not, the issue in LIVE or sandbox, the issue is OOTB or customized built, support always starts bullshit a week, then start to work.
4. The key factor for a CPQ project is the person, I have to say Apttus guys very familiar with CPQ terminologies and processes, so even with Apttus packages, you have to do a lot of customization which designed by Apttus implementation consultants. By end of the day, you will have more than 50% of the customized components beside Apttus packages, which make you have no reason to pay Apttus license, but you have to because of those customization relay on Apttus packages... good luck...
5. Because of those customizations made the package upgrade even though complex and risky.

# Product Design
1. The data model is over-designed, in our org with has 298 Apttus objects, none from Apttus can explain the more 20% object purpose, and you only use up to 50 or the objects, others who know why they are there, then why we need those object in our Org?
2. The product setup is designed about 15 years ago, from after release the UI and process not many changes, now is 2018 and Lightning Experience, when using Apttus, like you are using Windows XP.
3. The product catalog and shop cart also slow, this is a known issue within the industry, but Apttus never make this changes, no improvement.
4. Exception and errors pop up in the screen, the developers is very experienced limited, even don't know how to handle exceptions, there is no reason you popup exception to the users, at least catch them and pop in the debug log.
5. The GREAT product team, every time the success manager and supports says report to the product team and wait for the response, then NEVER response, BUT we are in production, users need the feature everything, we can't wait, and feedback from Apttus is sorry, and appreciate your understanding, what the f**, is 2018 now.
6. Lighting Ready isn't Lightning Exprience, Apttus never got chance to be Lightning Experince, if you worked or developed a product with 15 years old, you know how hard to make the changes unless you refactor the whole product which cost much, if they are that's Steelbrick, now Salesforce CPQ (Now, you know why Salesforce acquisite Steelbrick).

# Customer Service
1. Everything is a price, without a premier support you can't get anything helps, unfortunately, because of the product terrible quality you pretty relay on their services
2. The response is very slow, every emergency, Production issues all rely on the in-house team, and if you don't have an experience in-house Salesforce team, then good luck for you.
3. You know what's Salesforce support right? Aptttus support is the other side quality and service, be sure not Salesforce style.
4. Apttus using Dynamic for the customer service, no more Salesforce Service cloud, the case number is Case:**CAS-06124-W0X6D3**, when you contacting with Apttus support, they ask, what's your case number, then "Humm..... CAS....", if you can tell them the correct case number you are genius, what's the f**k case number, Apttus asking "Stupid!! DON'T open case!!".

# Product Quality


# Others:
1. When Apttus open the case detail page you will find out they are using DynamicCRM, what's the f**k!! you are selling Salesforc
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE2Mzk0NjY0OTYsMTk0MzAyNjEwLDc1MD
gyNDk0NiwtNjgzNDU3NzIwLDUyNTAyNjI5Miw1NjU2ODI3NDIs
NjYyOTYwODk1LDU2MDMzODEwNiwtMTQ0Njg0MDU2NV19
-->