# REST API CLIENT

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : GIRISH KUMAR

*INTERN_ID* : CT06DF2915

*DOMAIN* : Java Programming

*DURATION* : 6 WEEKS

*MENTOR* : Neela Santhosh Kumar

## Description

Weather Data Fetcher   <br/><br/>
1.Java Application Description : This Java application demonstrates a comprehensive approach to consuming REST APIs and handling JSON responses, specifically designed for a computer science student learning web service integration and HTTP communication. The application fetches real-time weather data from the OpenWeatherMap API and presents it in a well-structured, user-friendly format.  <br/><br/>
2. Core Architecture and Design Principles : The application follows object-oriented programming principles with clear separation of concerns. The main WeatherApp class handles HTTP communication and user interaction, while a separate WeatherData class serves as a data transfer object (DTO) that encapsulates weather information. This design promotes code reusability, maintainability, and follows the single responsibility principle that is fundamental in software engineering.  <br/><br/>
3. HTTP Request Implementation : The application utilizes Java's built-in HttpURLConnection class to perform HTTP GET requests to the OpenWeatherMap API. This choice demonstrates understanding of core Java networking capabilities without relying on external libraries. The implementation includes proper connection configuration with timeout settings, request headers, and response code validation. The HTTP request construction dynamically builds URLs with query parameters, showing proficiency in string formatting and API parameter handling. <br/><br/>  
4. JSON Parsing and Data Extraction : JSON response parsing is handled using the org.json library, which provides a straightforward approach to working with JSON data structures. The application demonstrates how to navigate nested JSON objects and arrays, extract specific values, and handle optional fields gracefully. The parsing logic shows understanding of JSON structure and proper error handling when dealing with potentially missing data fields.  <br/><br/>
5. Error Handling and Robustness  : The application implements comprehensive error handling at multiple levels. Network-related exceptions are caught and handled gracefully, providing meaningful error messages to users. HTTP response codes are validated to ensure successful API calls, and connection timeouts prevent the application from hanging indefinitely. This demonstrates best practices in building resilient applications that can handle real-world networking issues.  <br/><br/>
6. User Interface and Experience : The console-based interface provides an intuitive experience with clear prompts and formatted output. The weather data is displayed using a structured format with visual separators, emojis for enhanced readability, and properly formatted numerical values. The application includes a continuous loop allowing users to query multiple cities without restarting the program, demonstrating good user experience design principles.  <br/><br/>

<br/>

### Output Images
  
![restapiimage](https://github.com/girishkr9331/Weather-App-Using-Rest-API-Client/blob/master/RestApiClient.png)

  
<br/><br/><br/>
Instruction:
1. Go to https://www.weatherapi.com/
2. Sign up for free account
3. Get your API key from dashboard
4. Replace YOUR_API_KEY_HERE with actual key or use my key (7cdfedd1065048c094f190302252706) by default its set

Run in Terminal  : 
javac WeatherApp.java
java WeatherApp

Sample output looks like this:

Simple Weather App
Enter city name: Ranchi

Format of the output will look like this : 

Location: Ranchi, Jharkhand, India
Temperature: 24.3°C (75.7°F)
Feels like: 26.7°C
Condition: Mist
Humidity: 94%
Wind: 18.7 km/h WSW
Pressure: 1005.0 mb
Visibility: 3.0 km
UV Index: 0.0
