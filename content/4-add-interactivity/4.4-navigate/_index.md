---
title : "Navigation Actions"
date: 2024-01-01
weight : 4
chapter : false
pre : " <b> 5.4 </b> "
---


#### Navigation Actions

**Navigation actions** are primarily designed to take the user to other sheets based on a selection, often with filters.

For example, take the user from a sheet with summary metrics to a sheet with more detail on selection.

1. Select the original chart. In this case the pie chart. In the left navigation bar, select **Parameters** > **Create one...**.

2. Set the option name (eg `Industry`). Select **Create**.

![AWS](/images/4/1.4-4a.png?featherlight=false&width=90pc)

3. Select **Custom actions**.

![AWS](/images/4/1.4-4b.png?featherlight=false&width=90pc)

4. Select the **+** icon to the right of the Actions column.

![AWS](/images/4/1.4-4c.png?featherlight=false&width=90pc)

5. Set an arbitrary action name (eg `See orders from «Industry» customers).

{{%notice tip%}}
If you don't want to type **<<Industry>>**, you can select the **...** icon in the right corner and select **<<Industry>>**.
{{% /notice %}}

6. In the Action type section, select **Navigation action**. Under Target sheet, select **Details**. Select the **+** icon to the right of the Parameters column.

![AWS](/images/4/1.4-4d.png?featherlight=false&width=90pc)
 
7. Under Parameters, select **Industry** you just created in steps 1 and 2. Select **Add** > **Save**.

![AWS](/images/4/1.4-4e.png?featherlight=false&width=90pc)

Now when you select an industry in the pie chart, you will see the option **See orders from Tech customers**. When selected you will be taken to the **Details** sheet.

![AWS](/images/4/1.4-4f.png?featherlight=false&width=90pc)
  
You can follow these steps to have the **Details** sheet filtered based on your industry selection:

8. In the left navigation bar, select **Filter** > **Create one...** > **Industry**.

![AWS](/images/4/1.4-4g.png?featherlight=false&width=90pc)
  
9. Select **Use parameters** > **Industry** > **Apply**.

![AWS](/images/4/1.4-4h.png?featherlight=false&width=90pc)

Now if you select the **Tech** industry, the **Details** sheet only shows the **Tech** industry data.

![AWS](/images/4/1.4-4i.png?featherlight=false&width=90pc)