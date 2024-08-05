# **Overview**

Bolt is a company that offers ride-hailing, electric scooter and bike rentals, food delivery, car rentals, business services, financial technology solutions, and courier services through its versatile super app. In this project, our primary focus lies on ***Bolt Business***, the B2B arm of Bolt. We aim to extract valuable ***insights*** from acquisition and ordering data to formulate ***strategic growth recommendations*** for Bolt's Business country managers, directors and VP.


  # **Data Sources**
  
  - [Acquisitions Data](https://github.com/Ayman947/EDA-for-Strategic-Business-Growth/blob/main/Analysis%20Data/data-acquisition.xlsx)
      - Region: geographical location of the company (ex: Seraphica, Valoria, ...etc)
      - Acquisition Channel: how the company was acquired (ex: Marketing, Outreach, ...etc)
      - Segment: company performance tier  (ex: T1, T2, ...etc)
      - Acquisition Month: the month when the companies signed up  (ex: 2024-02, 2024-10, ...etc)
      - New Companies: number of companies that signed up  (ex: 5, 2, 15, ...etc)
  
  - [Ordering Data](https://github.com/Ayman947/EDA-for-Strategic-Business-Growth/blob/main/Analysis%20Data/data-ordering.xlsx)
      - Region, Acquisition Channel, Segment (as defined above)
      - Order Month: the month when an order was placed  (ex: 2024-05, 2024-12, ...etc)
      - Active Companies: number of companies with at least one completed order (ex: 7, 18, ...etc)
      - Revenue: generated revenues (ex: 163, 59.44, ...etc)
      - Orders: number of completed orders (ex: 22, 36, ...etc)


  # **Environment** & **Packages**

  | Package Name | Functionality                 |
  |--------------|-------------------------------|
  | pandas       | Data Manipulation             |
  | numpy        | Numerical Calculations & Array Manipulations   |
  | matplotlib   | Data Visualization            |
  | seaborn      | Data Visualization            |
  | missingo     | Inspecting & visualizing missing values |


  # **Data Cleansning & Preprocessing**

  - Merging acquisition and ordering data into a unified analytical dataset.
  - Renaming columns to lowercase with underscores (i.e. to follow a consistent convention).
  - Inspecting and dealing with null values.
  - Inspecting and dealing with duplicates.
  - Casting columns to relevant data types.
  - Sorting the data for clarity and logical order of patterns.
  - Computing monetization KPIs: Average Order Value (AOV) and Average Revenue Per User (ARPU).


  # **EDA Key Insights**

   ![KPIs](https://github.com/Ayman947/EDA-for-Strategic-Business-Growth/blob/main/Images/kpis.PNG)
   ![Acquisitions per Channel](https://github.com/Ayman947/EDA-for-Strategic-Business-Growth/blob/main/Images/acquisitions%20per%20channel.PNG)
   ![Acquisitions per Region](https://github.com/Ayman947/EDA-for-Strategic-Business-Growth/blob/main/Images/acquisitions%20per%20region.PNG)
   ![Acquisitions per Region & Channel](https://github.com/Ayman947/EDA-for-Strategic-Business-Growth/blob/main/Images/acquisitions%20per%20region%20and%20channel.PNG)
   ![Segments Profitability](https://github.com/Ayman947/EDA-for-Strategic-Business-Growth/blob/main/Images/segments%20profitability.PNG)
   ![Monthly Revenues & Orders](https://github.com/Ayman947/EDA-for-Strategic-Business-Growth/blob/main/Images/monthly%20revenues%20%26%20orders.PNG)


  # **Recommendations**
![Strategic Recommendations](https://github.com/Ayman947/EDA-for-Strategic-Business-Growth/blob/main/Images/strategic%20recommendations.PNG)



  # **Conclusion**
In summary, our analytics project has yielded **actionable strategic recommendations** for driving Bolt Business growth, focusing on **acquisition optimization** and **profitability maximization**.



  # **Appendix**
  
  - [Presentation Slides](https://docs.google.com/presentation/d/19CLk_pnv4ATStA7liKf7NS4Mb5Tsv4qs9m-782pUUK4/edit?usp=sharing)
  - [Analysis Notebook](https://colab.research.google.com/drive/1WqzR5eXR7Jf0dhxlmApou--V21oHz98W?usp=sharing)
