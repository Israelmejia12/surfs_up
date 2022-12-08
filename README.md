# Overview of the analysis: Explain the purpose of this analysis.

An entrepreneur is interested in moving Hawaii, Oahu to follow his dreams and open and an ice-cream shop. However in order to open the shop he needs investors to help him achieve his dreams. He just so happen to know an investor named W. Avy. W.Avy also has a passion on ice cream and surfing and is interested in the investment. Before moving forward however, W. Avy would like to get an analysis on the weather of Oahu because he has knowledge of similar stores that closed in the past, the main reason being the weather and the precepitation. 

## Results: 
### firstthing's first is write a query that filters the measurement table to retrieve the temperatures for the month of June. 
![Graph](https://github.com/Israelmejia12/surfs_up/blob/9fc316d17b4ff57d39dd50b8821de38681fb7523/query%20that%20filters%20the%20Measurement.png)
### Second thing is to extra the temperature for June and convert temperatures to a list. 
![Graph](https://github.com/Israelmejia12/surfs_up/blob/54ab1a1c7a6edca4cc05d7f3df23cbc6a618c3c7/Convert%20June%20temperatures.png)
### The next step is to Create a DataFrame from the list of temperatures. 
![Graph](https://github.com/Israelmejia12/surfs_up/blob/57c0dc547fe9ce75ca982e9a5656a3ae665a548b/Create%20a%20DataFrame.png)
### Next step is is to  create a summary statistics for the June temperature DataFrame
![Graph](https://github.com/Israelmejia12/surfs_up/blob/57c0dc547fe9ce75ca982e9a5656a3ae665a548b/Summary%20of%20June.png)
### Final step is to follow all of the steps above for the month of december and get similar results so that we can make a comparison. 

![Graph](https://github.com/Israelmejia12/surfs_up/blob/57c0dc547fe9ce75ca982e9a5656a3ae665a548b/Summary%20December.png)
![Graph](https://github.com/Israelmejia12/surfs_up/blob/57c0dc547fe9ce75ca982e9a5656a3ae665a548b/Summary%20December.png)


## Summary: The information provided does a good job showing the information us the temperatures in both June and December. I think, however that having a visiual image of the information can help. This is something that can be done using mobplotlib. I would ran a line graph that shows the max, mean, and the min of the temps in order to help see which dates in december and june had the biggest shift. Looking at the data June had a min of of 64 degrees. This would not be a good date to eat ice cream or surf. While it had a max temp of 85 degrees, which in diffrence is a perfect date for ice cream and surfing. Decemenber also had a similar data but the deviation was more extreme, the min was 56 degrees, horroble weather for business, and a max of 83 degrees which again would be the best weather to sorft in. In a future project I would use this kind of data in a graph in order to help investor come up with with a decition. 
