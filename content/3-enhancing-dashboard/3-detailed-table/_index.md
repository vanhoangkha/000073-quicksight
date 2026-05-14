---
title : "Data Details Table"
date: 2024-01-01
weight : 3
chapter : false
pre : " <b> 4.3 </b> "
---


### Content

- [Content](#content)
  - [Format sheet](#format-sheet)
  - [Create detailed data table](#create-detailed-data-table)
  - [Conditional formatting](#conditional-formatting)
  - [Data table format](#data-table-format)
  - [Publish Dashboard](#publish-dashboard)

#### Format sheet

1. To rename the sheet, select the arrow next to the sheet to be renamed, select **Rename** and enter an optional name (eg `Summary`).

![AWS](/images/3/1.3-7a.png?featherlight=false&width=90pc)

2. Select the **+** icon next to the **Summary** sheet. Repeat the above step to rename it to **Details**.

![AWS](/images/3/1.3-7b.png?featherlight=false&width=90pc)

#### Create detailed data table
1. In the Fields list, select **Order ID**, **Order Date**, **Contact Name**, **Country**, **Customer**, **Industry**, **Product **, **Discount** and **Sales**.

2. Select the arrow next to **Discount (Sum)** > **Aggregate: Sum** > **Average** to convert the total discount to the average discount.

![AWS](/images/3/1.3-8a.png?featherlight=false&width=90pc)

2. Select the arrow next to **Sales (Sum)** > the decrease icon to sort the data from large to small.
3. Select the arrow next to **Sales (Sum)** > **Show as: Currency** > **Format** > **More formatting options...**
4. In the Field section, select **Data Type** and change it to **Currency**. In the **Decimal places** section, select **2**. Thus, when you use this field, the data will be displayed in dollars and dong.

![AWS](/images/3/1.3-9a.png?featherlight=false&width=90pc)

#### Conditional formatting
1. Select the symbol **...** in the right corner of the chart, and select **Conditional formatting**.

![AWS](/images/3/1.3-9b.png?featherlight=false&width=90pc)

2. Select **Select a column** > **Discount**.

![AWS](/images/3/1.3-9c.png?featherlight=false&width=90pc)

3. Select **Add background color**.

![AWS](/images/3/1.3-9d.png?featherlight=false&width=90pc)

4. In Conditional #1, select **Greater than or equal to**. In the Value section, the condition is at **0.5**, and choose any color (eg red). Select **ADd condition**.
5. In Conditional #2, select **Greater than or equal to**. In the Value section, the condition is at **0.2**, and choose any color (eg yellow). Select **ADd condition**.
6. In Conditional #3, select **Less than**. In the Value section, the condition is at **0.2**, and choose any color (eg green).
7. Select **Apply** > **Close**.

![AWS](/images/3/1.3-9e.png?featherlight=false&width=90pc)

8. Select **Select a column** > **[Entire row]**.

![AWS](/images/3/1.3-9f.png?featherlight=false&width=90pc)


1. In **Format field based on** select **Order Date**, in **Conditional** select **After**. Under **Date**, select January 1, 2021, and choose any color (eg blue). Select **Apply** > **Close**.

![AWS](/images/3/1.3-9h.png?featherlight=false&width=90pc)

#### Data table format

1. Select the gear icon in the right corner of the chart. Select **Group-by column name**. In the **Contact Name** section, select `Contact`.

![AWS](/images/3/1.3-10a.png?featherlight=false&width=90pc)
2. Select **Value column name**. In the **Discount (Average)** section, select `Avg Discount`.

![AWS](/images/3/1.3-10b.png?featherlight=false&width=90pc)


#### Publish Dashboard
1. In the right corner, select **Share** > **Publish dashboard**.

![AWS](/images/3/1.3-11a.png?featherlight=false&width=90pc)
2. Enter the dashboard name (eg Module 2). Select **Publish Dashboard**.

![AWS](/images/3/1.3-11b.png?featherlight=false&width=90pc)

Here are the published dashboard results.
![AWS](/images/3/1.3-12a.png?featherlight=false&width=90pc)

![AWS](/images/3/1.3-12b.png?featherlight=false&width=90pc)