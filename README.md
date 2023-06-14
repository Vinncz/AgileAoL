# Report for AoL of Agile Methodology

**Anggota kelompok:**
- 2501977941 – Kevin Gunawan
- 2501967575 – Stevans Calvin Candra
- 2501977784 – Kelvin Giovanno
- 2501977430 – Yofadha Chandra Berliano

This document is the ***report file*** mentioned in the requirements.
\
You can find everything realted with this AOL using the link [here](https://binusianorg-my.sharepoint.com/personal/kevin_gunawan011_binus_ac_id/_layouts/15/guestaccess.aspx?folderid=0b2d18f70a6ab4197b40e99cf629fbfe2&authkey=AUnBmZ5TOaVD-c2Lpoc7dzQ&e=CemF27), or paste the following into your browser:
https://binusianorg-my.sharepoint.com/personal/kevin_gunawan011_binus_ac_id/_layouts/15/guestaccess.aspx?folderid=0b2d18f70a6ab4197b40e99cf629fbfe2&authkey=AUnBmZ5TOaVD-c2Lpoc7dzQ&e=CemF27
\
There might be some improvements over time. Expect new email(s) over the coming week(s).

## Building A New Utility App for a Logistic Company

### I.	Introduction &  Agile Development Methods:

A logistic startup company who goes by the name of TUKU, is preparing to open their business on October 1st, 2023. They had done their market-trend research, and when the result were confirmed in June, they came to a conclusion that an average person are three times more willing to send packages with TUKU, if TUKU is willing to pick their packages from home.

A few months back, TUKU has bought itself an expensive web application. It is specifically tailored to TUKU's needs, that TUKU will basically be depending on this application for as long as it stayed relevant. However, when Edot the TUKU’s CEO looked at the result, he is convinced that a `new mobile application` will be necessary to support the pick-up operations. He stated that the application needs to be able to do two things: **(1) lets the customer to make a pick-up appointment**; and **(2) track customer's packages through the app**.

With merely months before opening, Edot pressured his team to develop a working application quickly as to not miss the important date. Knowing this, the company's software development team has decided that **SCRUM methodology of agile** would work best against the looming deadline.

ㅤ

### II.	Sprint, Requirements, User Stories, and Product Backlog

#### A.	Sprint

**What's a sprint?**
Sprint is a vital part of agile methodology. Sprint is a ***short run of doing something in a given period of time***. They have a pre-determined goal that is raised at the beginning of each sprint, and they are time-boxed: meaning that they have a pre-determined start, and end point. 

**How should it behave?**
Ideally, planned sprints should have a **fixed length** to promote consistency, and **its goal should not be tempered with** once it is decided or ongoing. Like if the first sprint were to span for two weeks, then the subsequent sprints should also be given two weeks duration. Also, it should have its own definition of what considered to be "done".

**What happens when a sprint cannot complete its agreed-upon duration?**
When a pressing matter comes, rather than altering the goal of a sprint, one may consider "aborting" it. It is an action that effectively terminate the ongoing sprint. There are three course of action should a sprint be terminated: 
1. Start the next sprint immidiately to address the matter, while using the rest of leftover duration
2. Regroup and reorganize for a moment, then wait until the agreed-start of the next sprint, and address the issue there
3. Make a "longer sprint" that encompasses the current leftover duration, plus the duration of the next sprint to make sure the matter is solved.

Now, to make sure that the next sprint is as productive as the terminated one, one can consider looking into the `Capacity` of the team. `Capacity` is the number of ideal hours available during the next sprint or iteration. It is a forecast on the amount of time that the team can work effectively on a given task. 

The table below are gotten from calculating the available effort hour amount for the TUKU app.

|	Name	|	Available day (Excl. personal time)	|	Days for other scrum activity	|	Available hour per day	|		Available effort hour	|
|----------|-------------------------------------------|--------------------------------------|------------------------------|--------------------|
|	Kevin Gunawan	|	5	|	3	|	5-8	|	10-16	|
|	Stevans Calvin Candra	|	5	|	3	|	5-8	|	10-16	|
|	Kelvin Giovanno	|	5	|	3	|	5-8	|	10-16	|
|	Yofadha Chandra Berliano	|	3	|	1	|	5-8	|	10-16	|
|		|		|		|	**Total**	|	40-64 hours	|

Sprint will adapt with the avaibility of each team member. In this case, a sprint will last for one week.

ㅤ

#### B.	Requirements
To be accepted, the application has to fulfill these criterias:
1. Be able to take in a pick-up request from customers.
2. Allow customers to track their packages.

ㅤ

#### C.	User Stories

`User Story` is an informal, often simple, explanation of a specific software feature, that is created from the end-user's perspective. It serves to describe **(a) what role does the user hold**; **(b) what do they want and why**; and **(c\) what are the benefits to them**.

Below are a collection of user stories related to the TUKU app that was created by Edot, the product owner.
 
|	No.	|	Assumed Role (As a)	|	Request	|	Benefits	|
|-------|---------------|-----------|---------------|
|	1.	|	Merchant that sells goods online	|	I want to place many pick-up request at once, and label each of them to indicate whether a given item fragile or not	|	So I can ensure my packages will arrive to its destination safely	|
|	2.	|	Customer who rarely or have never sent a package before	|	I want an onboarding guide on what’s the process like to get my packages inputed and delivered	|	So I can feel confident in knowing that I did everything right to ensure my packages get sent safelly.	|
|	3	|	Customer who's in an urgency	|	I want to be informed of any other existing shipment-plan, on which I can choose to get my packages sent faster; along with their price	|	So I can consider TUKU among other companies that have a faster/cheaper alternative.	|
|	4	|	Independent cook who sends food as a package 	|	I want to be able to schedule the pick-up time 	|	So I can prepare the goods beforehand	|
|	5	|	Typical Customer	|	I want to be informed of what the total fare's going to be	|	So I can prepare the exact amount to pay the courier-man when he arrives	|
|	6	|	Typical Customer	|	I want to see how the fare could be broken down	|	So I can reduce my spending if possible	|
|	7	|	Independent Contractor	|	I want to be able to cancel a pick-up request	|	So the courier-man won't have to waste a pick-up time	|
|	8	|	Typical Customer	|	I want the application to save my recent recipients	|	So I don't have to retype all of their details again	|
|	9	|	Typical Customer	|	I want to know updates related to (track) my packages	|	So I can prepare the time to recieve the package	|
|	10	|	Merchant that sells goods online	|	I want to track updates on my packages (deliveries)	|	So I can confirm whether or not they have been recieved by my customer	|
|	11	|	Typical Customer	|	I want somethig like a code-phrase, for which I can use to track  my packages	|	So I can simply remember it, rather than having to log in every time just to track my packages	|

ㅤ

#### D.	Product Backlog Items
Product backlog is a `giant`, `constantly-updated`, `"To Do" list` of all the features, functions, and improvements that are ***planned*** for a product. It can be seen as a large pool of "tasks", controlled by the product owner, revised as the development process went, and influenced by the state of the market.

Below are the `Product Backlog` for TUKU app:

|	User Story No.	|	Acceptance Criteria	|	Story Point Estimation	|	Priority	|	Type	|
|-------------------|-----------------------|---------------------------|---------------|---------|
|	1	|	Application has to be able to make a pick-up request	|	8 points	| Highest	|	Fundamental Feature
|	9 & 10	|	Customers have to be able to track their packages from within the app	|	8 points	| High	|	Feature
|	4	|	Customer have to be able to choose between the available pick-up time for their pick-up request	|	1 point	|	High	|	Feature
|	5 & 6	|	Each pick-up request has to be able to show its fare, and how it is broken down	|	1 point	| High	|	Feature
|	1	|	In making a pick-up request, Customer has to be able to mark their packages as fragile or some other type: such as documents, foods, clothes, etc.	|	1 point	|	High	|	Feature
|	3	|	Customers have to be able to choose between mutiple shipment plan available	|	3 points	|	Medium	|	Feature
|	7	|	Pick-up request has to be cancel-able	|	3 points	|	Medium	|	Feature
|	1	|	Application are to be made to handle multiple pick-up request creation	|	2 points	|	Medium	|	Feature
|	11	|	Application can accept a code-phrase, that lets user to track the associated package's status	|	1 point	|	Low	|	Feature
|	2	|	Application has to have an onboarding screen that tutors people using it	|	2 points	|	Low	|	Feature
|	8	|	Application can save recent senders/recipients name & details	|	2 points	|	Lowest	|	Non-essential Feature
|	---	|	**Total**	|	32 points

ㅤ

### III.	SCRUM Roles

There are many roles to be assumed by someone in SCRUM. Ranging from the final decider (Product Owner), influencer (Stakeholders), the one building the application (The Development Team), and many more. In TUKU's context, the following table will suffice:

|	Name	|	Role	|
|-----------|-----------|
|	Edot	|	Product Owner	|
|	Kevin Gunawan	|	Scrum Master	|
|	Stevans Calvin Candra	|	Developer in the Development Team	|
|	Kelvin Giovanno	|	Developer in the Development Team	|
|	Yofadha Chandra Berliano	|	Developer in the Development Team	|

ㅤ

### IV.	Sprint Planning

`Sprint Planning` is the event that kicks off a sprint. It **defines the scope & focus of a sprint**, and **how do you achieve it**. While planning, it is important to estimate the team's capacity correctly. The scope of a sprint is usually sourced from the Product Backlog; with those that have the highest priority level gets chosen (assuming that the Product Backlog Item has been sorted accordingly; from the most to least).

The following plan assumed that each sprint has 100% completion rate (meaning that there are no termination nor any unfinished job leftover from the last sprint).

#### Sprint 1


*OBJECTIVE*
Try to put together the very basic functionality for the TUKU app
\
*RELATED PBI*
- Application has to be able to make a pick-up request
- Customer have to be able to choose between the available pick-up time for their pick-up request
- Each pick-up request has to be able to show its fare, and how its broken down

*DEFINITION OF DONE*
- Application is able to make a pick-up request; albeit only able to take in the most fundamental information.
- Application is able to estimate the shipping fare with limited information available
- Application is able to show the detail behind the price calculation in presentable manner

*BACKLOG*
- Sketch the initial interface to place a pick-up request, with consideration towards:
   - Package type (fragile/food/etc.), and
   - Available pick-up time.
- Code the interface, with the sketch as reference.
- Make a function to calculate the shipping fare.

#### Sprint 2
*OBJECTIVE*
Expand the functionality of TUKU app

*RELATED PBI*
- Customers have to be able to choose between mutiple shipment plan available
- Application are to be made to handle multiple pick-up request creation

*DEFINITION OF DONE*
- Customer is able to choose their preferred shipping speed for each pick-up request made using the application.
- Application can enable the user to place multiple pick-up request

*BACKLOG*
- Improve the interface from previous sprint, so that the application can place multiple pick-up request.
- Add a feture to the interface, to allow users to switch to a different shipping plan, while considering to:
	- Display what benefit does each plan offer, and
	- Display the fare differences between the plan.


#### Sprint 3
*OBJECTIVE*
Implement package tracking to the TUKU app.

*RELATED PBI*
- Customers have to be able to track their packages from within the app
- Application can accept a code-phrase, that lets user to track the associated package’s status

*DEFINITION OF DONE*
- Mobile application can accept a code-phrase, that is used in contacting the web application to fetch a package's status or whereabouts.
- Application can display those fetched data in a presentable manner:
	- Where the package is currently at (try pin-pointing it using a map)
	- Estimated time of arrival

*BACKLOG*
- Make a function that recieves the unique identifier returned from the web application, whenever it posted a new pick-up request that the user made.
- Make an interface that lets the user to input those unique identifier.
- Make a function that fetches a package data, which is determined by the unique identifier inputted by the user.
- Make an interface that displays those fetched package data.

#### Sprint 4
*OBJECTIVE*
Expand the accessibility of the TUKU app.

*RELATED PBI*
- Application has to have an onboarding screen that tutors people using it
- Application can save recent senders/recipients name & details

*DEFINITION OF DONE*
- Application has a new onboarding screen
- Application is able to write down a list of recent sender/recipient details, and lets user to select from it

*BACKLOG*
- Make an onboarding screen that’s visible when accessing the app for the first time, or when the tutorial button gets pressed. The onboarding screen should:
	- Display what’s the process to make a pick-up request:
		- Determine what is the formal process (intended flow)
	- Accessible with a click of a button
- Make a function that saves the recent recipient/sender details temporarily
- Make a function that lets user to select "which recipient do they wish to send to" based on the list written by other function, and pre-fill it into the appropriate textbox.

ㅤ

### V.	Sprint Execution

While executing the planned sprint above, there are several activity that occurs [in each planned sprint above] when proper agile principle are being followed. Those are:

#### 1.	Daily Scrum
The Development Team, along with Scrum Master will conduct a quick briefing (usually in the morning) everyday, to discuss several important matter. The spoken topics will most often be:

- What have been accomplished yesterday?
- What to be done today?
- What obstacle is hindering the progress?

Even though the presence of Product Owner is not needed nor required, it is considered a good thing to keep the final decider within the loop.

When executing the **first sprint** in its daily scrum, the software division at TUKU noted the following:
```
Day 1 _____________________________________________________

Yesterday: 
   - undefined.

Today's tasks:
   - make a skeleton interface to place a pick-up request, considering the ability to input package type (fragile/food/etc.) and choose between available pick-up times
   - designate the initial function/controller/interface as the definitive reference for coding practices
   - start working and asking the relevant individual in charge of the function to calculate the shipping fare

Challenge/blocker: 
   - undefined.

Day 2 _____________________________________________________

Yesterday:
   - make a skeleton interface to place a pick-up request, considering the ability to input package type (fragile/food/etc.) and choose between available pick-up times
   - designate the initial function/controller/interface as the definitive reference for coding practices
   - start working and asking the relevant individual in charge of the function to calculate the shipping fare 

Today's tasks:
   - refine and enhance the visual aesthetics of the user interface.
   - continue working on the function to calculate the shipping fare

Challenge/blocker: 
   - undefined.

Day 3 _____________________________________________________

Yesterday:
   - refine and enhance the visual aesthetics of the user interface.
   - continue working on the function to calculate the shipping fare

Today's tasks:
   - finalize and test the function to calculate the shipping fare

Challenge/blocker: 
   - undefined.

Day 4 _____________________________________________________

Yesterday:
   - finalize and test the function to calculate the shipping fare

Today's tasks:
   - continue finalize and test the function to calculate the shipping fare

Challenge/blocker: 
   - yesterday, an issue occurred on the server which resulted in the app experiencing an "unusual" bug.


<!-- End of note -->
```

#### 2.	The “ToDo” Board

A Sprint Backlog holds many key points that needed to be done within a sprint. However, it does not specify the required actions to finish each backlog.  Therefore, there needs to be a “ToDo” board, on which the team members can break a sprint backlog down into little steps, that ultimately accomplish the backlog on the bigger picture.

Example of updating the “ToDo” board in day 2 of the first sprint:
- Add an element to capture the pick-up location
- Add an element to capture the pick-up time
- Add an element to capture the type of package
- Add a function where it calculates the end fare
- Add a validation function for the captured information

#### 3.	Sprint Review

At the closing mark for each sprint, the team will be doing a Sprint Review. This activity have several purpose, that being:

- To inspect “what good the sprint brings to the product”,
- To demonstrate “what work got accomplished”, and
- To gather feedback from stakeholders.

Below are things that typically happen during a sprint review:

- Product Backlog Refinement/Grooming
\
Once a sprint gets a backlog item done or two, it usually is a good idea to refine the Product Backlog based on the insights recieved during the sprint.

- Sprint Goals Review
\
The team need to discuss: whether the sprint that they’re on have accomplished all their goals. If not, then this activity serve to raise awareness that something did not go according to plan, and has to be revisited again sometime in the future (probably in the next sprint planning activity).

#### 4.	Sprint Retrospective

This activity occur during the closing mark of a sprint, and right after the Sprint Review. Its main purpose is to allow for the team to reflect on their previous sprint, and identify in which case can they improve on. Generally, when they find an activity worth improving, they’re going to plan things differently.

The difference between a Sprint Review and a Sprint Retrospective is that Review focuses on the product – while Retrospective focuses on the sprint process itself.

