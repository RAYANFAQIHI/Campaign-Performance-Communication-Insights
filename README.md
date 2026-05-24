# Campaign Intelligence Dashboard

## Overview

This project analyzes the performance of a communication campaign using Power BI.  
The goal is to evaluate campaign performance, identify the most effective channels, understand audience behavior, assess message clarity, and provide actionable recommendations based on data.

The project combines data analysis, business intelligence dashboards, and communication insights to support better decision-making for future campaigns.

---

## Project Objectives

The main objectives of this project are to:

- Analyze campaign performance across different communication channels.
- Identify high-performing and low-performing channels.
- Evaluate audience awareness, trust, and message clarity.
- Understand audience needs and preferred communication channels.
- Compare campaign performance against benchmark standards.
- Provide practical recommendations to improve future campaign performance.

---

## Tools Used

- Power BI
- DAX
- Power Query
- Excel
- PowerPoint / PDF

---

## Dataset Description

The dataset represents a fictional communication campaign and includes multiple tables:

| Table | Description |
|---|---|
| Campaign Performance | Channel-level performance including reach, clicks, registrations, spend, and conversion |
| Audience Segments | Audience awareness, trust, message clarity, top needs, and preferred channels |
| Survey Results | Audience survey responses related to campaign understanding and barriers |
| Feedback Log | Audience feedback, sentiment, and issue categories |
| Benchmarks | Campaign performance compared with internal and sector benchmarks |

---

## Dashboard Pages

The Power BI dashboard consists of four main pages:

# 1. Executive Overview
<img width="2058" height="1155" alt="Screenshot 2026-05-22 010443" src="https://github.com/user-attachments/assets/04658f58-89ac-4e67-9703-e3860a384256" />

This page provides a high-level summary of the campaign performance.

Key indicators include:

- Total Reach
- Total Registrations
- Conversion Rate
- Cost per Registration
- Registrations by Channel
- Conversion Rate by Channel
- Weekly Registration Trend

---

# 2. Channel Performance
<img width="2069" height="1169" alt="Screenshot 2026-05-22 011542" src="https://github.com/user-attachments/assets/56f0dde9-48aa-46bb-a6ac-1a57c331f538" />

This page analyzes the efficiency of each communication channel.

It focuses on:

- Channel Efficiency Gap
- Registration Share vs Spend Share
- Cost per Registration by Channel
- Channel-level performance details

The goal of this page is to identify which channels deserve more investment and which channels require budget optimization.

---

# 3. Communication Insights
<img width="2062" height="1171" alt="Screenshot 2026-05-22 011832" src="https://github.com/user-attachments/assets/b30917b6-0cdf-4102-beab-72dd9f95bb7c" />

This page focuses on the communication perspective of the campaign.

It analyzes:

- Audience awareness
- Message clarity
- Trust score
- Negative feedback rate
- Feedback categories
- Audience needs and preferred channels

This section helps identify whether the communication challenge is related to the message, the channel, or the registration journey.

---

# 4. Benchmark & Recommendations
<img width="2064" height="1161" alt="Screenshot 2026-05-22 014406" src="https://github.com/user-attachments/assets/bd0a96c5-fb2e-4d9e-8be1-fac353d3c22d" />

This page compares the campaign performance with benchmark standards.

It highlights:

- CTR Gap
- Conversion Gap
- Cost Gap
- Rate Metrics vs Benchmark
- Cost per Registration vs Benchmark
- Recommended Actions

---

## Key Findings

The analysis showed that the campaign achieved strong reach, but there is room for improvement in conversion and cost efficiency.

Key findings include:

- The campaign reached approximately **1M users**.
- Total registrations reached around **1,640**.
- The overall conversion rate was **5.90%**.
- The cost per registration was approximately **344.77 SAR**.
- LinkedIn generated the highest number of registrations.
- WhatsApp/SMS showed strong cost efficiency.
- Internal Event achieved the highest conversion rate.
- Website Banner and X/Twitter had higher costs and weaker conversion performance.
- Communication gaps appeared in message clarity, registration understanding, and audience-specific messaging.

---

## Communication Insights

The communication analysis showed that different audience segments require different messages and channels.

| Audience | Main Need | Preferred Channel |
|---|---|---|
| Customers | Understand the benefit and how to register | Instagram / WhatsApp |
| Employees | Know how to explain the service | Email / Internal Event |
| Government Stakeholders | Understand policy relevance and outcomes | Briefings / LinkedIn |
| Media | Clear story and supporting facts | Press Kit / X |
| Partners | Use cases and integration details | LinkedIn / Email |

---

## Recommendations

Based on the analysis, the following actions are recommended:

1. Shift budget toward high-performing channels such as LinkedIn and WhatsApp/SMS.
2. Reduce spending on high-cost and low-conversion channels such as Website Banner and X/Twitter.
3. Improve the registration journey to reduce drop-off after clicks.
4. Rewrite campaign messages to clearly explain the service value and registration steps.
5. Use Internal Event messaging as a model for conversion-focused communication.
6. Tailor messages based on audience segment needs and preferred channels.

---

## 30-Day Improvement Plan

| Week | Action |
|---|---|
| Week 1 | Fix registration friction by reviewing the landing page, form steps, and call-to-action messages |
| Week 2 | Redesign campaign messages based on audience segment needs |
| Week 3 | Reallocate budget toward efficient channels and reduce low-performing spend |
| Week 4 | Run A/B testing and monitor conversion rate improvements |

---

## Project Structure

Recommended repository structure:

```text
campaign-intelligence-dashboard/
│
├── README.md
├── Campaign Intelligence Dashboard.pbix
├── Campaign Analysis Presentation.pdf
├── Executive Summary.pdf
│
├── data/
│   └── campaign_data.xlsx
│
├── images/
│   ├── executive-overview.png
│   ├── channel-performance.png
│   ├── communication-insights.png
│   └── benchmark-recommendations.png
