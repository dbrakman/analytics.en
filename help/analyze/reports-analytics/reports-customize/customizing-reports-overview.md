---
description: After running a report, you can customize the report to view and analyze the data according to your needs. You can filter report data, change how data is presented graphically, change date granularity, and so on.
title: Customize reports overview
uuid: 37d221b7-50fd-4425-b2ba-f40911b72a2f
feature: Reports & Analytics Basics
role: User, Admin
exl-id: 5a042fac-926e-4560-83bf-11f66ddb8273
---
# Customize reports

After running a report, you can customize the report to view and analyze the data according to your needs. You can filter report data, change how data is presented graphically, change date granularity, and so on.

## Select a date or date range {#task_9BEF7D4D839A4748B76E8500D1406C34}

You can choose the time periods for your report data.

<!-- 

t_reports_select_date.xml

 -->

You can select specific days, weeks, months, or years. You can also run comparison reports.

When you open a dashboard with reportlets that have different date ranges, you can choose a new date range in the calendar. The changes apply to all reportlets in the dashboard.

To select a date range: 

1. Run a report.
1. Click the calendar icon on the top right.
1. Select a date.

   You can:

    * View days, months, or year periods (up to three).
    * Drag your cursor across dates to select a range.
    * Enter dates manually.
    * Click a month name to select a month.
    * Click **[!UICONTROL Select Preset]** to select a preset date.
    * Compare dates.

1. Click **[!UICONTROL Run Report]**.

## Compare dates {#task_95155C3700774B709F5FB81AE96B0824}

You can use the calendar to run date comparisons between ranked reports.

<!-- 

t_reports_comparing_dates.xml

 -->

You cannot compare dates between trended reports.

>[!NOTE]
>
>If you want to perform a date comparison on key metrics in a dashboard, you can pull the data into [Report Builder](https://experienceleague.adobe.com/docs/analytics/analyze/report-builder/home.html) using two separate requests. You then use custom formulas in Excel to analyze the difference between the two.

<!-- delete this procedure, but what about this entire "Compare dates" section?

To compare dates between ranked reports in Reports & analytics: 

1. Run a report.
1. Click the calendar at the top right.
1. Click **[!UICONTROL Compare Dates]**.
1. Select the dates you want to use.
1. Click **[!UICONTROL Run Report]**.

-->

## Display a percent as a graph {#task_BC28CA19A4834AF6BFE68B5B5AEFE75D}

You can specify whether to display the percent in a report table as a graph.

<!-- 

t_reports_graph_percent.xml

 -->

This visualization is available also in dashboard reportlets.

To display the percent as a graph in a report table:

1. Run a report that supports percentages, such as a [!UICONTROL Pages Report].
1. Click **[!UICONTROL Percent Shown As: Graph]**.

## Normalize report data {#task_8005B55E59BD479DA67BC618FF8BC94A}

<!-- 

t_reports_normalize.xml

 -->

After you run a report with compared dates, or for A/B comparisons, you can normalize the data to show the percent of change between the reports. The secondary data set is adjusted to compensate for differences in the number of selected days, or for different volumes of traffic.

To normalize report data:

1. Run a report that supports date comparisons.
1. Click **[!UICONTROL Compare Dates]**, then specify your date comparison.
1. Click **[!UICONTROL Run Report]**.
1. Click **[!UICONTROL Normalize Data: Yes]**.

## Select a page for a report {#task_5CAC3B76BD4C4208B8D53DD972D4771F}

To select a specific page from the pages of your website for a report:

<!-- 

t_reports_select_page.xml

 -->

1. Generate a report, such as a [!UICONTROL Page Views Report] ( **[!UICONTROL Reports]** > **[!UICONTROL Site Metrics]** > **[!UICONTROL Page Views]**).
1. Click the **[!UICONTROL Selected Page]** link.
1. On [!UICONTROL Choose Page], select the pages you want to display.
1. Locate the page.
1. Click **[!UICONTROL OK.]**

## Compare report suites {#task_6BEBEB2D4F36497C9DA5B18ADAD35546}

You can display reports from two report suites in the same report.

<!-- 

t_reports_compare_suites.xml

 -->

In addition to the graphical display, the table of the report gives you a percentage comparison. The following reports can be run with comparisons:

* Site Content 
* Mobile 
* Traffic Sources 
* Campaigns 
* Products 
* Visitor Retention 
* Visitor Profile 
* Custom Conversion 
* Custom Traffic 
* Target 
* Survey

To compare report suites: 

1. Generate a report that allows you to compare reports.
1. Click the **[!UICONTROL Compare to Site]** link.
1. Locate the report suite.
1. Click **[!UICONTROL OK.]**

## Specify report granularity {#task_7ED3EEC9E1704A918B25D06ADA3412E0}

You can view report totals on an hourly, daily, weekly, monthly, quarterly, or yearly basis.

<!-- 

t_reports_granularity.xml

 -->

The report's time period determines which granularity options are available. For example, you can select only **[!UICONTROL Hourly]** if you have a one or two day time frame selected. You can select only **[!UICONTROL Yearly]** granularity if you have more than one year selected.

To specify report granularity:

1. Generate a trended report, such as **[!UICONTROL Site Content]** > **[!UICONTROL Pages.]**
1. Click the **[!UICONTROL View by]** link, then click a granularity.

## Run a day-of-week report {#task_67CC818ACC3749839B69BDB2ED9AE6B8}

You can run reports on a specific day of the week, such as over each Monday in a given date range.

<!-- 

t_reports_day_of_week.xml

 -->

This feature applies only to trended reports filtered with a date range of Week or Day.

To run a day-of-week report:

1. Run a trended report over a specified date range.
1. Click the **[!UICONTROL Day of Week]** link, then click a day.
