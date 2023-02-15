# highcharts-thingspeak-demo
ThingSpeak Highcharts Stock Chart demo

NB All licensing from Highcharts and Thingspeak applies.

This demo shows the ability to download public and private ThingSpeak channel JSON data into multiple Highcharts Stock charts. It uses all 8 ThingSpeak channel fields, and as this data is from a weather station, the channels are assigned in logical groups according to the station data.

NB ThingSpeak limits JSON data to a maximum of 8000 points and this is not affected by averaging value set.

Private channel data can be read by choosing between the Highcharts.getJSON request (comment either one) in the chart.js file, and inserting your ThingSpeak channel Read API key in the apiKey variable.


Access ThingSpeak API documentation here https://www.mathworks.com/help/thingspeak/readdata.html

You can access my ThingSpeak channel here https://thingspeak.com/channels/1657561/

Highcharts Stock documentation can be accessed here https://www.highcharts.com/products/stock/
