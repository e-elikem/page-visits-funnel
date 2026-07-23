# Page Visits Funnel Analysis

An analysis of customer behavior through a retail website conversion funnel. This project tracks users from initial page visit through purchase, identifying dropoff points and calculating conversion rates at each stage.

## 📋 Project Overview

This project analyzes user journey data through an e-commerce website funnel to understand:

- How many visitors progress to each stage (visit → cart → checkout → purchase)
- Where customers are dropping off in the conversion process
- Conversion rates and completion percentages at each funnel stage
- Opportunities to optimize the customer journey

**Goal:** Build a funnel analysis to identify bottlenecks and optimize the purchase conversion process.

## 🛍️ The Funnel Stages

```
Stage 1: Website Visit
         ↓
Stage 2: Add to Cart
         ↓
Stage 3: Proceed to Checkout
         ↓
Stage 4: Complete Purchase
```

Each stage represents a critical milestone in the customer journey. Users who don't progress to the next stage represent **conversion losses** that should be investigated.

## 📁 Project Structure

```
page-visits-funnel/
├── README.md                     # This file
├── page_visits_funnel.ipynb      # Complete analysis notebook
├── visits.csv                    # Stage 1: All website visitors
├── cart.csv                      # Stage 2: Users who added items to cart
├── checkout.csv                  # Stage 3: Users who proceeded to checkout
└── purchase.csv                  # Stage 4: Users who completed purchase
```
