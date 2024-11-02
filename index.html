const apiKey = '04a524e4aa66bb6e75b85f49715a1960'; // Replace with your OpenWeatherMap API key

async function getWeather() {
    const city = document.getElementById('city').value;
    const weatherDiv = document.getElementById('weather');

    if (city) {
        const url = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}&units=metric`;

        try {
            const response = await fetch(url);
            if (!response.ok) {
                throw new Error('City not found');
            }
            const data = await response.json();
            displayWeather(data);
        } catch (error) {
            weatherDiv.innerHTML = `<p style="color: red;">${error.message}</p>`;
        }
    } else {
        weatherDiv.innerHTML = '<p>Please enter a city name.</p>';
    }
}

function displayWeather(data) {
    const weatherDiv = document.getElementById('weather');
    const { main, weather, name } = data;

    weatherDiv.innerHTML = `
        <h2>Weather in ${name}</h2>
        <p>Temperature: ${main.temp} °C</p>
        <p>Condition: ${weather[0].description}</p>
        <p>Humidity: ${main.humidity}%</p>
        <p>Wind Speed: ${data.wind.speed} m/s</p>
    `;
}
