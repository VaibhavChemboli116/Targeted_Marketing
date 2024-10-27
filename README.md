Project Overview

This project analyzes SMARTMARKET's targeted marketing strategy, specifically focusing on a structured campaign delivery system. SMARTMARKET conducts campaigns over a period of 26 weeks, delivering personalized campaign content to subscribers on a rotational basis. This analysis aims to optimize marketing effectiveness by selecting campaigns to each user and predicting response rates.

Campaign Structure and Data Description

SMARTMARKET operates a weekly campaign delivery system as follows:

Week 1: Each campaign (1-10) is delivered to 1/10th of the subscriber base, ensuring each subscriber receives only one campaign.

Subsequent Weeks (2-26): Campaigns are rotated each week so that subscribers receive a new campaign in sequential order, ensuring exposure to all 10 campaigns over multiple cycles.

Weekly Rotation Pattern: The rotation continues over a 26-week period, allowing each subscriber to engage with every campaign.

Data Columns

The dataset consists of the following columns:

week_number: Week of the campaign delivery (1-26).

subscriber_id: Unique identifier for each subscriber.

user_category: User's category based on demographic criteria (A, B, C, D).

state_id: Code representing the subscriber's location (150 unique states).

gender: Gender of the subscriber (M, F).

campaign_id: Unique identifier for each campaign.

response: Indicates whether the user responded to the campaign (0, 1).

