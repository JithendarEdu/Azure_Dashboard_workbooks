# Azure Monitor Workbooks: Learning & Documentation

## Overview
This section documents my learning and experiments with [Azure Monitor Workbooks](https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/workbooks-create-workbook).

### What are Azure Workbooks?
Azure Workbooks are interactive reports and dashboards in the Azure Portal. They allow you to combine text, queries, metrics, parameters, images, and more to visualize and analyze data from Azure resources.

## Key Steps to Create and Use Workbooks
1. **Create a new workbook**: Go to Azure Monitor > Workbooks > New.
2. **Add elements**: You can add text (Markdown), images, videos, parameters, queries (KQL, metrics), charts, links, groups, etc.
3. **Edit mode**: Use the Edit button to add or modify elements.
4. **Text blocks**: Use Markdown for formatting, headings, tables, and links. Text can be styled (info, warning, error, etc.).
5. **Add queries**: Insert KQL or metric queries to visualize data. Use best practices for performance (summarize, short time ranges, check for missing tables/columns).
6. **Parameters**: Add parameters for interactivity (dropdowns, text, time range, etc.).
7. **Charts**: Visualize metrics with area, bar, line, scatter, or grid charts.
8. **Links & Tabs**: Add navigation, buttons, or tabs for better UX.
9. **Groups**: Organize content, control visibility, and improve performance.
10. **Images & Videos**: Embed for richer context.

## Best Practices
- Use summary rules and short time ranges for queries.
- Protect against missing tables/columns using `column_ifexists` and `union isfuzzy=true`.
- Use parameters for dynamic, interactive reports.
- Organize large workbooks with groups and templates.

## Useful Links
- [Official Documentation](https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/workbooks-create-workbook)
- [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Sample Workbooks](https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/workbooks-sample-links)

---

## My Workbook Experiments & Notes

### [Date]
**Goal:**
- (What are you trying to achieve?)

**Steps Taken:**
1. 
2. 

**Learnings/Issues:**
- 

**Screenshots/Links:**
- 

---

> _Repeat the above template for each experiment or learning session._
