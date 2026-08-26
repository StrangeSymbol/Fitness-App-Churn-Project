# Fitness-App-Churn-Project

In this project, we assume we have a Fitness Gym business; the retention team would like to know, given its user data, deliver a table of churn probabilities and expected revenue at risk given the various subscription prices: Basic - $9.99 per month; Premium - $19.99 per month; and Elite - $29.99 per month.

"Churn" means a customer cancelling or stopping their subscription — leaving the service entirely.

The word comes from the idea of customers "churning" in and out of a business — like butter being churned, constantly turning over. It's used broadly across subscription businesses: streaming services (Netflix), SaaS products, gyms, phone plans, subscription boxes — anywhere revenue depends on people staying subscribed month over month rather than making a one-time purchase.

**Why it matters so much to companies:** 

Acquiring a new customer is typically far more expensive than retaining an existing one (ad spend, onboarding costs, etc.), so a small reduction in churn rate can have an outsized impact on revenue. That's exactly why "churn prediction" is such a common real-world Data Scientist project.

What this project does:

Build the complete pipeline: SQL feature engineering → PyTorch model → business-ready output.

Using the following skills:

`SQL`: filtering, aggregating, joins (inner and left), CTEs, subqueries, window functions, and a self-join for rolling windows — assembled into a real feature-engineering query\
`Pandas`: bridging SQL output into one-hot encoded, properly typed numeric data\
`PyTorch`: tensors, a neural network with Linear/ReLU/Dropout, a training loop with gradients and backpropagation, class-imbalance handling, and proper train/test evaluation\
`Business translation`: converting a probability into an actual prioritised dollar-value output
