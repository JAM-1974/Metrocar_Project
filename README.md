# Metrocar Project

## Project Overview
This project presents a detailed analysis of user and ride funnels for Metrocar, a ride-sharing app, focusing on optimisation opportunities to improve user retention, ride completion rates, and overall platform efficiency. The goal of this analysis was to identify pain points in the user journey and develop data-driven recommendations to enhance Metrocar's performance and customer satisfaction.

The project analysed user, and ride data from January 2021 to April 2022, covering over 6,233 users and 212,628 completed rides, with a total revenue of $4,251,668. The analysis helped uncover key conversion rate drop-offs, platform usage insights, and customer behavior trends. Data manipulation and visualisations were performed using Pandas, Plotly, Seaborn, and Matplotlib.

## Key Questions
The analysis was guided by the following questions:

- At which stage does the highest drop-off occur in the user funnel?
- Which age demographic has the highest conversion rate?
- What are the main factors leading to ride cancellations, and how can they be reduced?
- How can surge pricing be optimized to maximize revenue without hurting user retention?
- What strategies can improve both driver performance and user satisfaction?

## Methods and Tools
### Data Processing and Analysis:

**Exploratory Data Analysis (EDA):** Exploratory Data Analysis (EDA): Conducted to uncover patterns, outliers, and trends in user behavior.

**Funnel Analysis:** Built separate user and ride funnels to track conversion rates from app download through ride completion and user reviews.

**Platform-Based Insights:** Analysed platform usage (iOS, Android, Web) and identified opportunities to improve user acquisition efforts on Android.

**Age-Based Performance:** Investigated conversion rates across age groups, emphasising the importance of addressing missing age data.

### Tools:

**- Pandas:** Used for data wrangling, cleaning, and aggregating funnel data.

**- Plotly, Seaborn, Matplotlib:** Employed for visualising data trends, funnel progression, and ride-request peaks by time of day.

**- SQL:**  Utilised to query and extract raw data from the database prior to analysis.

## Key Insights

### Funnel Drop-offs:
A 49% drop-off occurred between the rides accepted and rides completed stages, primarily driven by driver availability issues, user cancellations, and communication gaps.
A 35% drop-off was observed between ride requests and accepted rides, likely due to an insufficient supply of drivers.

### Platform Usage:
iOS users accounted for 60% of total platform usage, while Android users represented 30%, highlighting a mismatch between Metrocar’s user base and overall smartphone market share.

### Demographics & Retention:
The 35–44 age group exhibited the highest conversion rates across all funnel stages, positioning them as a key target demographic for Metrocar.
Approximately 30% of users did not provide their age during signup, limiting the accuracy of customer segmentation efforts.
The retention rate declined to 25% after 60 days, highlighting the need for improved retention strategies.

### Surge Pricing and Cancellation:
Peak ride requests occurred during rush hours (7 AM–10 AM and 3 PM–8 PM), presenting opportunities for surge pricing but also leading to higher cancellation rates due to increased fares.


## Recommendations

- **Enhance Driver Support:** Implement better navigation tools and provide real-time traffic updates to assist drivers.

- **Improve Communication:** Establish clearer and more consistent communication channels between drivers and users during the pickup process.
- **Optimise Surge Pricing:** Refine surge pricing strategies to balance profitability with user retention during peak demand periods.

- **Mandate Age Range Collection:** Require users to input their age range during signup to enable more effective segmentation and targeted marketing.

- **Expand Driver Base:** Increase the number of active drivers to reduce cancellations caused by driver shortages.

- **Tailored Marketing Initiatives:** Focus marketing campaigns on the high-performing 35–44 age group and develop strategies to re-engage users with missing demographic data.

- **Launch Loyalty Programs:** Introduce loyalty programs aimed at improving customer retention and rewarding frequent users.

## Conclusion
This project highlights key opportunities for Metrocar to optimise its platform by enhancing driver availability, improving driver–user communication, and better targeting high-value user demographics. By addressing drop-offs in the customer and ride funnels and refining surge pricing strategies, Metrocar can drive higher revenue, boost user satisfaction, and improve overall platform performance.


## Authors

Jason A. Martin

Mayfair A. Agyei

Elif Aydin Alsancak 

Nina Ojike Udeh
