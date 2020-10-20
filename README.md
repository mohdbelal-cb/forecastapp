# Time and Weather Forecast App

A Time and Weather Forecast App that displays the following:
- Current time (hh\:mm\:ss)
- Temperature in Celsius for each specified location
- Temperature in Fahrenheit for each specified location
- Weather forecast for each specified location

## Running the App

1. Set up local environment

- node v11.9.0
- npm v6.5.0

2. Install Dependencies
```
npm install
```

3. Build the App
```
npm run build
```

4. Run the App
The app takes comma-separated values of location names or postal codes.
You can run the app on the command line using `node`.

Example: Get the weather in Vancouver, Toronto, and New York
```
node dist/lib/weather.js Vancouver, Toronto, New York
```

To run the application using directly - Without creating the build
Follow the steps below:

1. Convert the `Typescript` file into `js` file using `tsc` module

  ```
    npx tsc src/weather.ts
  ```
  
2. This will create a file in `src` folder with name `weather.js`

3. Now you can directly run the file using the command below:

  ```
  node src/weather.js Vancouver, New York, New Delhi
  ```


Using Open Weather API - https://openweathermap.org/
