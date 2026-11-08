# Getting Started with Quick Sight

> Data visualization with Amazon QuickSight.

A hands-on workshop from the [AWS First Cloud Journey](https://github.com/vanhoangkha/aws-first-cloud-journey) series, available in English and Vietnamese.

**Read the workshop online:** https://vanhoangkha.github.io/000073-quicksight/

## Overview

In this workshop, we will build a dashboard to visualize our data. Starting with sample data, we'll go through parts of the workshop that focus on performing data analysis and representation via QuickSight.

We will use Region Singapore (ap-southeast-1), you can choose another region as you like.

## Workshop contents

1. Preparation
2. Introduction
3. Build dashboard
   - Update Dataset
   - Line chart
   - KPI and Insights
   - Pie chart
   - Create Pivot Table
   - Complete Dashboard
4. Dashboard Improvements
   - Dashboard Format
   - Additional charts
   - Data Details Table
5. Create Interactive Dashboard
   - Create backup dashboard
   - Filter Settings
   - Filter Actions
   - Navigation Actions
   - Publish dashboard
6. Clean up resources

## Prerequisites

- An AWS account with permissions to create the resources used in the labs
- Basic familiarity with the AWS Management Console
- [Hugo](https://gohugo.io/installation/) (extended edition) if you want to run the site locally

## Run locally

```bash
git clone https://github.com/vanhoangkha/000073-quicksight.git
cd 000073-quicksight
hugo server
```

Then open http://localhost:1313 in your browser.

## Repository structure

| Path | Purpose |
| --- | --- |
| `content/` | Workshop pages (`*.md` English, `*.vi.md` Vietnamese) |
| `static/` | Images and other static assets |
| `layouts/` | Hugo layout overrides |
| `themes/` | Hugo theme |
| `config.toml` | Site configuration |

## Cost and cleanup

The labs create AWS resources that may incur charges. Complete the **Clean up** chapter when you finish to remove them.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

To report a security issue, see [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
