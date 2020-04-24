# Apr 24, 2020
# Labs-Sprint-Challenge-2.3-Accountability-and-Delivery

This challenge allows you to practice the concepts and techniques learned over the past week and apply them by providing answers to questions related to working with others of your Labs product.

In your challenge this week, you will demonstrate understanding over these topics by responding to prompts.

## Instructions

Read these instructions carefully. Understand exactly what is expected before starting this Journal Entry.

You are not allowed to collaborate during the Journal Entry. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in being able to adapt to changes that approach you during Labs.

We have allocated time on your schedule to ensure that you get this done at the end of each sprint.

For Full Time Students: Please submit your work on this journal entry before 11am PT every Friday.
For Part Time Students: Please submit your work on this journal entry before the end of your B-Week Thursday class period.

## Introduction

Now that you have been down in the thick of the Labs process for a while, we want to hear how you've come to a few conclusions and dealt with requirements changing throughout your delivery process.

Any time that you've deviated from your original plan, as documented in your release canvas, we want you to tell us about why you pivoted from the plan which you agreed upon as a team.

**Please respond to the following prompt to detail out the reasons your team pivoted away from the plan upon which you agreed as a team.**

### Prompt 1

As you have now been in the process of delivering and building your product, we'd like to know what has changed along the way:

#### Describe how the requirements of the features you have been building/designing have changed.
After talking to Austin, we finally cut the 12 forms to 3 forms, drastically deviating the app flow and design from the flow provided by the UX team. We also briefly deviated when our apollo server wouldn't cooperate with us. After talking it over and divising a plan as to how we would roll back to regular REST, we realised that we have to create our tables from scratch and deal with the relations of each table, and it's alot of data. Thats one of the reasons why we stuck with apollo and prisma. We have been getting assistance from Bernie who was so gracious enough with alot of the debugging. We were also stuck on testing, and when we got them to be successfully passing we realised that we had to deal with Coldclimate criteria. 
#### What caused these requirements to change?
We had to cut down alot of our code to improve our score to the D, and with the way things were going, we felt that we would have had to cut down essential code to improve our code, but that would interfere with our first 2 release canvas criterias. 
- **Engineering Students:** What types of architectural requirements changed? Did you have to make any trade-offs or add any new packages/libraries or dependencies to your application's technical stack in order to meet the new changes? **Please be as specific as you can. Provide details via screenshots to Trello cards or your release canvases to support your response.**
For both the frontend and backend we were struggling with testing since we were using Jest and react testing library. I know on my end when I was testing the components, useParams error kept creeping up mostly because of Graphql, so I've been spending about 2 days refactoring it to get it to be accepted. Then we Coldclimate criteria came in place, and it forced us to start refactoring most of our code to the point we found ourselves removing tiny features (not entirely mentioned on our release canvas, but features that would have enhanced our app overall) just to get the coldclimate score to improve. We almost had a meltdown that we had to cut down essential code in some other files, until Bernie and his team provided an update to the codeclimate criteria, which shot our score up from a D to an A 

<img height="300px" src="https://github.com/ebisLab/Labs-Sprint-Challenge-2.3-Accountability-and-Delivery/blob/master/Screen%20Shot%202020-04-24%20at%2011.46.59%20AM.png"> <img height="300px" src="https://github.com/ebisLab/Labs-Sprint-Challenge-2.3-Accountability-and-Delivery/blob/master/Screen%20Shot%202020-04-24%20at%2011.46.59%20AM.png">

https://www.notion.so/e9858304e56341a688cab689992a28c7?v=d7ffe101269d4b6d93116689793e40cb&p=4120c382d91247f8a879331af3918302


- **UX Students:** Describe any design patterns or user flows that had to change as a result of the requirements above. **Please be as specific as you can. Provide details via screenshots to design files or your release canvases to support your response.**
- **Data Scientists:** Tell us about how your work has evolved from the beginning stages of finding and cleaning the data with which your team is working all the way down to delivering that data model through your project's data pipeline. **Please be as specific as you can. Provide details via screenshots to Trello cards, Python/Jypyter Notebooks or your release canvases to support your response.**

## Submitting your work

Please submit a link to your journal entry for this sprint, in the Sprint Retrospective Form. This is to be done every _Friday before 11am PT_ -- for Full Time -- and before the end of your 2nd '5th' day -- for Part Time -- to be counted as a submission for that sprint.

## Rubric & Samples

[Here is a link to the rubric](https://www.notion.so/lambdaschool/2-3-Rubric-Accountability-and-Delivery-Diff-Entry-a35bcf0776194cdbba1c849007860b46) that will be used to assess your answers to the prompts. _Use this as a guide_ as you craft your responses.

[Here is a link to a sample submission](https://www.notion.so/lambdaschool/2-3-Accountability-and-Delivery-Diff-Entry-4dc1dbb2b1164b74849cd065adf8e209) that you can use for inspiration.
