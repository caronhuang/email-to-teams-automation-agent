# email-to-teams automation agent
Parse email attachment, normalize the content, deduplicate items, and send structured Microsoft Teams reply using Adaptive Card

# Background
In my role as a quoter, I receive frequent quote requests. Each quote may contain multiple quote line items, which are stored and processed at the line-item level in our system. However, from a workflow and communication perspective, the key objective is not to track every line item, but to remind internal stakeholders to pay attention to outstanding quote numbers (quote #) that still require action. Reminders have been sent out by emails manually if without this agent.

This automation agent addresses that need by:

- Monitoring incoming quote-related emails
- Extracting quote line item data from attachments or email content
- Normalizing and aggregating the data
- Deduplicating quote numbers, ensuring each quote # appears only once

Automatically sending a clear reminder message to Microsoft Teams, prompting the relevant BU or stakeholders to review outstanding quotes

https://gamma.app/docs/Email-to-Teams-Automation-Agent-mz208bxp1n8jv6f
