---
title: ABUS.13 Warn Users Where Appts are Outside Disposition Timeframe 
sidebar: usecase_sidebar
permalink: usep_abus13.html
---

## ABUS.13 Warn Users Where Appts are Outside Disposition Timeframe 
**_In order_** that the patient and their call handler or clinician can make an informed decision of the appropriate timescale and location of service that best meets the patient's needs and situation 

**_As a_** Integrated Urgent Care Service Provider

**_I want_** to be warned if the appt slot I am about to book falls outside of the clinically appropriate timeframe for this patient. 

### Commentary 
Urgent care can theoretically book an appointment at any time offered even if that goes beyond the clinical assessment time frame.  Ideally any appointment interface should warn the user that they are about to book beyond the clinical assessment timeframe and show by how long.  It should then ask for them to confirm that decision. It may be that it should be possible to prevent appointments from being booked past the disposition timeframe unless requested by the patient. 

### Acceptance Criteria 
* The request to confirm the appt slot **must** warn the user if they are about to book an appt that is outside the clinical assessment timeframe. 
* The user warning **should** include details of by how long the appt fails to meet the clinical assessment timeframe. 
* The system **must** ensure that the user confirms a decision to continue. 
* The returned list of appointments **may** mark those appts that do not meet the current disposition timeframe, making them unbookable, if the user of the system does not have sufficient clinical authority to book appts outside the disposition timeframe. 
