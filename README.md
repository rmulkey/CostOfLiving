# CostOfLiving
iOS App that retrieves information about the cost of living of a given city, utilizing Numbeo's public API:

http://www.numbeo.com/api/doc.jsp

example call: 

/api/city_prices?api_key=your_api_key&query=Recife

response JSON:
{
   "monthLastUpdate":4,
   "contributors":91,
   "name":"Recife, Brazil",
   "prices":[
      {
         "average_price":5.443478260869566,
         "item_name":"Meal, Inexpensive Restaurant, Restaurants",
         "highest_price":7,
         "item_id":1,
         "lowest_price":4
      },
      {
         "average_price":1.8523809523809522,
         "item_name":"Imported Beer (0.33 liter bottle), Restaurants",
         "highest_price":2.3,
         "item_id":5,
         "lowest_price":1.5
      },
      {
         "average_price":0.3611111111111111,
         "item_name":"Lettuce (1 head), Markets",
         "highest_price":0.5,
         "item_id":113,
         "lowest_price":0.25
      },
      {
         "average_price":1.3,
         "item_name":"Cappuccino (regular), Restaurants",
         "highest_price":1.5,
         "item_id":114,
         "lowest_price":1.2
      }
   ],
   "yearLastUpdate":2012,
   "currency":"BRA"
}


