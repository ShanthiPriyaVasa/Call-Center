![Call Center](https://raw.githubusercontent.com/ShanthiPriyaVasa/Call-Center/main/Call%20Center.png)
# Call Center Performance Tableau Accelerator

## Overview

This Tableau Accelerator allows you to:

- Assess & Improve the performance of your Call Center
- Increase our quality of service and customer satisfaction
- Identify your top performing agents
- Better allocate resources according to peak periods
- Assess training requirements for your agents

## Features

### Key Business Questions Answered
- How many incoming calls do we handle?
- How many calls were answered/abandoned?
- How long do callers wait before hanging up?
- How long do callers wait before having their call answered?
- Which level of service do we deliver to our customers? How satisfied are they?

![Executive Summery](https://raw.githubusercontent.com/ShanthiPriyaVasa/Call-Center/main/Executive%20Summary.png)

### KPIs Monitored and Improved

#### Calls
- **Total Incoming Calls:** Total number of incoming calls
- **Incoming Calls (Daily):** Average number of incoming calls per day worked
- **Nb of Inquiries:** Number of inquiries, with multiple calls possibly for one inquiry

#### Level of Service
- **Total Abandoned Calls:** Total number of calls that were abandoned
- **Abandoned Calls %:** Share of incoming calls that were abandoned (expressed in %)
- **Total Answered Calls:** Total number of calls answered by agents
- **Answered Calls %:** Share of answered calls compared to all incoming calls (expressed in %)
- **FCR - First Contact Resolution:** Number of inquiries resolved/closed at first call
- **FCR - First Contact Resolution %:** Share of inquiries resolved at first call (expressed in %)
- **CSAT - Customer Satisfaction:** Customer Satisfaction score (1 for unsatisfied, 5 for fully satisfied)

![Agent Performance](https://raw.githubusercontent.com/ShanthiPriyaVasa/Call-Center/main/Agents%20Performance.png)

#### Agents
- **Nb of Agents:** Number of agents that have handled at least one call over the period
- **Incoming Calls per Agent:** Average number of incoming calls per Agent
- **Answered Calls per Agent:** Average number of answered calls per Agent

![Activity Peaks](https://raw.githubusercontent.com/ShanthiPriyaVasa/Call-Center/main/Activity%20Peaks.png)

#### Time
- **AHT - Average Handle Time:** Average Call Handle Time (Talk Time + Hold Time + After-call Tasks) (expressed in s)
- **Avg Wait Time:** Average time callers wait when calling the call center (expressed in s)
- **Avg Wait Time until Answer:** Average time callers wait before having their call answered (expressed in s)
- **Avg Wait Time until Abandon:** Average time callers wait before hanging up (expressed in s)
- **Avg Talk Time:** Average talk time (expressed in s)

## Required Attributes

- **Call # (string):** Call Unique Identifier
- **Call Date Time (date):** Date and Time of the call
- **Abandon Flag (string):** Expected values: 'Y', 'N'. 'Y' means the call was abandoned
- **First Contact Resolution Flag (string):** Expected values: 'Y', 'N'. 'Y' means the issue was solved after the first contact
- **Customer (string):** Customer where the caller is working
- **Agent (string):** Agent who handled the call
- **Call Reason (string):** Reason for the call
- **Inquiry # (string):** Unique identifier of caller inquiry
- **Wait Time (s) (numeric):** Call Wait Time in seconds
- **Talk Time (s) (numeric):** Call Talk Time in seconds
- **Handle Time (s) (numeric):** Handle Time in seconds (Talk Time + Hold Time + After-call Tasks)
- **Customer Satisfaction (numeric):** 1 for unsatisfied, 5 for fully satisfied
