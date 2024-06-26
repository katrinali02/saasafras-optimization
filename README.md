# SaaSafras Ops Optimization

Planterbox Inc, a plant care software business, just acquired a regional plant care operator named SaaSafras based in the Southeastern US. 

SaaSafras’ business has been stable with some organic growth and some natural churn. Planterbox has identified you as a rising star within the org and you’ve been hand picked to run the newly acquired business after the previous CEO of SaaSafras retired and sold their business. You’re excited for the opportunity and your first project is to figure out how you can grow SaaSafras’ revenue (Planterbox decided they loved the name too much, even though they acquired the company they’ll keep the SaaSafras name). 

As part of the acquisition, you’ve inherited 20 great people who can do it all between sales, account management and support. Unfortunately, doing it all has come at a cost and productivity has been lower than if they had specialized in any of the individual roles (and they are begging for specialization as well). Going forward each person will only perform one core role at a time. While each person will only perform one role at a time they can switch to another role at the start of any month - one person could cycle through every job without a loss in productivity.

Your goal is to maximize SaaSafras’ cumulative revenue over the next 24 months (the sum of all revenue generated over 24 months).Your responsibility is to determine where these 20 people will work each month for the next 24 months to maximize the cumulative revenue generated over the entire period.

The three roles are:
New Business Acquisition
These people are responsible for selling and getting new customers in the door
Account Management
These people help existing customers; they drive revenue growth from the customers they work with and improve retention
Support
These people solve customer problems; they improve retention for any active customer

SaaSafras has some key metrics that won’t change with the acquisition. The business currently has 1,000 customers. SaaSafras acquires 25 customers a month organically through great branding and customer referrals. Some customers turn to other, more specialized solutions and monthly churn is 10%. There has been a standalone support org in addition to your swiss army knife team, and support’s CSAT (Customer Satisfaction) has been steady at 70% for several years. SaaSafras doesn’t offer any discounts and every active customer pays a baseline fee of $100 a month for the core product. 

Team specifics are below:

Each New Business Acquisition team member can acquire 5 new customers a month.

Account Managers increase revenue by 20% month-over-month for accounts they manage up to a cap of 6 months. To be clear, this revenue increase compounds by 20% each month up to the 6th month, at which point it maxes out and remains flat for the remaining duration of time that the customer has an account manager (for example, if a customer has an account manager in month 1 they’ll pay $120, in month 2 they’ll pay $144, etc). If a customer has an account manager and then loses the account manager their metrics (revenue per month) return to the baseline, but there isn’t a negative consequence. Each Account Manager can carry 25 customers.

Each support agent increases CSAT by 1 percentage point. Each point of CSAT leads to a 15% relative decrease in churn, with a compounding effect (the next CSAT point decreases 15% of 85%, etc.).

SaaSafras needs you to make 3 key decisions:
How many people will work on acquiring new business, account management, and support each month from month 1 to month 24? 
Why are they working there? 
We care about your understanding of the why behind your decisions just as much as we care about the actual decision, so please explain your reasoning, not just the conclusion (i.e. don’t rely too much on solver / other tools).
Bonus: If you had a magic wand, what is the one variable you would try to improve going into year 3? How would you approach moving that variable?
By “variable” here, we mean one of your team members core metrics (customer acquisition, CSAT, revenue increase, relative churn decrease etc).

