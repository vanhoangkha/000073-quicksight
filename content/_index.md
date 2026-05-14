---
title : "Getting Started with Quick Sight"
date: 2024-01-01
weight : 1
chapter : false
---

# Get started with Quick Sight

In this workshop, we will build a dashboard to visualize our data. Starting with sample data, we'll go through parts of the workshop that focus on performing data analysis and representation via QuickSight.

We will use Region Singapore (ap-southeast-1), you can choose another region as you like.

#### Content
1. [Preparation](1-initial-setup)
2. [Build Dashboard](2-first-dashboard)
3. [Dashboard Improvements](3-enhancing-dashboard)
4. [Dashboard interactivity](4-add-interactivity)

#### Some basic concepts in QuickSight

**Data source** is an external data store and you need to configure data access in this external datastore, for example. Amazon S3, Amazon Athena, Salesforce, etc.

**Dataset** defines the specific data in the Data source that you want to use. For example, the Data source can be a table if you are connecting to the Data source database. It can be a file if you are connecting to an Amazon S3 Data source. The Dataset also stores any data preparation you have performed on that data, such as renaming a field or changing its data type. This saves you from having to revise the data every time you want to create a new Analysis based on it.

**Analysis** is a container for a collection of related Visuals and stories, i.e. all stories that apply to a given business goal or KPI. You can use multiple Datasets in an analysis, however 1 **Visual** can only use one of those Datasets.

**Visual** is a graphical representation of your data. You can create many different types of Visuals in an analysis, using different datasets and Visual types.

**Dashboard** is a page that includes one or more view-only Analysis that you can share with other Amazon QuickSight users for reporting purposes. The Dashboard keeps the configuration of the Analysis at the time you publish it, including things like filtering, parameters, controls, and sort order. When you view the Dashboard, this page reflects the current data in the Datasets used by **Analysis**.