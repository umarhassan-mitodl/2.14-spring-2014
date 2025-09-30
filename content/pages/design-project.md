---
content_type: page
description: This section provides details on the design project for the course and
  supporting files.
hide_download: true
hide_download_original: null
learning_resource_types: []
ocw_type: CourseSection
title: Design Project
uid: 98593a12-d5fa-7ba8-30c7-0831dc32f0f0
---

This problem considers the control of a fast tool servo (FTS), and is based upon the work done by [Xiaodong Lu in his Ph.D. thesis (PDF - 11.2MB)](/ans7870/2/2.14/s14/MIT2_14S14_XDLU_PhD_Thesis.pdf). The design problem focuses on:

*   High-bandwidth current controller for driving the actuator.
*   Identification of the electromechanical plant dynamics from a measured Bode plot.
*   Design of a controller to minimize following error for a sinusoidal reference trajectory, in the presence of sensor noise.
*   Graduate students only: Design of an add-on Adaptive Feedforward Cancellation (AFC) control block at the reference trajectory frequency in order to eliminate following error at that frequency.

We do not give you exact specifications for the servo performance. Rather, you are to apply your best effort to get good performance. The measure of performance in this problem is reduction of the following error due to the reference trajectory and to sensor noise.

The problem starts with designing the controller for the current loop, and then moves on to design of the FTS position controller.

Read the entire {{% resource_link d0434620-6a17-1b74-0f4f-4274f92002b4 "Final Design Project (PDF)" %}}.

Additional files

*   {{% resource_link 70450178-b070-b358-17af-c50c5ba2f4ae "Plant measured Bode plot (ZIP)" %}} (This zip folder contains: 1 .pdf file and 2 .mat files)
*   {{% resource_link 5953e644-7e1a-e18c-d9f5-bae98deb978c "MATLAB Template (M)" %}}