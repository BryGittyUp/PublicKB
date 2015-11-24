{{{
  "title": "Pricing, Billing and Invoicing for Partners",
  "date": "2-11-2015",
  "author": "",
  "attachments": [
    {
      "url":"../attachments/sample-end-user-report.csv",
      "type":"application/csv",
      "file_name":"sample-end-user-report.csv"
    }
  ],
  "contentIsHTML": false
}}}

### Overview
* How pricing and discount data are displayed in the portal.
* Invoicing customers and special pricing scenarios.
* Getting billing data and the schedule for receiving billing reports.

### The Basics of Pricing and Discounts

#### Cloud Portal Pricing

By default, prices in the Cloud Portal are displayed at list price unless the Partner changes them using the 'Set Your Own Price' functionality.  Either way, the customer **never** sees the partner’s discounted price.

#### CenturyLink Invoice to Partner

When you receive the invoice from CenturyLink, your contracted discount will be applied.  This is the  amount that the Partner needs to remit to CenturyLink.

### Invoicing Customers and Special Pricing

#### Partner Invoice to Customer

As a partner, you are responsible for invoicing your customers. The below information describes how to get detailed billing data for your customers.

### Getting Billing Data and Reports
On a monthly basis, in addition to receiving your invoice from CenturyLink, you will receive an End User Report to assist you in billing your end customers.  The End User Report details subaccount usage for the previous month and the total charges based upon the pricing in the portal.  As an alternative, you can leverage the API to automatically pull billing data. 

####Billing Report
**How It Works:** CenturyLink will email a report with the previous month’s billing data in .CSV format to an email alias of your choice.  Use this data to invoice your customers.
**Timing:** Report is sent by the 2nd business day of the month.
**About The Report:** The report is broken out by account and prices displayed are at list price.
**Sample Billing Report:** See the attachment at the bottom of this article.

####API Integration (Optional)
**How It Works:** You can integrate with CenturyLink Cloud’s APIs to pull billing data automatically.
**Resources:** Find out more about these capabilities at the following link: https://www.ctl.io/api-docs/v1/#billing

#### Special Pricing Scenarios – Customer Discount
If you choose to extent a discount to your customer, there are two ways to accomplish this. 

**Customer Discount at Time of Invoice**

You can extend a discount to your customer at the time of invoice. Simply communicate to your customer that prices displayed in the CenturyLink Cloud Portal are at list price; their invoice will reflect their discount. Note: This discount is not reflected in the End User Report, therefore you will apply the discount on top of that amount. 

**Set Your Own Price Functionality**

The Set Your Own Price (SYOP) Functionality allows the partner to adjust the prices that customers (subaccounts) see in the portal.  This change will also be carried through to the 'End User Report'. Note: it does not change however what CenturyLink will charge the Partner.  Partners will still be charged their agreed percentage off list prices.

To use this feature, the user must have the Account Admin or Billing Manager roles for your account in the portal.  In addition, only a parent account can adjust prices.  A sub-account cannot change its own prices.

It's also important to remember that there is no mid-month pricing.  If you change a price using the SYOP functionality, it will affect the entire month.

For complete instructions on the SYOP process to set prices, navigate to:
 https://www.ctl.io/knowledge-base/general/setting-prices-for-sub-accounts/ 
https://www.ctl.io/knowledge-base/general/set-your-own-price-faq/
Note: We are also happy to walk you through this functionality, so please reach out to your CenturyLink contact.
