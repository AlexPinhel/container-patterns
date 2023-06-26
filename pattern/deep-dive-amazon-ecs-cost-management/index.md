---
title: A deep dive into Amazon ECS cost management
description: >-
  How do you track container resource usage back to it's impact on your AWS bill? Watch a demo
  of how to use ECS resource tags and the AWS Cost and Usage billing report
filterDimensions:
  - key: type
    value: video
authors:
  - peckn
  - arvsoni
date: Jun 15, 2023
---

Nathan Peck (Senior Developer Advocate), Weijuan Davis (Senior Product Manager), Shubir Kapoor (Principal Product Manager, Cost Insights) and Arvind Soni (Principal Container Specialist) do a deep dive into cost management and cost allocation on Amazon ECS.

<youtube id="0s8KhOBHW7c" />

#### Summary

AWS has launched a new cost management feature called Split Cost Allocation Data (SCAD) that enables customers to allocate containerized application costs back to individual business units or teams. The feature introduces the ability to use tags to provide cost and usage on a per-task basis. This allows customers to understand their infrastructure costs at a more granular level, and identify opportunities to save money in each containerized service and team.

1. Enable tags in ECS service, including ECS managed tags and tag propagation.
2. Use the cost and usage report to filter and analyze costs. This provides granular data at the hourly per resource level, with each tag becoming a column in the report.
3. Use tags in the cost and usage report to allocate costs down to individual services or teams.
4. Observe actual usage versus reserved usage to optimize cost and try different models and configurations to see which works best from a cost management point of view.