In this project i will use the data "Toy Store E-Commerce Database" from maven analytics to conduct a __Sales Analysis__. You can find the data [here](https://mavenanalytics.io/data-playground/toy-store-e-commerce-database).
I clean the data, explore it, identify problems and will visualize key messages.

# E-Commerce Sales Analysis
__Tools:__ Python, pandas, matplotlib, seaborn  <br>
__Dataset:__ 7 CSV files covering orders, products, refunds and web traffic  <br>
__Goal:__ Identify revenue trends, top products, refund risks and traffic performance <br>
__Keywords__: Time series analysis, Product analytics, Risk analysis, Marketing analytics, Web analytics
<br>



# Data Loading and Exploring
Here I have a first look at the data. To get a first impressive of the data set I use the .shape .head() .describe() and .info() methods.

<br>


|  |  |
| :---: | :---: |
| <img width="871" height="347" alt="grafik" src="https://github.com/user-attachments/assets/edf55b90-8684-4643-a96b-c432e94ee146" /> | <img width="811" height="458" alt="grafik" src="https://github.com/user-attachments/assets/965e9c16-48c5-454f-a312-d505367e01ef" /> |
| .shape | .head() |
| <img width="853" height="537" alt="grafik" src="https://github.com/user-attachments/assets/63a540e8-ec3e-4e80-bdce-e08d24a37324" /> | <img width="807" height="444" alt="grafik" src="https://github.com/user-attachments/assets/327e9a38-c2c1-45cf-a807-68d28884c869" /> |
| .describe(include = "all") | .info() |
<br>
Now we got a first impression about our data.
<br>
<br>

# Data Cleaning

|  |  |
| :---: | :---: |
| <img width="1118" height="807" alt="grafik" src="https://github.com/user-attachments/assets/281a8c06-996a-4348-a8e9-4e672aad3617" /> | <img width="868" height="803" alt="grafik" src="https://github.com/user-attachments/assets/b1a79b2f-76c3-4616-88f0-e44db8a9224b" />|
| A example of 'manual' data cleaning | The data cleaning of all our data |
<br>

The result: Clean data, without any dublicates and missing data is replaced with the mean value.
<br>
<br>

# Analysis and Visualization

## Revenue Sales
<br>
<img width="1389" height="590" alt="grafik" src="https://github.com/user-attachments/assets/3b3b2299-6b1c-48f6-93fb-707a9f0797f7" />
<br>
Revenue is growing untill 2015 and declined then sharply. The Profit margin is stable. 
<br>
<br>
<img width="1389" height="390" alt="grafik" src="https://github.com/user-attachments/assets/18545112-1c61-4059-a9f9-4db4d765bcfb" />
<br>
Monthly order figures have been rising steadily and at an ever-increasing rate since May 2014. Since 2015, monthly order figures have been falling.
<br>
<br>
<img width="1389" height="390" alt="grafik" src="https://github.com/user-attachments/assets/3df1ae38-0d7c-499c-9d9b-657dc04b5526" />
<br>
<br>

## Products
<br>
<img width="1389" height="590" alt="grafik" src="https://github.com/user-attachments/assets/e0adac83-2a5f-4db9-a775-02ceae5001cc" />
<br>
<img width="851" height="109" alt="grafik" src="https://github.com/user-attachments/assets/7a96e579-6e07-4996-a101-359f5f679777" />
<br>
By far the best-selling product with the highest total revenue is “The Original Mr. Fuzzy” at $1,211,057.74, compared to the total revenue of the remaining products, which amounts to $727,452.01. “The Original Mr. Fuzzy” contributed the most to the total profit, at $738,893.00. Nevertheless, the profit margin is higher for the other products: it stands at 68.4% for “The Birthday Sugar Panda” and “The Hudson River Mini Bear”, compared to 61.0% for “The Original Mr. Fuzzy”.
<br>
<br>

## Refunds
<br>
<img width="1389" height="590" alt="grafik" src="https://github.com/user-attachments/assets/36f513d0-b705-432b-abf2-940c305887e6" />
<br>
We can see that "The Birthday Sugar Panda" is losing the most revenue in percentage terms (6.04%). In absolute terms, "The Original Mr. Fuzzy" is in the lead ($1,211,057.74), and it also ranks second in percentage terms (5.11%). "The Hudson River Mini Bear" performs the best, with 1.28%. "The Original Mr. Fuzzy" also has higher monthly fluctuations in its monthly return rate, but has stabilized since September 2013 at just under 4% (with a dramatic outlier in September 2014 at nearly 14%).
<br>

## Traffic and Conversion
<br>

<img width="1189" height="490" alt="grafik" src="https://github.com/user-attachments/assets/8a38eccd-22ee-4a22-b6dd-4b4d3569fee5" />
<br>
<img width="1189" height="490" alt="grafik" src="https://github.com/user-attachments/assets/c245b636-a746-4f9f-8656-6d48f8a5f79f" />
<br>
<img width="1189" height="490" alt="grafik" src="https://github.com/user-attachments/assets/df056da8-9273-4ce1-810a-f65cfb835c68" />

"gsearch" generate by far the most sessions. "bsearch" and "gsearch" are the main drivers of the monthly conversion rate (7,19% and 6,75%) and also generate the most revenue (revenue per session: 4,28% and 4,04%).
<br>
<br>

# Key Findings
<br>
<img width="785" height="144" alt="grafik" src="https://github.com/user-attachments/assets/ed849835-0190-4e88-8ff3-fa7407168215" />
<br>
<br>
<img width="862" height="145" alt="grafik" src="https://github.com/user-attachments/assets/e0624f77-07d9-4888-b7a3-7dbc974f506c" />







