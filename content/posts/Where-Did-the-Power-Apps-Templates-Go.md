---
title: "Where Did the Power Apps Templates Go? The 2026 Guide"
date: 2026-03-27T10:00:00+05:30
draft: false
author: "Sunil Pashikanti"
description: "A guide for architects and developers on finding classic finance templates like Expense Reimbursement and Budget Tracking in the modern Power Apps interface."
tags: ["Power Apps", "Microsoft 365", "Architecture", "Low Code", "Copilot"]
categories: ["Technical Insights", "Power Platform"]
showToc: true
TocOpen: false
---

If you’ve logged into Power Apps recently looking for the classic "Expense Reimbursement" or "Budget Tracking" templates to study their UI or logic, you might have noticed a glaring change: **The Template Gallery as we knew it is gone.**

As of March 2026, Microsoft has pivoted away from standalone "starter apps" in favor of more robust, enterprise-grade deployment methods. If you are an architect or a developer trying to find these learning resources, here is the new map.

## 1. The "Create" Screen (The New Sidebar)
Microsoft hasn't deleted the templates; they’ve simply categorized them under the **Create** menu. 
* Navigate to the **Create** tab on the left navigation bar.
* Look for the row labeled **"Start from template."**
* Click **"See all templates"** at the end of that row.

**Note for Architects:** Many of these now require a **Dataverse** environment. If you are in a "Default" environment without a database, some high-end templates (like Invoice Approval) may not appear.

## 2. Microsoft AppSource (Managed Solutions)
The more complex finance templates have been moved to **[Microsoft AppSource](https://appsource.microsoft.com/)**. 
Instead of a simple "one-click" app, these are now delivered as **Managed Solutions**. This is a superior way to learn because it shows you how to package:
* Canvas Apps
* Model-Driven Apps
* Power Automate Cloud Flows
* Dataverse Tables

## 3. The "Describe it to Design it" Shift
The biggest reason for the "missing" templates is **Copilot**. Microsoft's strategy is now "AI-First." 
Instead of a static template, you can now type:
> *"Create an expense reimbursement app with a gallery for my reports and a form to submit new ones."*

Copilot will generate the schema and the UI dynamically. While this is great for speed, I still recommend looking at the classic templates to understand **Responsive Design** and **Complex Formulas** that AI might simplify too much.

## 4. Why This Matters for ALM
As a Lead Architect, I see this shift as a win for **Application Lifecycle Management (ALM)**. The old templates were often "App-only" and difficult to move between environments. By moving to a Solution-based model in 2026, Microsoft is forcing developers to learn professional deployment patterns from day one.

---

### Pro-Tip for Learning
If you want to see professional UI tricks (like a **Loading Shimmer** effect or advanced navigation), don't just look at templates. Check out the [Power Apps Samples GitHub](https://github.com/microsoft/PowerApps-Samples) or the [PCF Gallery](https://pcf.gallery/).

**Happy Coding!**

---

### Resources & Links

* **Source Code:** [GitHub - SunilP-PowerApps-Shimmer](https://github.com/spashikanti/SunilP-PowerApps-Shimmer)
* **Community:** Find this control on [PCF Gallery](https://pcf.gallery/) (Submission in progress)
* **Documentation:** [Full Installation Guide](https://github.com/spashikanti/SunilP-PowerApps-Shimmer/blob/main/README.md)

---
### Let's Connect
How is your organization handling the shift to Managed Environments in 2026? I would love to hear your thoughts in the [Power Platform Community](https://community.powerplatform.com/profile/?userid=8077d18b-7b47-ee11-be6d-6045bdebe084) or on [LinkedIn](https://www.linkedin.com/in/sunil-kumar-pashikanti/).

{{< author-bio >}}
