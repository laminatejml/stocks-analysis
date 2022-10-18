# Stocks-Analyis
### Finding Optimal Green Stock Options for Steve's Parents
##### Overview
Hello Steve, this readme is in regards to an update on your request to optimize your stock analysis. In response to this I have refactored the pre-existing code so that it would loop throught all the data at one time in the hopes of creating a qucker, and more efficient analysis. This way if you wish to expand the dataset to include more stocks you will minimize your time waiting for results from VBA.
##### Analysis & Results
One of the benefits of refactoring code is that most of the code is already in place, with proper syntax. The downside comes with trying to find where withing the code you'd have to make adustments, and ensure that your refactoring doesn't cause any conflicts with the pre-existing code. One example of this can be seen below, where the refactored code failed to produce any values in the return columns of the target datasets. Aside from thiss we can see that tickers ENPH and RUN had massive increases in trade volume, jumping from roughly 222,000 to 607,000 and 268,000 to 503,000 respectively from, which would round out to return rates of over 82% and 84% each from year 2017 to 2018. Please see below for 2017 results.

<img width="553" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/111616227/196400836-c03939ad-3141-49f1-85f9-98b3553312ee.png">

See below for 2018 results.

<img width="542" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/111616227/196401040-99b61eb3-9cbc-428b-94cf-2d42afce2d4a.png">

##### Summary & Conclusion
In short refactoring code provides an opportunity to rewrite code in a cleaner and more streamlined fashion. This will make it easier for any clients or team members to review or improve upon your code in the future. In some cases however refactoring can be a detriment, particularly when dealing with larger datasets. When it comes to our stocks-analysis workbook, the intention of the refactored code would be increased flexibility so that we can add more data on stocks to the ticker index, as well as running in a shorter amount of time. In short refactoring code can allow for better optimization of pre-existing works.
