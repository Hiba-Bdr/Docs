# Introduction

Recommender systems have been developed in response to the massive expansion of content available online. Indeed, they help reduce the time and effort users must spend to find relevant information among a vast array of options on the Internet. In 2024 alone, approximately **720,000 hours of video** are uploaded to YouTube every day, meaning it would take years for a single user to watch it all (Sources: EarthWeb, DemandSage). Additionally, Spotify offers around 6 million podcasts, **350,000 audiobooks**, and **100 million songs** (Spotify). As for Amazon, the platform lists approximately **600 million products** on its marketplace (amzscout).

Beyond striving to improve user satisfaction, companies also aim to maximize user engagement or align recommendations with their business strategies. Consequently, users’ browsing history and all interactions with online platforms become crucial in defining them as viewers, listeners, readers, or consumers. This raises two major challenges for companies:

1. **How do recommender systems balance personalization with privacy concerns?**
2. **What are the ethical implications of using recommender systems to shape consumer behavior?**

## General Procedure of a Recommender System

Recommender systems typically consist of three key components:

1. **Candidate Generation:** This component generates a reduced subset of items to recommend from a vast pool of thousands. It narrows down the options to a manageable number for further processing.

2. **Scoring Systems:** Since candidate generation can be achieved using various methods, the scoring system standardizes these candidates by assigning a score to each item in the subset, based on multiple factors (e.g., geolocation of available offers).

3. **Re-ranking Systems:** After scoring, the system applies additional constraints and criteria related to the recommendation's objective to refine the list, ultimately producing the final ranked recommendations presented to the user.

the recommendation's objective

