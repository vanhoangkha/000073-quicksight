---
title : "Line chart"
date: 2024-01-01
weight : 2
chapter : false
pre : " <b> 3.2 </b> "
---

#### Line chart:
In this step, we'll create a line chart using the autograph feature, and try adding predictive metrics using QuickSight's Forecast feature.

#### Content
- [Line chart:](#line-chart)
- [Content](#content)
- [Sales chart by month](#sales-chart-by-month)
- [Add future prediction data](#add-future-prediction-data)

#### Sales chart by month

1. In the Fields list, select **Sales** then **Order Date**.
  - We will see the autograph chart automatically generates the total Sales chart by day.

![AWS](/images/2/1.2-5a.png?featherlight=false&width=90pc)

2. Select the arrow next to **Order Date** > **Aggregate: Day** > **Month** to convert the unit to months.
 
![AWS](/images/2/1.2-5b.png?featherlight=false&width=90pc)

3. We will see the chart converted to total **Sales** by month as shown below.

![AWS](/images/2/1.2-5c.png?featherlight=false&width=90pc)

#### Add future prediction data

Predictions are generated from datasets and QuickSight's Machine Learning model. Take the following steps to apply predictions to the chart:

1. Make sure your chart is active by clicking inside the chart.
  - Click the **...** icon in the right corner of the chart, and select **Add Forecast**.

![AWS](/images/2/1.2-6a.png?featherlight=false&width=90pc)

2. In the **Periods backward** section, enter **6**.
  + Click **Apply**.
  + The prediction line shows the data from 6 months ago so that we can compare it with the actual data in the Dataset.

![AWS](/images/2/1.2-6b.png?featherlight=false&width=90pc)

3. We can hover over the line chart to check the Forecast value and the actual value.

![AWS](/images/2/1.2-6c.png?featherlight=false&width=90pc)

Next, we will create a KPI chart and use QuickSight's Insights feature.