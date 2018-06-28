# visualization_on_cryptocurriencies

Off late, Cryptocurrency has been taking the digital trade world by storm. It has shown the world that becoming a millionaire is not a far-fetched dream. What is commonly perceived is that Cryptocurrency is only about Bitcoins and that they are the only big players in the industry, but is that true? Who are the other coins? What are their shares and volumes? Which coins have seen the biggest Gains and the biggest Losses? What are the trends of these coins? Should you invest in them?
In order to answer all of these Questions Team Animators has put together the following Visualization.

The two major tools we have used for this visualization are Tableau and Excel.
 
In the first part we graphed pie charts for the percentage of market share of all the coins year wise at their max prices. This was done to observe who has the largest slice and who has the smallest.
 
In the second part we analyzed whether Volume and Market Capitalization have an impact on the Value of the Coin. For this, we first graphed the Average Volumes and Average Market Capitalizations for all the coins using packed bubbles in Tableau which helped us visualize the size effectively. We then plotted the same measures as a bar graph and layered it with the current rank of all the coins using color. This helped us visualize the higher ranked coins with respect to Volume and Market Capitalization. Thus we could draw the following insight that highly ranked coins have high Volume and high Market Cap. This is because higher Volume indicates higher demand, which in turn results in higher Market Cap indicating higher value of the coin.
 
In the third part, we wanted to visualize which coins have had the biggest gains and losses so far. For this we first created a calculated field to calculate the Gain Percentage from the Close and Open Values that were provided in the dataset and plotted it for the respective coins. In order to get a better understanding we also plotted a condition to see if the median Gain Percentage was greater than zero which we encoded with color. This gave us a better picture that although ETC, DASH and NEO had the highest gains their median Gain percentage is actually negative.
 
In the Fourth part, we wanted to take the whole visualization a bit further so we plotted a candle stick chart of the coins that had a median gain percentage above zero and trend lines to see the growth potential of the coins.
From the analyses, we could conclude that all the coins have a positive trend and they show good long term potential for growth of coin value.
