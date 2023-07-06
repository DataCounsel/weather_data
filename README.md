# Fetch Weather Data using OpenWeatherMap API and write the data to excel

### <ins>Project Objective</ins>

The main aim of this project is to gather data using APIs and store it. Gathering data from APIs is a prevalent practice in real-world applications. APIs (Application Programming Interfaces) allow different software systems to communicate and exchange information. This stored data can be used for analysis or warehousing into Databases or Data Lakes. I have  used Python libraries and the free account on OpenWeatherMap API for retrieving data like city name, date, temperature, humidity, wind speed, Pressure. The python editor used was PyCharm. HTTP errors and user input errors were handled. The data was written into an excel file.


![openweather_api_free_account](https://github.com/DataCounsel/weather_data/assets/71335870/44acba13-46b0-41f3-8a6a-6537196a5417)

A free acount provides 60 call/min. it does not offer historic weather data.



The city for fetching the weather is provided by the user. This could also be provided as a list that can be iterated over. Each city data is a separate API call.
The JSON data contains a huge number of data fields and for this project I have fetched only a few important details about the weather.

![code_screenshot](https://github.com/DataCounsel/weather_data/assets/71335870/258687bd-9c61-48e4-b84a-fadb03a341ef)

![image](https://github.com/DataCounsel/weather_data/assets/71335870/5d575361-79de-4ce3-ae9c-dc81a340701b)


The Data is stored in a Pandas Dataframe and this dataframe is stored in Excel using the Openpyxl Library. The libraries used are Pandas, requests, Openpyxl. The datetime module was used to convert the date from 
a UNIX timestamp to a readable date format. The OS module was also used to check if the file already exists. If it does then data will be appened else a new file will be created and data will be written to it.

This project would be the  first step in a real-world Data Analytics process. The data collection is often done using APIs and thus it is crucial step in data gathering and warehousing. This data can be transformed and analyzed as required.



