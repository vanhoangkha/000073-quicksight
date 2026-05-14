---
title : "Pie chart"
date: 2024-01-01
weight : 4
chapter : false
pre : " <b> 3.4 </b> "
---

### Content
- [Content](#content)
  - [Create a chart](#create-a-chart)
- [Add Drill-down Layer](#add-drill-down-layer)
- [More details](#more-details)
- [Filter dashboard-wide data by optional industry](#filter-dashboard-wide-data-by-optional-industry)

#### Create a chart

1. Select **Add** > **Add visual**.
2. In the section Visual types on the left corner, select **Donut chart**.
3. In the Fields list, select **Sales** and **Order date**.
![AWS](/images/2/1.2-9a.png?featherlight=false&width=90pc)

### Add Drill-down Layer
You can add details related to data by adding Drill-down layers.

1. Drag and drop the item **Customer** from the Fields list into the Group/Color section. Hold this field and release the mouse when you see the **Add drill-down layer** message.
![AWS](/images/2/1.2-9b.png?featherlight=false&width=90pc)

2. Right-click on any **Industry** unit (eg Finance).
![AWS](/images/2/1.2-9c.png?featherlight=false&width=90pc)

3. Thanks to step 4, you will see the **Drill down to Customer** section, select this.
![AWS](/images/2/1.2-9d.png?featherlight=false&width=90pc)

4. At this time, the pie chart will show the **Customer** parameter of the **Industry** you have selected. In this case, it's Finance.
![AWS](/images/2/1.2-9e.png?featherlight=false&width=90pc)

Once done, you can select **Undo** to return to the main chart.

### More details

1. Select the gear texture in the right corner of the chart.
2. Select **Data labels** > **Show metrics**.
![AWS](/images/2/1.2-9f.png?featherlight=false&width=90pc)

### Filter dashboard-wide data by optional industry

1. In the left navigation bar, select **Actions** > **Filter same sheet visuals**.
![AWS](/images/2/1.2-12a.png?featherlight=false&width=90pc)

2. When completing step 1, if you select any industry (eg Finance), the parameters in other charts will be filtered and display data of the selected industry.
![AWS](/images/2/1.2-12b.png?featherlight=false&width=90pc)