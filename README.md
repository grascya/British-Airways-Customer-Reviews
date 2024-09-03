# British Airways Customer Reviews
British Airways (BA) is the flag carrier airline of the United Kingdom (UK). Thousands of BA flights arrive and depart from the UK daily, carrying customers across the world. Whether it’s for holidays, work, or any other reason, the end-to-end process of scheduling, planning, 
boarding, fuelling, transporting, landing, and continuously running flights on time, efficiently, and with top-class customer service is a huge task with many highly important responsibilitiesCustomers who book a flight with BA will experience many interaction points with the BA brand. Understanding a customer's
feelings, needs, and feedback is crucial for any business, including BA..<br>

**Background** In the Context of a British Airways Data Science job simulation taken on Forage, My Task was to scrape, collect customer feedback, review data from a third-party source, and analyze 
this data to present any insights I may uncover. After that, Build a predictive model to understand factors influencing buying behavior. <br>

**Objective**: Scrape and analyze customer review data to uncover findings for British Airways; Build a predictive model to understand factors that influence buying behavior <br>
**Methods Used**: Data Scraping, Exploratory Data Analysis, Data Visualization, NLP, Machine Learning, Predictive Modeling.<br>
**Type of Problem**: Binary Classification Task. <br>
**Language, Libraries, technologies used**: Python, Pandas, WordCloud, TextBlob, NRCLex, Nltk, Matplotlib, Seaborn, Numpy, Scipy, Scikit-learn<br>

## KEY INSIGHTS: 
- Out of the 2000 reviews scraped, 1292 were positive, 694 were negative and 14 were neutral, meaning that 65% of the reviews were positive,
- Crew, food, time, good, and seats were the most common words in the reviews; showing that people are actively talking about their experiences during the flights and the crew
- 94% of reviews classified as positive will recommend British Airways
- Our analysis revealed that 15% of the customers completed their booking, which means that Noncomplete rate is relatively high compared to the completion rate
- Our Model performs very well on unseen data with an accuracy of 0.95, a precision of 0.92, a recall of 0.99, and a f1 score of 0,95. A recall of 0,99 means that our model was able to identify 99% of the time, actual bookings that were completed
- purchase lead, flight hour, and length of stay are the three largest drivers that help the model predict.

