**This project aims to determine the optimal Dense medium separation (DMS) capacity for a greenfield mining operation by maximizing Net Present Value (NPV) based on a mining plan. The project analyzes the impact of different plant capacities ranging from 0.5 Mt to 2 Mt tons per year on NPV calculation by considering the following key variables:**

- Variable Mining Unit Costs: Mining unit costs are adjusted based on different mining capacities, reflecting economies of scale and potential cost increases.
- Variable Yield Values: Yield values change depending on the ore grade, accounting for varying ore characteristics and processing efficiencies.
- Variable Processing Costs: Processing costs are adjusted based on the ore grade, reflecting variations in processing requirements and cost per ton processed.
- Fluctuating Product Selling Prices: The project incorporates varying product selling prices to account for market volatility and price fluctuations.
- Variable Investment Costs: Investment costs are calculated for different plant capacities, reflecting the investment required for equipment, infrastructure, and other fixed assets.
- Loan Repayment: Loan repayment schedules are integrated for the plant investment, simulating the impact of debt financing on cash flow.

**Calculating these variables based on the chosen annual production capacity, the project ultimately determines the total NPV. This analysis helps to identify the most profitable plant capacity for the mining operation. To achieve this, we did analyze the NPV for production capacities ranging from 0.5 Mt to 2 Mt tons in increments of 100,000 tons, with 1,000 iterations performed for each capacity value. This will provide a comprehensive understanding of the NPV profile across different plant sizes.**

![Ekran görüntüsü 2024-07-18 225740](https://github.com/user-attachments/assets/2408c6e5-43a3-404b-b01e-1a2702c33dc1)

**The ore grade and tonnage values for the mine site are provided in the table. As an initial step, the Python code block below will be used to mathematically model the objective function. This will calculate the NPV value for the "initial_annual_production_ton" variable, which will be set to 0.5 Mt and 2 Mt respectively. In the second phase, the quantity of product to be extracted for each ore grade range is calculated based on the recovery rate. Then, using the prevailing ore sales price for each year over a 20-year period, net revenue and net present value are determined for each grade range.**

![newplot](https://github.com/user-attachments/assets/59051890-3ec0-426a-a5f9-325f28767ef1)

In the third phase, we analyzed the NPV for production capacities ranging from 0.5 Mt to 2 Mt in increments of 100,000 tons, with 1,000 iterations performed for each capacity value. This analysis provides a comprehensive understanding of the NPV profile across different plant sizes.

![npv](https://github.com/user-attachments/assets/f5b65716-1fb3-4cb0-99e8-eeba06526086)
