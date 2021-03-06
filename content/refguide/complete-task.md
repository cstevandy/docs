---
title: "Complete Task"
parent: "workflow-activities"
menu_order: 10
tags: ["studio pro", "user task", "workflow", "task outcome", "complete task"]
---

{{% alert type="warning" %}}
This activity can only be used in **Microflows**.
{{% /alert %}}

## 1 Introduction

The **Complete task** activity can be used to define which outcome the [user task](user-task) should follow. 

![Complete Task](attachments/set-task-outcome/complete-task.jpg)

## 2 Properties

An example of complete task properties is represented in the image below:

![Complete Task Properties](attachments/set-task-outcome/complete-task-properties.jpg)

There are two sets of properties for this activity, those in the dialog box on the left, and those in the properties pane on the right.

The **Complete task** properties pane consists of the following sections:

* [Action](#action)
* [Common](#common)

## 3 Action Section {#action}

The **Action** section of the properties pane shows the action associated with this activity.

You can open a dialog box to configure this action by clicking the ellipsis (**…**) next to the action.

You can also open the dialog box by double-clicking the activity in the microflow or right-clicking the activity and selecting **Properties**.

### 3.1 User Task

The user task entity available from the microflow parameters.

### 3.2 Workflow Task

The user task for which you want to set an outcome. 

### 3.3 Outcome

Gives you a list of available outcomes for the selected user task. The user task will follow the selected outcome. If there is only one outcome available, the value is set to *Default* and is not editable.

## 4 Common Section {#common}

{{% snippet file="refguide/microflow-common-section-link.md" %}}