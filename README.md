# Next Best Action
## Replacing JavaScript buttons and improving User Experience with Lightning features

Lightning is here and if you are still wondering how to get those older JavaScript buttons into Lightning while improving user experience, consider how Einstein Next Best Action, conditional page layouts and Flows can help.

A lot of JavaScript buttons were built to validate certain data conditions and then take action, perhaps redirecting users to a URL with parameters taken from the current record to prepopulate that new web page.

[Einstein Next Best Action](https://help.salesforce.com/articleView?id=nba_implementation_checklist.htm&type=5) can help. It is a Salesforce setup feature that recommends Actions (think Flows and Quick Actions here) based on a series of conditions and filters. Use it to present a Flow based on record type, user info, or other 'strategies' you define based on your business rules.

Next Best Action ties closely to Flow enabing us to build even more powerful logic for a defined strategy. 

Flow can be combined with reuseable Lightning components to direct users to an alternative web page using this [sample code from Salesforce.](https://github.com/snugsfbay/LightningFlowComponents/tree/master/flow_action_components/Summer18/LoadWebPage)

Of course, actions that appear and disappear from the screen only when they are valid may be confounding for users. We can improve this experience with a corresponding Next Best Action strategy to help users complete the data for the actions they need, or by adding a conditional page layout to help them with data completion via a Flow.

Keep a watch on this repository as I prepare to demo this technique in an upcoming [Automation Hour webinar on October 4, 2019.](http://bit.ly/BHinners100419)

The sample is built on three Trailhead Badges: 

[API Callouts ...](https://trailhead.salesforce.com/en/content/learn/modules/apex_integration_services/apex_integration_rest_callouts)

[Bear Warning ...](https://trailhead.salesforce.com/en/content/learn/projects/workshop-platform-events/platform-event-subscribe)

[Manage Products ...](https://trailhead.salesforce.com/en/content/learn/projects/manage-products-prices-quotes-orders)
