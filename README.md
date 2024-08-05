# DataCo Supply Chain Analytics

- **Goal and Dataset Structure**
- **Insights Summary**
- **Recommendations**
- **Performance Dashboard**
- **Presentation**
 
## Goal:
The goal of this project is to investigate the operational efficiency of supply chains used by DataCo Global to surface recommendations on cost and delivery delay reductions.

## Dataset Structure:
The dataset consisted of one table including information about customers, store locations, shipping locations, delivery status, among other variables. The key features and the table schema are shown below:

![DataCo Table Schema](schema.png)

## Insights Summary:
**In order to evaluate the operational efficiency and analyze sales, we focused on the following key metrics:**
- **Order Fulfillment Time:** Order Shipping Date - Order Placement Date. This helps measure how fast a supply chain can handle shipping.
- **On-Time Delivery Rate:** The percent of deliveries that arrive on-time to their destination.
- **Order Item Profit Ratio:** The profit made from an order divided by the product price of the order before any discounts. This helps assess how profitable an item is relative to its price.
- **Sales Value per Customer:** The average sales value of the purchases made by a customer.

**Order Fulfillment Rate**
- The **Pet Shop department** had the **lowest** average OFT of **3.39 days**. The Discs Shop department had the highest at almost 3.6 days. Both departments had a low number of orders.
- **Same Day** deliveries had the **lowest** average OFT of **0.478 days**, although there were less than 10k orders. Standard Class deliveries had the highest at almost 4 days, but more than 50% of deliveries were shipped with Standard Class.
- **All global markets had a similar average OFT**, with the fastest OFT in US-Canada and the slowest in Africa differing by less than 0.03 days.

**On-Time Delivery Rate**
- The **Discs Shop department** had the **highest** On-Time Delivery rate of **41.43% days**, while only having 839 orders. The Pet Shop department had the lowest at 37%, with only 182 orders.
- **Standard Class** deliveries had the **highest** On-Time Delivery rate of **57.66%**, with over 62k orders arriving on-time. First Class deliveries had the lowest, with no orders arriving on-time.
- **All global markets had a similar average On-Time Delivery Rate**, with the highest in Africa and the lowest in Europe differing only by around 1%.

## Recommendations:
- 
- 
- 

## Performance Dashboard:
The Tableau Public Dashboard can be viewed [here](https://public.tableau.com/views/dataco_supply_chain_analysis/DataCoDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

![DataCo Performance Dashboard](dashboard.png)

## Presentation Samples:
The presentation created for a Logistics and Operations team walks through the insights and recommendations above and can be found [here](https://docs.google.com/presentation/d/1YRsjol2CDJYCgXTLvIrZK1GCY26MXXMTdnmRFiCXFrc/edit?usp=sharing). Some extracts are presented below for easy viewing.

## Data Source:
Constante, Fabian; Silva, Fernando; Pereira, António (2019), “DataCo SMART SUPPLY CHAIN FOR BIG DATA ANALYSIS”, Mendeley Data, V5, doi: 10.17632/8gx2fvg2k6.5