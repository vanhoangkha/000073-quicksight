---
title : "Additional charts"
date: 2024-01-01
weight : 2
chapter : false
pre : " <b> 4.2 </b> "
---


### Content
- [+++](#)
- [pre : " <b> 4.1 </b> "](#pre---b-41-b-)
  - [Content](#content)
    - [Sankey chart](#chart-sankey)
    - [Sales Map](#map-sales)

#### Sankey chart

1. In the right corner, select **Add** > **Add visual**.
2. At the bottom right corner of Visual types, select **Sankey Diagram**.
3. In the Fiels list, select **Region**, and **Sales**.
4. Rename the chart to `Sales Sankey`.

![AWS](/images/3/1.3-4a.png?featherlight=false&width=90pc)

#### Sales Map
1. In the right corner, select **Add** > **Add visual**.
2. At the bottom right corner of Visual types, select **Points on map**.
3. In the Fields list, select **Country**, and **Sales**.
4. Rename the chart to Sales by Country.

![AWS](/images/3/1.3-5a.png?featherlight=false&width=90pc)

5. Select the gear icon in the right corner of the chart, select **Tooltip**, change the type to **Detailed tooltip**, and select **Add field**.

![AWS](/images/3/1.3-6a.png?featherlight=false&width=90pc)

6. In the Field section, select **Contact Name**; Label entry - enter `# of Users`; Displayed value - select **Count distinct**.

7. Select **Save** to apply.

![AWS](/images/3/1.3-6b.png?featherlight=false&width=90pc)

8. Now, when you hover over the country you want to see, you can see the number of customers in each country.

![AWS](/images/3/1.3-6c.png?featherlight=false&width=90pc)