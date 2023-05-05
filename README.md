Download Link: https://assignmentchef.com/product/solved-database-queries
<br>
1. ISone is hiring. They need a way to track job applications. An interest candidate must submit an application. The candidate is known by an CandidateID, Name and PhoneNumber.

The candidate can only submit one application and only one application can be submitted by that candidate. An application is known by an ApplicationID and SubmissionDate. In addition, the application must include the candidates previous jobs (job title, companyname and years in the job).

Construct an ER diagram for this scenario. Be sure to include all elements of an ER diagram.

2. A database is needed to track and record the medals won at the Olympics. Gold, Silver and Bronze metals are awarded for each winner of the final competition of each sport.

Normalize the table in the accompanying image to 3NF:

Functional Dependencies:

AthleteNo -&gt; AthleteName, AthleteCountry, AthleteDOB,

SportID -&gt; SportName, SportType,

EventID -&gt; EventDate, EventTime,SportID

AthleteNo, EventID -&gt; SportName, SportType, EventDate, AthleteName, AthleteCountry, MedalWon