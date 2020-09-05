# Retail Analytics of ABC SME

## Problem Statement 
- What opportunities exists for <b>ABC(SME)</b> start up after seeing `revenue fallen by 25%` during 1st half of 2018 compared to 2017 data to bring <b>revenue losses by 0% </b> at the end of 2018 through `new product and delivery strategy` or `closing stores at low revenue`? 
- A brief documented [Problem Statement](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Capstone%202%20PS%5BMonisha%20Anila%5D.pdf)

## Context
- ABC start up became the leading SME in London for online retail industry after seeing  <b>€ 448000 during 2017</b> and it has been voted as `“choice for customers”`.
- Due to unknown product issues and delivery speeds the <b>customer base has been decreased tremendously</b> during 2018.
- To avoid these disadvantages the company held urgent meeting to solve both `product and delivery issues` across their stores. 

## Success critiera 
- To implement a new product and delivery strategy to bring `revenue losses by 0%` at the end of <b>2018</b>. 

## Scope of solution 
- Statistics- [`Python`](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Statistics.ipynb) and [`Tableau`](https://public.tableau.com/profile/monisha.anila#!/vizhome/RetailAnalytics_15972219055200/Final)
- Customer strategy – [`Out Of Stock analysis`](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Demand%20Forecast.ipynb)
- Market strategy – [`Optimised Price for products`](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Optimised%20Price.ipynb)
- Product divestment – [`Customer segmentation`](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Customer%20Segmentation.ipynb) , [`Recommendation system`](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Market%20Basket%20Analysis.ipynb) and [`Demand Forecast`](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Demand%20Forecast.ipynb)
- <b> Note: Light GBM is used for both out of stock analysis and demand forecast </b>

## Constraints in solution 
- `Outlier removal from data` 
- `Granular product strategy enrolment`

## Stake holders
1. <b>Product Manager </b>
2. <b>Sales Manager </b>
3. <b>Regional Manager </b>

## Data Source 
1. [Original data](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Data.csv)
2. [Segmented data](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Segmentdata.csv)

## Presentations
1. [`Executive`](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Capstone%202%20Executive%20%5BMonisha%20Anila%5D.pdf)
2. [`Technical`](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Capstone%202%20Technical%20%5BMonisha%20Anila%5D.pdf)
3. [`Non Technical`](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Capstone%202%20Non%20Technical%20%5BMonisha%20Anila%5D.pdf)

## Issue Tree 
- <b>MECE principle </b> A brief documented [Issue Tree](https://github.com/monisha-anila/Springboard-India/blob/master/Capstone%202/Capstone%202%20IT%5BMonisha%20Anila%5D.pdf)
1. `Customers are leaving`
2. `We're making customers leave`
3. `Future work`

### Awesome tips
- You can view Jupyter notebook data within seconds by pasting Github link [here](https://nbviewer.jupyter.org/). 
- `pd.factorise` is used in place of `get_dummy` which makes easier data encoding.
- `pd.qcut` makes bins with quantile distribution
- Use `Pandas profiling` to get data overview within minutes.
