# Revenue Charts<a name="analytics-revenue"></a>

The charts and metrics on the **Revenue** page provide details about user purchase activity and the revenue that's generated by your app\.

**Note**  
Some of the charts and metrics on the **Revenue** page refer to *endpoints*, while others refer to *users*\. For information about the difference between users and endpoints, see [Endpoints and Users in Amazon Pinpoint Analytics](analytics-charts.md#analytics-endpoints-users)\.

## Viewing the Revenue Charts<a name="analytics-revenue-view"></a>

Complete the following steps to view the **Revenue** charts and metrics on the Amazon Pinpoint console\. You can filter the data by date and by endpoint attributes\.

**To view and filter the Revenue charts and metrics**

1. Open the Amazon Pinpoint console at [https://console\.aws\.amazon\.com/pinpoint/](https://console.aws.amazon.com/pinpoint/)\.

1. On the **All projects** page, choose the project that you want to view revenue data for\.

1. In the navigation pane, under **Analytics**, choose **Revenue**\.

1. \(Optional\) To apply a filter that displays the data for a specific date or range of dates, use the date selector at the top of the page to choose the dates for the time period that you want\. After you choose new dates, the page updates to show the data for the selected time period\.

1. \(Optional\) To apply a filter that displays data for only those endpoints that have specific attributes, expand the **Filters** section\. Then choose an attribute from the **Endpoint Attributes** list\. After you choose an attribute, choose an attribute value from the **Endpoint Attribute Values** list\.
**Note**  
To provide you with the best possible experience, we hide this filter if you haven't used it in the past 90 days\.  
If the **Filters** section shows a message stating that the filter is unavailable, choose **More information**, and then choose **Enable filters**\. When you do, we restore the filter for your account in the current AWS Region\. Depending on the amount of data that's associated with your account, this process can take up to 72 hours to complete\.

   To further filter the data, repeat this step for each additional attribute and attribute value that you want to filter the data by\.

## Chart Descriptions<a name="analytics-revenue-description"></a>

The **Revenue** page contains the following sections:

**Revenue**  
Shows the amount of money, in USD, spent within your app by all users for each day in the selected time period\. This chart also provides the average amount of revenue that was generated by the app for the entire time period, and the percentage change in the amount of revenue from the beginning to the end of the time period\.

**Revenue per endpoint**  
Shows the average amount of money that was spent within your app by each endpoint for each day in the selected time period\. Amazon Pinpoint calculates this number by dividing the amount of revenue generated during the selected time period by the number of users who opened the app in that time period\. This chart also provides the average amount of revenue per endpoint for the entire time period, and the percentage change in the amount of revenue per endpoint from the beginning to the end of the time period\.

**Paying users**  
Shows the number of unique users who made at least one purchase for each day in the selected time period\. This chart also provides the total number of paying users, the average number of paying users, and the percentage change in the number of paying users from the beginning to the end of the time period\.

**Revenue per paying user**  
Shows the amount of money that was spent by each paying user\. Amazon Pinpoint calculates this number by dividing the amount of revenue generated each day in the selected time period by the number of unique users who made at least one purchase during that day\. This chart also provides the average amount of revenue per paying user for the entire time period, and the percentage change in the amount of revenue per paying user from the beginning to the end of the time period\.

**Units sold**  
Shows the total number of items that were purchased in your app for each day in the selected time period\. This chart also provides the total number of units sold, the average number of units sold per day, and the percentage change in the number of units sold from the beginning to the end of the analysis period\.

**Units sold per endpoint**  
Shows the daily average number of items that were purchased by each endpoint\. Amazon Pinpoint calculates this number by dividing the number of units sold each day by the number of endpoints that were active during the selected time period\. This chart also provides the average number of units that were sold per endpoint for the entire time period, and the percentage change in the number of units sold per endpoint from the beginning to the end of the analysis period\.

**Purchases**  
Shows the number of purchases that were made in your app for each day in the selected time period\. This chart also provides the total number of purchases made in the time period, and the percentage change in the number of purchases from the beginning to the end of the analysis period\.

**Purchases per endpoint**  
Shows the daily average number of purchases per endpoint for each day in the selected time period\. Amazon Pinpoint calculates this number by dividing **Purchases** by the number of endpoints that made a purchase for each day in the analysis period\. This chart also provides the average number of purchases per endpoint for the entire time period, and the percentage change in the number of units sold per endpoint from the beginning to the end of the analysis period\.