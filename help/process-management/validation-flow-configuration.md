---
title: How to configure validation workflows in Adobe Campaign
description: Learn how to configure different approval validation workflows.
feature: Workflows, Approvals
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
role: Business Practitioner
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
---
# How to configure validation workflows in Adobe Campaign

Adobe Campaign offers several options for marketers to review and provide delivery content, campaign target, data extraction and budget approvals. 

This tutorial explains how to configure different approval validation workflows.

## Prerequisite {#prerequisite}

Prior to enabling approval steps, the marketing team must define individual reviewers:

* The Adobe Campaign reviewer role within an approval activity can either be a single reviewer (Operator) or a group of reviewers (Operator role). 
* The reviewers and reviewer groups must be previously configured in Adobe Campaign by an Administrator role. This enables campaign developers to select the reviewers as approvers in a campaign or a delivery.

## Configuring approvals for campaigns  {#configuring-approvals-for-campaigns}

If you have the same set of reviewers for all deliveries in your campaign workflow, then you would leverage the [!DNL Campaign] approval functionalities. By setting up approvals and reviewers at the campaign level, the approval tasks and reviewers will be pushed down to each delivery activity of your workflow once the workflow is executed.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Configuring approvals for deliveries  {#configuring-approvals-for-deliveries}

You can also set up approvals at a delivery level. If delivery approvals steps and reviewers differ from the campaign approval steps and reviewers, the delivery settings will override the campaign settings.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Configuring an approval activity  {#configuring-an-approval-activity}

Unlike the delivery or campaign approvals, the approval activity allows one to create an approval process within a workflow. This way, the targeting selection logic can be approved before the delivery is launched. It also allows approval at multiple levels within the workflow, if needed.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

For more information, refer to the [Approval Documentation](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)