---
title : "Create Pivot Table"
date : "`r Sys.Date()`"
weight : 5
chapter : false
pre : " <b> 3.5 </b> "
---

#### Add Pivot Table

1. In the left corner, select **Add** > **Add visual**.
2. In the section Visual types in the lower left corner, select **Pivot Table**.
3. In the Fields list, select **Sales**, **Region**, and **Subregion**.
4. Drag and drop **Order Date** into the **Columns** section in the Field wells section.
![AWS](/images/2/1.2-10a.png?featherlight=false&width=90pc)

5. Select the **Order Date** item arrow in the Field wells section. Select **Aggregate:Day** > **Year**. Pivot Table will now be divided by year.
![AWS](/images/2/1.2-10b.png?featherlight=false&width=90pc)

6. Select the gear icon in the right corner of the chart. Select **Styling** > **Hide single metric** so that the word Sale under each year disappears.
![AWS](/images/2/1.2-10c.png?featherlight=false&width=90pc)

7. Select the item **Subtotal** > **Show subtotals for rows**. At this point, the Pivot Table will have totals by year and region.
![AWS](/images/2/1.2-10d.png?featherlight=false&width=90pc)