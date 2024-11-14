# Mobile Service Preference Analysis

This project analyzes the preferences of customers for mobile service attributes, focusing on factors such as brand, internet capacity, service support, and pricing. The goal is to determine the most preferred mobile service attributes and evaluate the relative importance of each attribute in customer decision-making.

## Key Insights
- **Most preferred brand**: Verizon  (Rescaled Utility: 12.71)
- **Most preferred internet capacity**: 20 GB (Rescaled Utility: 92.16)
- **Most preferred support level**: Premium support (Rescaled Utility: 19.41)
- **Most preferred price**: $40 (monthly charge) (Rescaled Utility: 43.56)
- **Most important attribute**: Internet Capacity (Importance Score: 46.07%)

## Detailed Utility Scores

### Brand Preferences:
- **AT&T**  (Rescaled Utility: -12.59)
- **T-Mobile**  (Rescaled Utility: -0.11)
- **Verizon** (Rescaled Utility: 12.71)

### Internet Capacity Preferences:
- **7 GB** (Rescaled Utility: -89.08)
- **12 GB** (Rescaled Utility: -3.08)
- **20 GB** (Rescaled Utility: 92.16)

### Support Preferences:
- **Premium support** (Rescaled Utility: 19.41)
- **Regular support** (Rescaled Utility: -1.42)
- **Basic support** (Rescaled Utility: -17.98)

### Price Preferences:
- **$40** (Rescaled Utility: 43.56)
- **$50** (Rescaled Utility: 7.96)
- **$60** (Rescaled Utility: -51.52)

## Attribute Importance Scores:
- **Brand** (Importance Score: 0.15%)
- **Internet Capacity** (Importance Score: 0.46%)
- **Service Support** (Importance Score: 0.14%)
- **Price for a single line** (Importance Score: 0.25%)

## Model Fit Metrics
- **Average RLH**: 0.657
- **Standard Deviation RLH**: 0.165
- **Min RLH**: 0.231
- **Max RLH**: 0.919

## Key Findings
- **Model Fit**: The average RLH of 0.657 indicates good model fit.
- **Most Important Attribute**: Internet Capacity (46.07% importance score).
- **Strongest Preference**: Verizon with a rescaled utility of 12.71.
- **Strongest Preference in Internet Capacity**: 20 GB with a rescaled utility of 92.16.

## Dataset Information

### Rescaled Utilities
The rescaled utilities of various options (e.g., brand, internet capacity, service support, and price) are provided for each record ID in the dataset. These values represent the preference score for each attribute at a given level.

### Raw Utilities
Raw utility values for each attribute are also included to showcase the unadjusted preference score for each attribute.

### Importance Scores
Importance scores indicate how much weight each attribute has in the decision-making process for customers.

## Usage

1. Clone the repository to your local machine.
2. Use the dataset provided in the `data/` directory for further analysis or modeling.
3. Analyze the utility scores to understand customer preferences and make data-driven decisions.

## Contributing

Feel free to contribute by submitting pull requests or opening issues for suggestions and improvements.
