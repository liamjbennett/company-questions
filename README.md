#Company Questions
After having seen several people fumble at the end of the interview to ask questions about the company and also having been that candiate with a rough piece of papper in my back pocket I decided to compile a list of questions that I find useful to ask any future employeer.

This is very much aimed at those of us in Agile/DevOps roles. You may decide to select the a couple to ask at the end of the interview process or you may (if appropriate) ask your employeer for answers on all of them.

I have split this up into 4 sections: Company, Product, Process and Tools - the order is deliberate and based upon the level of importance that I give to each. I will attempt to add useful descriptions to each question so that you can understand the motivation for asking it. Other questions, that I am thinking about also be found elsewhere in this repository.

##Company

####Why does [company] do what it does?
This is a great starting question. What your looking for here is the vision of the company - it's the why, not the what or the how. Newer companies will likely be able to tell you this pretty easily but big older enterprise firms may struggle. This is classic goldern circle stuff - if they can't tell you why they do what they do then why should to care. A company that can tell you what it does might earn your loyalty for a few years until a new technology or new start-up comes along. A company that can tell you why it does what it does will be able to keep you there however many times they decide to pivot and do something new.

####Why do you work for [company]?
This is a very personal question so the answers that you get will vary widely but as well as telling you about the person that you might be working with it will also tell you the type of environment that you might be walking into. Do they work for the company for the money, for the technology, or for the vision?

####What is the best/worst part of your job?
This is not just a question for your interviewer, ask this to everyone you get to meet in the compmany. Ask what they do, find out their role and purpose within the organisation and try and discover the good, bad and ugly parts of the job. Most people, particularly in an interview situation will find it easy to tell you the best parts (they are trying to sell the organisation after all) but they will find it difficult to tell you the bad bits. Maybe try and ask yourself this question about your current role as it will help you try and find out what sort of answers you are looking for.

####What are the top 3 projects your are working on or planning right now?####
This is a pretty simple one. They *should* tell you about projects that are important to the business but in a technical role they might very well tell you about projects they excite them. Do these projects excite you? Do they challenge you?

####Do you have an dedicated Ops team? What are their responsibilities?####
The answer to this question will vary widely for organisation to organisation. The key thing your looking for here is there approach to the DevOps methodology? Do they have a big Ops team that does deployments and infrastructure and a big wall between them and the developers? Is the Ops team under a different management structure than Dev? In larger organisations you will almost certainly have an Ops team but if they are doing deployments then they are doing it all wrong. If they are just racking and stacking hardware then that's probably ok.

####What is your policy on remote working?
This is a fortunate benifit of working in one of the service industries that we are able (in theory) to always work remotely from anywhere. It still shocks me that not all companies are get up for this and that some companies are actively against the practice. There are some justified reasons against it and some fairly big cultural challenges to overcome in order to make it work but it is still possible and, in my opinion, should be encouraged. Asking about this to your interviwer gives you a good idea of the culture of the company. Is it a company of fixed hours and timesheet-based working with little trust or is a company with flexiable working hours, asynchronous communication and total trust? Which meets your current needs and your current working style? 

####How do you manage the communication problem of out-of-office teams and/or remote workers?
If employees are working remotely or the company is of a size as to be cross-site then how does the company manage this? How do you make sure that everyone is kept in the loop and that on-one is missed out? Do you do long email chains? Do you bring people in from remote sites for meetings or on a periodic basis? Do you do ChatOps? How is the scaling for your orgnaisation?

####What are your top 3 business metrics? Can everyone see them?
I am an engineer and a craftsman but I do care about the direction of the company. What does to comapny really care about? Annual Revenue? Cost per-user? Returning customers? Click-through rates? It doesn't really matter what they are just as long as they have some and can explain why they are important. Also who can see these metrics? Can the whole business see them on massive dashboards or is it something just for finance and the executives?

####What has been the challenge for your organisation in adopting Continuous Delivery?
Do they know what Continous Delivery (CD) is? If not then back away very slowly. Assuming that they do know what CD is then you want to try and understand their experiences of it. Every company has it's own story of adoption, it's own problems and difficulties both cultural and technical. Discuss these, share your own stories and chat about possible future oppertunities.

####What are your thoughts on the roles of Build/Release engineer, DevOps, DevTools etc – are they the same or different?
This question is attempting to dig into what the role really is. Titles are ultimately a pointless label given out in organsiations and are not something that is every equal from one organisation to the next. Build engineers can either be junior employees who spend their whole day merging branching and building packages or they can be cross-domain jacks-of-all-trades who can adapt to many roles. DevTools is another common title appearing where build and release engineering is evoling to being more about providing tools for the whole business to use. **Ask about DevOps** - if this is in the job title then they have got it all wrong. You may find DevOps in the job description, it's become a bit of a shorthand but it shouldn't be in the title beause you can also guantee that it means that the hiring manager or C-level exec thinks that they can "buy the DevOps".

####How many teams do you have and what do they do?
A start-up will probably have one team of a few guys who do everything development and operations related. As the company grows teams will naturally form, either around technical speciailities or around functional product areas. Which of theses in your company? Do you have a Ops team, a database team, front-end developers and backend-developers? How are they orgnaised? Are they in the same location? Or do you have cross-functional teams? How does this effect the communication and the productivity of the business?

##Product
####Can you give me a 10,000ft view of your infrastructure and architecture
A lot of companies will not want to share all the details of their infrastucture and the tools that they use because they believe it to be part of the "secret sauce" but hopefully you will be able to get the 10,000ft view -- the rough 5min outline. Are they bare-metal or AWS? 3-tier or multi-tier? Postgres or Mysql? Get a rough idea of what your walking into and if your skills match and if you want to move in that direction. Hopefully the company will be able to tell you all about their infrastrcuture because it's really nothing special these days - there is a limit set of hardware vendors, software vendors and open source projects.

####What is the best thing about your product/process/infrastructure?
What is the best thing you have? Why should I be exicited about the company? What makes your culture different? Have you released any tools open source that you want to brag about? What makes your product so much better than your competitors?

####What is the worst thing about your product/process/infrastructure? 
This is the tougher question. What work does the company still have to do? What is difficult? Are their any limiting constrints on your company that you need to try and address and/or manage in a unique way. Do you have legacy infrastrcutre that you wish would just die? Do you have a product that you have to support that was written 15 years ago and is scary to change?

##Process
####Can you explain your build pipeline?
What stages are there? What checks and permissions are there? Is your pipeline cross-project? How does your pipeline integrate with the overall business pipeline? Is it growing, is it scaling? What is missing?

####What is your open source policy?
Do you even have one? What is your policy for using open source software? Do you audit it, do you control it at build time? What is your policy for releasing software into open source? How do you determine the corporate sensitivity of the code your write and if it is appropriate or not to open source? Is your code really that special?

####Do you do code-review and/or pair programming?
This is not just about code quality but it's about education and team building. Juniors learning from Seniors. Assumptions being broken and mistakes being avoiding. It takes time, is hard to do and some companies avoid it because of that. Is this something you care about as an employee? How does the company manage this process without it being too heavy-weight?

####What is your test coverage?
Ok, this is a bit of a trick question. If the response in 90%+ then be very suspicious because the quality of these tests might not be as good at they think it is. Also test coverage is really only about unit tests so want you really want to know is how many of your user stories/workflows have been tested. It is good to know that they care about this stuff but make sure that they care about the right thing and are not just chasing some theorical number that they belive that should have.

####What is your average build time?
If they know the answer to this at all then thats great but it doesn't really mean a huge amount unless then can quantitfy it in relation to the rest of their build pipeline. Build times can vary widely from projec-to-project and from one technology to another but the important thing is that they know builds should be < 10 mins to be useful and that they care about this.

####How often do you release?
This is the **BIG** million dollar question. Nothing matters unless it is relased to customers - it has zero value. How often do they deploy code? It is faster or does deployment also equal release? Deployments that are once a month are not useful for anyone and usually mean big painful cruch-time the few-days before. Also even if your deploying once a day and do a big release effort once a month that is still a painful thing to do and a lot of feature flags to maintain. If they don't do any of these things then this is a clear sign that you are moving into a "legacy" organisation and unless you honestly believe you can change this then you need to move on to another job opperunity.

##Tools

####What monitoring solution do you use?
I don't care which. I just want to know you have one and discuss how you use it. Is it scaling? Do you have actions that are triggered by checks so that I don't have to make up at 3am and deal with something? How is your monitoring evolving? What should be a check and what shouldn't be? How does this integrate with your software testing effort?

####What is your configuration management solution?
Again - I don't care which. I do care why you chose one solution over another one. I do care about how you manage this codebase. It is modular? It is tested? Are you using vagrant? How much is open sourced back to the community? 

####How do you deal with drift in configuration?
Environment configuration is only as good at the configuration that is actually managed. How do you determine where you have gaps in your CM solution? How do you deal with configuration dift? Do you accept it or periodically rebuild?

