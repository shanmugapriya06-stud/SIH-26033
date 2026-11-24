# Smart India Hackathon Workshop
# Date:24/11/26
## Reference Number:26009333
## Name:Shanmugapriya R P

## Problem Title :

SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization : 

Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description

Multiple intermediaries between farmers and consumers can reduce the share of the final price received by farmers and increase the price paid by consumers. Farmers may also lack reliable access to buyers, current market prices, transport, and payment information.


## Proposed Solution
FarmLink Direct is a mobile and web platform that helps farmers sell produce directly to consumers, retailers, restaurants, and institutional buyers. It brings together product listings, buyer requests, transparent pricing, logistics coordination, and digital payments in one place.

The platform does not need to remove every intermediary. Instead, it helps farmers and buyers find more direct, transparent trading options while allowing useful services—such as aggregation, storage, transport, and quality checks—to remain available.

A key feature is Demand-Based Group Selling: when one farmer cannot fulfil a large order, FarmLink can combine suitable produce from nearby farmers or an FPO. This can help farmers reach larger buyers and coordinate shared collection and delivery.

<img width="1212" height="876" alt="Screenshot 2026-11-24 153810" src="https://github.com/user-attachments/assets/41333662-fbca-4208-8988-782da5366238" />

  ## Inovation and uniqueness:
  
FarmLink combines local produce listings, buyer requests, transparent offer comparisons, group selling, and delivery coordination. Its Fair-Price View shows the farmer’s expected net earnings after visible costs such as transport and platform charges. A Demand Match Alert can notify nearby farmers or FPOs when buyer demand matches their listed produce.


## Technical Approach

Suggested technologies:

- Frontend: React or a mobile-friendly web app
- Backend: Python with FastAPI
- Database: PostgreSQL
- Maps and routes: OpenStreetMap with a routing service
- Forecasting: Python and scikit-learn, introduced after enough reliable data is available
- Notifications: SMS or in-app notifications

Implementation process:

1. Register farmers, FPOs, and buyers.
2. Let farmers list produce and buyers post requirements.
3. Match listings with buyer requirements by crop, quantity, location, and availability.
4. Show offers, estimated delivery costs, and the farmer’s expected net amount.
5. Allow farmers or FPOs to combine produce for eligible bulk orders.
6. Coordinate pickup and delivery, then record order and payment status.
7. Use completed transactions to improve matching and, when sufficient data exists, demand estimates.

  
## Feasibility and Viability:

The marketplace and routing are ordinary engineering with mature libraries, and commodity price data is published daily by Agmarknet so the demand and price side has a real public source, but you have no order history to forecast demand from and no actual farmers or vehicles, so the two-sided liquidity the whole model depends on is simulated.
A prototype can be built with standard web technologies and a small sample dataset. A pilot could focus on one crop and local area, working with a few farmers or an FPO and a small group of buyers. The initial version can use manual or rules-based matching; forecasting can be added when enough trustworthy sales data is available.


 
## Impact and Benefits

Potential Impact on the Target Audience

Farmers gain direct market access and better price visibility. Consumers and bulk buyers gain easier procurement, while FPOs benefit from improved supply coordination.
 
- Farmers: More buyer options, clearer offers, and visibility into expected net earnings.
- Consumers and businesses: Easier access to nearby produce and clearer pricing.
- FPOs: Tools to aggregate supply and coordinate orders.
- Supply chain: Better coordination may reduce avoidable trips, delays, and unsold produce.

- 
## Research and References
Smart India Hackathon Official Website: [https://sih.gov.in/](https://sih.gov.in/)

feasability and viability:https://www.sihbuddy.in/ps/SIH26033

FastAPI Documentation: https://fastapi.tiangolo.com/

