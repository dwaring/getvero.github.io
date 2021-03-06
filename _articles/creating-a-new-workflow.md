---
title: Creating a new workflow
description: Each new workflow starts with an Entry Trigger, and you can choose from different logic and actions to build your customer journey.
categories:
- workflows
layout: articles
---

# Creating a new workflow

Workflows provide you with the visibility and tools to design and manage your customer email journeys. With a clear view of all the logic, steps and content in your journey, you and your team can feel confident that your customers will receive the right message, at the right time. 

Each new workflow starts with an Entry Trigger, and you can choose from different logic and actions to build your customer journey. The basic configuration of each step is visible on the canvas, and the sidebar gives you access to the full configuration options available for each step.

![{{ site.data.screenshots.vero.workflows.canvas-overview['title'] }}]({{ site.data.screenshots.vero.workflows.canvas-overview['image'] }})

To create a new workflow:
1. Select an entry trigger
2. Add logic and action steps
3. Add a conversion goal
4. Save and publish your workflow

## 1. **Select an entry trigger**

In order for a customer to enter a Workflow, they must trigger an event. Vero defines events as all the actions a customer takes on your site. It could be everything from signing up for an account, purchasing an item or viewing a page. You can [track your customer event data]({{site.data.links.events.event-placeholders}}) in Vero so that when you customer triggers the specified event they will be entered into the workflow.

## 2. **Add logic and action steps**

All steps can be easily moved around using drag and drop, giving you full control over the order of logic, delays, and emails. This allows you and your team to quickly create and improve your customer journeys.

![{{ site.data.screenshots.vero.workflows.drag-and-drop['title'] }}]({{ site.data.screenshots.vero.workflows.drag-and-drop['image'] }})



### Logic steps:


- **Delay**

  Designed to hold users at any stage in a workflow for a period of time, before allowing them to move on to the next step. This is particularly useful if a user must be given time to complete actions before receiving an email. [Vero offers three types of delays]({{site.data.links.articles.timing}}).

- **Branch**

  Allows you to create several paths in the journey for your users. By adding logic that results in the user moving down either a true or false path means you can tailor your customer journeys even further. This also means you can combine multiple campaigns into a single workflow so you and your team can view more complex journeys on one visual canvas.

- **Filter**

  Progress users to the next step of the workflow if all the specified conditions are met. customers who don't meet the conditions of the filter will exit the workflow at this point.



### Action steps:

- **Email**

  You can add emails to your workflow and create/edit the email content from the workflow screen. The aim of all Workflows is to allow you to engage with your customers at the right time in their journey.

- **Push notifications** - Coming soon!

## 3. Add a Conversion Goal

You can measure the overall success of a workflow by adding a conversion goal. A conversion goal is reached when a customer triggers the specified [event]({{site.data.links.events.event-placeholders}}) up to 30 days after they have left the workflow. 

If a customer triggers the conversion goal they will continue to progress normally through the workflow. They will not exit the workflow.

You can change the goal conversion period via **Settings** > **Advanced**.

## 4. Save and publish your workflow

Once you've reviewed the configuration steps, simply save and publish your workflow to start your customers on their journey!

**Next up**: [Making changes to a live campaign]({{ site.data.links.workflows.make_changes_live_workflow}})
