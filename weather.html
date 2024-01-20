<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Weather Dashboard</title>

    <script src="https://cdn.zingchart.com/zingchart.min.js"></script>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <style>
        #dashboard {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
            font-size: 24px;
            font-weight: bold;
        }
        
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background-color: #f0f0f0;
        }
        
        #myCharts {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 100vh;
            flex-wrap: wrap;
            padding: 20px;
        }
        
        .chart-container {
            width: 30%;
            margin: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            position: relative;
        }
        
        .chart-label {
            position: center;
            text-align: center;
            padding-top: 20px;
            bottom: 10px;
            left: 50%;
            /* transform: translateX(-50%); */
            font-size: 16px;
            font-weight: bold;
            color: #333;
        }
    </style>
</head>

<body>
    <div id="dashboard">Revolutionising Copra Technology - Weather Dashboard</div>

    <div id="myCharts">

        <div class="chart-container" id="myChart-temperature">
            <div class="chart-label">Temperature</div>
        </div>
        <div class="chart-container" id="myChart-humidity">
            <div class="chart-label">Humidity</div>
        </div>
        <div class="chart-container" id="myChart-rain">
            <div class="chart-label">Rain Forecast (1h)</div>
        </div>
    </div>

    <script>
        ZC.LICENSE = ["569d52cefae586f634c54f86dc99e6a9", "b55b025e438fa8a98e32482b5f768ff5"];

        $(document).ready(function() {
            fetchWeatherData();
        });

        function fetchWeatherData() {
            // Replace with your API key and city
            fetch('https://api.openweathermap.org/data/2.5/weather?q=Mangalore&appid=2b5cc959496a1f87309c20ebd407268f')
                .then(response => response.json())
                .then(weatherData => {
                    const temperature = weatherData.main.temp - 273.15;
                    const humidity = weatherData.main.humidity;
                    const rain = weatherData.rain ? weatherData.rain['1h'] : 0;

                    renderCharts(temperature, humidity, rain);
                })
                .catch(error => console.error('Error fetching weather data:', error));
        }

        function renderCharts(temperature, humidity, rain) {
            const gaugeConfig = {
                type: "gauge",
                series: [{
                    values: [28]
                }],
                'scale-r': {
                    ring: { //Gauge Ring
                        size: 10,
                        'background-color': "purple"
                    },
                    aperture: 200, //Specify your scale range.
                    values: "0:100:20" //Provide min/max/step scale values.
                }
            };

            const gaugeMConfig = {
                type: "gauge",
                series: [{
                    values: [88]
                }],
                'scale-r': {
                    ring: { //Gauge Ring
                        size: 10,
                        'background-color': "blue"
                    },
                    aperture: 200, //Specify your scale range.
                    values: "0:100:20" //Provide min/max/step scale values.
                }
            };

            zingchart.render({
                id: 'myChart-temperature',
                data: gaugeConfig,
                title: {
                    text: "Temperature"
                }
            });

            zingchart.render({
                id: 'myChart-humidity',
                data: gaugeMConfig,
                title: {
                    text: "Humidity"
                }
            });

            const rainConfig = {
                type: "bar",
                series: [{
                    // values: [40],
                    aperture: 200,
                    values: "0:100:20"
                }]
            };

            zingchart.render({
                id: 'myChart-rain',
                data: rainConfig,
                title: {
                    text: "Rain Forecast (1h)"
                }
            });
        }
    </script>
</body>

</html>
