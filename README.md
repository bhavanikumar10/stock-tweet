
# Stock Tweet Group Project

### Inspiration & Motivations

* Social media is changing the way the world is interacting/communicating with each other. Companies are also influenced by the use of social media
* To this end, we wanted to see if we could predict the movement of the stocks based on the sentiments of the stakeholders (company, users, investors, media, analysts).
* We wanted to track the sentiments of what a company was tweeting and what was being tweeted about/at them.
* We compared the sentiment analysis to hourly stock prices to see if there was any correlation.
* If there is correlation, we thought it might be possible to predict stock activity!
* We took a company from each market capitalization structure to study the influence of social analytics on their stock price movement.
* We decided to focus on the tech industry because it seems to depend heavily on branding and user sentiment.
* We chose Facebook for large-cap Stock, Nintendo for a mid-cap stock and MindBodyOnline for a small-cap stock.


### Data Collection

* We first started to collect tweets from Facebook, tweets directed to Facebook, tweets with #facebook.
* As we were doing our research, we came across “cashtags”. They are similar to a regular hashtags, but specific to stock tickers. So we included them in our tweet gathering.
* After getting all the tweets and graphing the data, we compared it to a graph of the stock activity for the day (from Yahoo Finance) and the stock performance over a period of time.
* Then we selected a mid cap company (Nintendo) and a small cap company (MINDBODY), and gathered the same information.
* Because there are such a vast amount of tweets and we only had so much time, we only grabbed data for three days for Facebook and two days for the other company.
* With more time (and more efficient code) we would have a better idea of what the data is saying and how to apply that to stock prices.


### What We Learned...

* On some of the days, public sentiment did loosely correlate with intraday movements in the stock price, which suggests that there is potential in social analytics to gain some insight into intraday stock performance.
* Many more variables would need to be included in any predictive model that considers social analytics.
    * For example, second-by-second trading and minute-by-minute stock prices would be very useful, but this data is very expensive.
* Ultimately, there are good reasons to be interested in this type of analysis, but it would take a dedicated team of data scientists with access to institutional resources to effectively develop it.
