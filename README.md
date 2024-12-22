# Balance-of-Payment-Analysis
## Contributors
#### Data Analysts
- [Shahzada Husnain](https://github.com/ihusnainmehar)

## Project Overview
The Balance of Payments (BoP) is a financial statement that summarizes a country's economic transactions with the rest of the world over a specific period. It consists of three main components:
- **Current Account:** Tracks trade in goods and services, income from investments, and remittances.
- **Capital Account:** Records transfers of financial assets, such as investments or grants, between countries.
- **Financial Account:** Captures changes in ownership of international assets, including foreign investments and reserves.

This project provides a comprehensive analysis of the Balance of Payments and the economic performance of five European countries: Albania, Austria, Belgium, France, and Germany. Using these components, the project highlights key trends such as trade balances, capital inflows, and investment dynamics, offering valuable insights into these nations' economic activities.
## Tools Used
- Google Sheets: For Data Extraction
- Excel: For Data Preparation and Transformation
- Microsoft SQL Server: For Querying
- Power BI: For Visualization
## Steps Taken
### Data Extraction
- The developers extracted the Balance of Payment dataset from the [IMF Website](https://data.imf.org/regular.aspx?key=62805740) using Google Sheets 
### Data Transformation:
- The original dataset was transformed for better usability.
- Checked for duplicates and standardized the data using SQL.
### Data Modeling:
- Established relationships between tables to ensure seamless analysis.
![Data Modeling](https://github.com/user-attachments/assets/0b867666-6380-4ac3-879a-f7d65032d668)
### Calculated Columns:
- Created calculated columns in Power BI to derive additional insights and support key metrics.
### Dashboard Development:
- Designed and built an interactive financial dashboard in Power BI to visualize economic trends and performance.
## Key Insights
### Albania
![Albania](https://github.com/user-attachments/assets/d1159a1a-cadd-44cc-a570-dec92eba486a)
Albania's Capital Account had a surplus, with a sharp increase in 2021. This was due to the capital account credits exceeding the capital account debits, which indicates that more capital is flowing into the country than going out. 
- Albania experienced a Current Account Deficit. The deficit results from a negative balance on goods and services, as the imports exceed exports significantly. While primary income (like earnings on investments) and secondary income (such as remittances) are positive, they are insufficient to offset the trade deficit.
- Financial Account Deficit: This deficit is driven by negative contributions from direct investment and other investments, with consistent downward trends. These components suggest that more money is leaving Albania through investments than coming in, leading to a net outflow of financial resources.
### Austria
![Austria](https://github.com/user-attachments/assets/220ed203-4a65-4361-b0f6-bf17dff008f3)
Austria experienced a deficit in its Capital Account but a Surplus in 2023. The consistent deficit over the years is attributed to high capital account debits, which indicate outflows of capital. In 2023, there was a surplus, where credits surpassed debits, marking a shift towards a net inflow of capital.
- Current Account Surplus (Deficit in 2022). The primary contributor to the surplus is the balance of goods and services, where exports exceed imports. In 2022, the deficit in the balance of goods and services led to a current account deficit, possibly due to increased imports or a decline in export performance.
- Financial Account Surplus (Deficit in 2022). The surplus arises from positive portfolio investments and other investments, indicating a net inflow of financial resources. In 2022, there was a deficit caused by negative other investments, meaning outflows in this segment exceeded inflows.
### Belgium
![Belgium](https://github.com/user-attachments/assets/012d6d44-6088-4f33-911b-dd927e810676)
- Belgium has experienced a capital account surplus since 2016, except for 2020. The capital account surplus is due to capital account credits exceeding debits. There was also a sharp increase in the capital account surplus in 2012.
- Primary income has been the main driver of the current account surplus in Belgium for several years, while secondary income has been the primary cause of the current account deficit in some years.
- Financial Account Fluctuations: Direct and other investments primarily drive the financial account surplus, while portfolio investment is the main driver of the deficit. The volatility of portfolio investments reflects their sensitivity to economic and market conditions.
### France
![France](https://github.com/user-attachments/assets/1e90d8f1-6e06-4e98-a955-1ee821fbb811)
- France has consistently experienced a Capital Account surplus, with a notable increase in 2021. While there was a slight dip in 2016, the overall trend shows a positive balance. This surplus indicates that the country has been attracting more capital inflows than outflows.
- Current Account deficit, with some fluctuations over the years. This indicates that the country's imports have exceeded its exports. A negative balance of goods and services and secondary income primarily causes the deficit. While primary income (e.g., remittances, wages) shows a positive balance, it's not enough to offset the deficit.
- Financial Account Deficit: This means that the country's financial outflows have exceeded its inflows. Negative contributions from Portfolio Investments and Other Investments primarily drive the deficit.
### Germany 
![Germany](https://github.com/user-attachments/assets/d731d0c4-876a-4b89-81e9-225e405b0345)
Germany's capital account was in deficit except in 2010 and 2014 when there was a slight increase in surplus. This indicates that the country has had more capital outflows than inflows.
- Current Account Surplus: This indicates that the country's exports have exceeded its imports. Positive balances from goods and services primarily drive the surplus. The primary income is also able to offset the negative balance from secondary income.
-  Financial Account surplus. This means that the country's financial inflows have exceeded its outflows. All investment accounts showed consistent positive balances, with Portfolio Investment being the major contributor to the surplus. This was sufficient to offset the fewer deficits arising from other years.
### Comparative Analysis
![Comparative Analysis](https://github.com/user-attachments/assets/ec039165-192f-46ac-8e5c-99f96cdcff64)
- The capital account balances indicate that France has had surplus years, Germany has had deficit years, and Albania has maintained a relatively stable surplus.
- The current account balances indicate that Germany has consistently had a current account surplus, reflecting its strong export-oriented economy. Austria has also had surplus years. Meanwhile, Albania has had deficit years, and Belgium and France have experienced fluctuating current account balances.
- The financial account balances indicate that Germany has consistently had a financial account surplus, reflecting strong foreign investment inflows. Austria has also had surplus years, while the other countries have experienced fluctuating financial account balances.
## Recommendations
- Countries facing capital account deficits should implement policies to attract foreign investment, improve the investment climate, and reduce capital outflows. Even countries with consistent current account surpluses should prioritize fostering a business-friendly environment, implementing sound economic policies, and attracting foreign direct investment.
- Countries with persistent current account deficits, like Albania, Belgium, and France, should implement strategies to improve export competitiveness, diversify their export base, and control imports. These strategies could involve investments in education and training, promoting innovation, and implementing supportive trade policies. 
- Countries with strong financial account surpluses, like Germany, should implement policies to stimulate domestic investment and curb capital outflows. This could involve offering tax incentives, investing in infrastructure, supporting SME growth, and promoting domestic savings. For countries with financial account deficits, attracting foreign investment, ensuring financial stability, and managing debt levels are essential.
