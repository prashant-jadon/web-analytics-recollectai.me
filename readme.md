Here's your full project converted into a clean and professional `README.md` format for GitHub or portfolio use:

---

```markdown
# 📊 Mini Project - Web Analytics

**Student Name**: Prashant Jadon  
**UID**: 24MCC20001  
**Branch**: MCC  
**Section/Group**: B  
**Semester**: 2nd Sem  
**Date of Performance**: 4-April-2025  
**Subject Name**: Web Analytics Lab  
**Subject Code**: 24CAP-676  

---

## 🔍 Project Title  
**Optimizing Conversion Rates for RecollectAI.me Using Web Analytics & A/B Testing**

---

## 🧠 Project Summary

RecollectAI.me is a student-focused AI tool for capturing and summarizing lectures. In its early adoption phase, it has gathered 16 new users with an average session time of just 17 seconds. The main goal of this project is to optimize user experience and improve engagement and retention using real-time analytics and A/B testing.

---

## 🎯 Objective

To increase engagement, page views, and repeat visits using data-driven A/B testing experiments. Inspired by Amazon's use of iterative optimization, this project implements two test variations aimed at improving unique visitor count and repeat behavior.

---

## 🛠️ Tools & Tech Stack

- **Google Analytics 4 (GA4)** – User metrics & behavior tracking  
- **Awo.so** – A/B testing setup and analysis  
- **Firebase** – Event-level feature tracking  
- **Vercel** – Hosting & deployment  

---

## 📊 User Data Snapshot (From GA4)

| Metric                         | Value                    |
|--------------------------------|--------------------------|
| Active Users (30d)             | 16                       |
| New Users                      | 16                       |
| Avg. Engagement Time per User  | 17 seconds               |
| Active Users (Last 30 mins)    | 1                        |
| Total Revenue                  | $0.00                    |
| Top Page                       | `offkart` – 23 views (+2200%) |
| Top Countries                  | 🇺🇸 US (5), 🇮🇳 India (4), 🇮🇪 Ireland (1) |
| Top Traffic Channels           | Organic Social (9), Direct (6), Referral (2) |
| Retention (Week 1+)            | 0%                       |

---

## ⚠️ Problem Areas Identified

| Issue                    | Insight from Data                          |
|--------------------------|--------------------------------------------|
| Low user retention       | 0% return rate after Week 1                |
| Minimal feature interaction | No tracked events like `start_listening`   |
| Short average engagement | Users drop off within 17 seconds           |
| Low product page diversity | All traffic clustered on a single page     |

---

## 🧪 A/B Testing Metrics

### ✅ M1 – Unique Visitors per Page Visit

- **Primary Metric**: Unique visitors  
- **Direction of Better**: Increase  
- **Minimum Detectable Effect (MDE)**: ±5%  
- **Region of Practical Equivalence (ROPE)**: ±1%  
- **Statistical Power**: 80%  
- **False Positive Rate (α)**: 10%  
- **Goal**: Increase page views with unique visitor tracking

### 🔁 M2 – Returning Visitors

- **Metric**: Unique visitors for repeated page visits  
- **Statistical Parameters**: Same as M1  
- **Goal**: Improve user retention through visual clarity and action-oriented CTAs  

---

## 🧠 Hypotheses

- **H1 (M1)**: “Improved hero visuals and CTA color will increase unique visitors by at least 5%.”  
- **H2 (M2)**: “A dynamic hero experience with explainer video will lead to more revisits.”

---

## 📈 Success KPIs

| Metric                  | Target         |
|-------------------------|----------------|
| Avg. Engagement Time    | ≥ 45 seconds   |
| CTA Click Rate          | ≥ 30%          |
| Week 1 Retention Rate   | ≥ 25%          |
| Unique Visitors (M1)    | +5% vs baseline|
| Return Visitor Rate (M2)| +5% vs baseline|

---

## 🛠️ Implementation Plan

1. Set up GA4 custom events (`start_listening`, `summarize_click`)  
2. Launch Variant B using Awo.so  
3. Run the A/B Test for 14 days  
4. Analyze results using Awo’s statistical engine  
5. Deploy the winning variant if statistical significance is met  

---

## 🧾 Conclusion

Through real-time web analytics and A/B testing on RecollectAI.me, we aim to replicate industry-leading optimization processes, such as those used by Amazon. By focusing on high-impact metrics (M1 & M2), this project transforms early user activity into measurable improvements in engagement and retention.

---

## 🎓 Learning Outcomes

- Enhanced understanding of user behavior and conversion funnels  
- Improved conversion rates through A/B testing  
- Analyzing metrics like click-through rates, page visits, and retention  
- Leveraging data to make product design decisions  
```

---
