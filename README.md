# steeleye_assignment
Assignment Submission

## Application Deployed on heroku at
  
home-url:https://steel-eye.herokuapp.com/

##Valid url paths
  
1.  https://steel-eye.herokuapp.com/get_all_trades/   (to get all trades)
   
2. https://steel-eye.herokuapp.com/get_all_trades/?page="page number"&sort_by="column_name"   (note:The page numbers should be in multiples of 10)

(get trades by page each page has 10 trades and sortby to sort using columns both parameters are optional and can be used individully)
  
3.https://steel-eye.herokuapp.com/filter_trades/?parms 

(filter trades using minPrice for trades with minimun price of trade) (accepted values integers) (example: https://steel-eye.herokuapp.com/filter_trades/?minPrice=30)

(filter trade using maxPrice for trades with less then maximun price of trade) (accepted values integers) (example : https://steel-eye.herokuapp.com/filter_trades/?maxPrice=60)

(filter trade using start to get list of trades which are executed after the start date) (accepted values dates) (example : https://steel-eye.herokuapp.com/filter_trades/?start="2020-01-01")

(filter trade using end to get list of trades which are executed before the end data) (accepted values dates) (example : https://steel-eye.herokuapp.com/filter_trades/?end="2020-01-01")

(filter trade using assestClass to get list to trades based on assest class) (accepted values "EQ","DEBT","FX") (example : https://steel-eye.herokuapp.com/filter_trades/?assestClass="EQ")

(filter trade using tradetype to get list of trades based on type) (accepted values "buy","sell") (example : https://steel-eye.herokuapp.com/filter_trades/?tradeType="buy")

all the parmeters are optional and can be used independently or individually but atleast one parameter is required;

4. https://steel-eye.herokuapp.com/search_by/?search="your query"  (to get list of trade based on search string present in their fields)

(https://steel-eye.herokuapp.com/search_by/?search="your query"/?page="page number"&sort_by="column_name" (both page and sort_by are optional and can be used independently or individually)
  
5. https://steel-eye.herokuapp.com/get_trade/id  (get a trade by id)
