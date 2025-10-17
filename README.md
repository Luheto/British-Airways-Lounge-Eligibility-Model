# British Airways Lounge Eligibility Model

## Overview
This project develops a lookup table that British Airways can use to estimate lounge eligibility percentages across different flight groupings, allowing the business to anticipate lounge demand without needing exact flight or aircraft details.

## Business Problem
Lounge access is a key part of the premium travel experience, and understanding lounge demand is crucial for British Airways to maintain high standards while optimizing space and resources. As the airline plans for future operations at Heathrow Terminal 3, it's important to anticipate demand across different types of lounge access, each associated with varying levels of customer loyalty and travel class.

Future schedules can be unpredictable, which means we need a modeling approach that is both flexible and scalable. The goal is to create a lookup table that BA can use to estimate lounge eligibility percentages across different flight groupings, allowing the business to anticipate lounge demand without needing exact flight or aircraft details.

## Methodology
To create an effective model, flights are grouped in meaningful ways—by time of day, route type, or regional destination—and logical assumptions are applied to estimate how many travelers fall into each lounge tier. This approach helps the Airport Planning team better understand where lounge investments may be needed as operations evolve.

## Key Findings

### Lounge Eligibility Lookup Table

#### Long-Haul Flights
| Time Period | Destination | Tier 1 % | Tier 2 % | Tier 3 % |
|-------------|-------------|----------|----------|----------|
| Afternoon | Asia | 0.2% | 2.7% | 10.8% |
| Afternoon | Middle East | 0.2% | 2.8% | 10.2% |
| Afternoon | North America | 0.2% | 2.8% | 10.5% |
| Evening | Asia | 0.2% | 2.6% | 10.0% |
| Evening | Middle East | 0.2% | 2.7% | 10.4% |
| Evening | North America | 0.2% | 2.8% | 10.5% |
| Lunchtime | Asia | 0.2% | 2.7% | 10.3% |
| Lunchtime | Middle East | 0.2% | 2.6% | 10.0% |
| Lunchtime | North America | 0.2% | 2.7% | 10.3% |
| Morning | Asia | 0.2% | 2.6% | 10.2% |
| Morning | Middle East | 0.2% | 2.8% | 10.6% |
| Morning | North America | 0.2% | 2.8% | 10.8% |

#### Short-Haul Flights (Europe)
| Time Period | Tier 1 % | Tier 2 % | Tier 3 % |
|-------------|----------|----------|----------|
| Afternoon | 0.3% | 4.3% | 16.6% |
| Evening | 0.3% | 4.5% | 17.0% |
| Lunchtime | 0.4% | 4.5% | 17.3% |
| Morning | 0.3% | 4.4% | 16.7% |

### Key Insights
- **Long-haul, afternoon period**: Flights to Asia have the most business class clients and the least BA gold member clients
- **Long-haul, lunchtime period**: Flights to North America have the most BA gold member & business class clients, while Asia has the least BA gold member clients
- **Long-haul, evening period**: Flights to the Middle East have the least BA gold member clients
- **Short-haul flights**: Show highest demand for Business Class clients, followed by BA gold members, with first class client accommodation being the least at all time periods
- **Peak periods**: Lunchtime and evening periods show the highest eligibility percentages across most categories

## Business Applications
This lookup table enables BA to:
- Estimate lounge eligibility percentages across different flight groupings
- Anticipate lounge demand without exact flight details
- Make informed decisions about lounge investments and resource allocation
- Maintain flexibility for future schedule changes and fleet strategy

## Project Output
The primary deliverable is a reusable lookup table that translates data into decisions, ensuring BA continues to deliver a seamless experience for its most valued customers at Heathrow Terminal 3.

---
*Developed as part of the British Airways Virtual Experience Program*
