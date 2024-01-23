# 🌀 Hack for Impact (Berkeley, 2024)

Here's everything hackers at Hack for Impact need to know about The Hack Foundation &amp; HCB.

We give nonprofits the financial tools they need to make an impact and maintain transparent finances.  

The Hack Foundation provides fiscal sponsorship through a custom-built platform called HCB ([https://hackclub.com/hcb](https://hackclub.com/hcb)). On HCB, organisations can raise money through invoices, donations, bank transfers etc. and then spend it using cards we issue. 

At the core of it, we’re a nonprofit that builds software! There’s about a half a dozen engineers working on HCB at the moment; @sampoder is one of them, he’s a student here at Berkeley / Cal Hacks organiser and is at Hack for Impact today so give him a shout if you need any help. At the moment, we’re working towards open sourcing the entire platform. Thus far, [we’ve open sourced small pieces of it](https://github.com/hackclub/?q=hcb&type=all&language=&sort=). We hope to soon open source the main Ruby on Rails codebase.

We have an API for hackers to use public data in their projects: [https://hcb.hackclub.com/docs/api/v3/](https://hcb.hackclub.com/docs/api/v3/).

**Problem Statements**

***1) Data visualisation of transparent organisations***

**Problem statement:** something (it could be a web app or it could be something totally different, get creative!) that provides you with a visual breakdown of how an organisation spent the money they’ve raised.

**Background:** on HCB, an organisation can choose to make their finances publicly available through Transparency Mode. These finances can then be accessed through the API.

**Goal:** reading a long list of transactions is time consuming, a user should be able to get a rough understanding of an organisation’s finances in a few minutes using your product.

**Key features:** changes to an organisation’s account balance overtime, categorised spending using tags, spending by user.

**Stuck?** Here are some ideas to get you started: what are some novel formats you could use? What if you programmed a video using Remotion? What would a GitHub commit graph look like if it was for a nonprofit’s finances?

***2) Budgeting tool for events that is transparent***

**Problem statement:** a tool that allows organisations to create a budget and then open-source it. Similar to how organisations can open source their spending using HCB, it’d be nice for them to be able to open source their budget.

**Background:** a lot of hackathons are organised using HCB. These hackathons like to open source their budgets (eg. Lion City Hacks & Assemble), however, the best tool they have at the moment to do that is Google Sheets.

**Goal:** teams should be able to collaborate on budget and then have a public view of that budget. A stretch goal would be an integration with HCB’s API.

**Key features:** assigning amounts to spending categories, having sub categories, and having charts that visualise the budget.

***3) Machine learning to tag transactions.***

**Problem statement:** a machine learning model that can suggest tags for a transaction based on its memo and any other information available from the API.

**Background:** on HCB, users can add tags to transactions. However, for large organisations this can take a lot of time. 

**Goal:** speed up the process of transaction tagging by having suggested tags there for users. 

**Key features:** ideally any solution would be implemented in Ruby but we’re flexible so use what’s most comfortable to you!

***4) Open Ended***

Got a project in mind related to the HCB API or financial transparency? We’d love to see it come to life! Feel free to venture outside of our three problem statements. Scratch that… you’re encouraged to do something different. 
