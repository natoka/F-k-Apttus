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
1. The data model is over-designed, in our org with has 298 Apttus objects, some org with about 500 object as I know, none from Apttus can explain the more 20% object purpose, and you only use up to 50 of the objects, others who know why they are there, then why we need those object in our Org?
2. The product is designed about 15 years ago, from that on the UI and process not many changes, if you compare Salesforce UI and Lightning then you know what's I'm mean, now is 2018 and Lightning Experience, when using Apttus, like you are using Windows XP.
3. The product catalog and shop cart also slow, this is a known issue within the whole CPQ industry, but Apttus never make this changes, no improvement.
4. Exception and errors pop up in the screen, the developers is very experienced limited (probably 1. 2 year developers), even don't know how to handle exceptions, there is no reason you popup exception to the users, at least catch them and pop in the debug log.
5. The GREAT product team, every time the success manager and supports says report to the product team and wait for the response, then NEVER response during my 4 years only 1 or 2 bugs been fixed, good luck for you rely on their product team, No matter in production, users need the feature every day, you can't wait, but feedback from Apttus is "sorry, and appreciate your understanding", what the f**k, is 2018 now.
6. Lighting Ready isn't Lightning Experience, Apttus never got chance to be Lightning Experience, if you worked or developed a product with 15 years old, you know how hard to make the changes unless you refactor the whole product which will cost much, if they are that's Steelbrick, now Salesforce CPQ (Now, you know why Salesforce acquisition Steelbrick).

# Customer Service
1. Everything is a price, without a premier support you can't get anything helps, unfortunately, because of the product terrible quality you pretty relay on their services
2. The response is very slow, every emergency, Production issues all rely on the in-house team, and if you don't have an experience in-house Salesforce team, then good luck for you.
3. You know what's Salesforce support right? Aptttus support is the other side quality and service, be sure not Salesforce style.
4. Apttus using Dynamic for the customer service, no more Salesforce Service cloud, the case number is Case:**CAS-06124-W0X6D3**, when you contacting with Apttus support, they ask, what's your case number, then "Humm..... CAS....", if you can tell them the correct case number you are genius, what's the f**k case number, Apttus asking "Stupid!! DON'T open case!!".
5. Debug Log, debug log is everything for Salesforce issue debug, as Apttus is managed packages, there is no way to get any debug log, and all the issue fix all rely on Apttus, you can't do anything.
6. Apttus asked you send emails to documentation@apttus.com if you have any question or need help, but once you send them an email, you will get the following auto-reply.
![enter image description here](https://lh3.googleusercontent.com/b0a4YSgSFfb-MTltWeByrmLNDtv7_jcb-yHrOp_wfy_hR7-FIxONNqnma6MeDBjQU6yQnOIeRNzU)

# Product Quality
1. Exceptions anywhere
The developers should be been trained to write a professional code if see Apttus code you know what's low-quality software development, and exception handling, you can see exception anywhere, even though very positive process and operations.

![enter image description here](https://lh3.googleusercontent.com/J1o1t5t7O_sp5NKR1-DuL5Y019PDtvxsahloS9ebiNhviEO17MA4nUj18eSYNvIjJPSSETyXGu1R)

2. External service side (like xAuthor generator) upgrade without notifications, they only way you figure this out is the when user report the issues, unfortunately, that's too late, LIVE system, Apttus can't understand what's Production environment.
3. Waste spaces, the only way is to overwrite the CSS file to make to cart workable. unfortunately still wasn't half of the screen and no way to make additional changes.

![enter image description here](https://lh3.googleusercontent.com/Re8U9gh32D4g8w9POFJMkrJqyct1shFk5nLOSJMv6LeBih0tVaCRCoF4YLT54qq5tkm6lpHSl41U)

4. Low effecitve SOQLs

        SELECT Id, Name, CreatedDate, Apttus_Config2__Status__c, Approval_Status__c
FROM Apttus_Config2__ProductConfiguration__c
WHERE (Apttus_Config2__BusinessObjectId__c = :tmpVar1
    AND Apttus_Config2__Status__c != :tmpVar2
    AND (Approval_Status__c != :tmpVar3 OR Approval_Status__c != NULL))
ORDER BY CreatedDate DESC NULLS FIRST LIMIT 1



# Others:
When Apttus open the case detail page you will find out they are using Dynamic CRM, as a Salesforce ISV partner, Apttus using Dynamic CRM, are you saying Salesforce is a shit?


#**Standard Case Comments:**
Greetings of the day!

This is regarding your Apttus Case # CAS-06605-B4C2V0 Exceptions when generating the quote

As per Apttus Technical Support policy, **we would be unable to share the debug logs.**

While we are working with our Tier 2 team, we need following details to take this forward.

- We request you to create a user with email rgandhi@apttus.com with X-Author for Contracts System Admin permissions.  
- Also, please share the URL of the record on which we are getting the same error when we finalize the quote.  
- Please provide us permission to create a clone of given template for testing purpose.  
- Also, we want to confirm if the same error is arising when we use any other template other than “EnglishFirst-Russian-Order-Invoice”

We look forward to hear from you on the above mentioned details.

Please feel free to reach out to us in case of any further queries. We would be happy to help.

We appreciate your Business with Apttus.


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU2NTEwOTUwNCwtNTI0ODQ4MjM1LDIwNj
U5ODg5MDEsLTE3MzM3MzEzODgsLTE2NjAyMTgwODAsLTIxNDYw
MzQ1MDYsNDQyOTU0MzQsLTIxMDI3OTYwMDcsNDA3MTkyMTE2LD
E5NDMwMjYxMCw3NTA4MjQ5NDYsLTY4MzQ1NzcyMCw1MjUwMjYy
OTIsNTY1NjgyNzQyLDY2Mjk2MDg5NSw1NjAzMzgxMDYsLTE0ND
Y4NDA1NjVdfQ==
-->