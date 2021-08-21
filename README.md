<h1 align="center">Welcome to Travel Advisor 👋</h1>
<p>
</p>

> A React application that searches for restaurants, hotels, and attractions based on your location using RapidAPI's Travel Advisor API.

### 🏠 [Homepage](https://antonio-travel-advisor.netlify.app/)

![screenshot](/uploads/travel_advisor_screenshot.png?raw=true)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Create an account at [RapidAPI](https://rapidapi.com/hub)
- Enable key for [Travel Advisor API](https://rapidapi.com/apidojo/api/travel-advisor/)
- Enable key for [Open Weather Map API](https://rapidapi.com/community/api/open-weather-map/)
- Enable key for [Maps JavaScript API ](https://developers.google.com/maps/documentation/javascript/get-api-key)

## Features

- Travel Advisor API fetching of restaurants, hotels, and attractions based on a user's location
- Filter items by ratings
- List scrolls to the selected item from the map
- Address and phone number of selected item
- "Certificate of Excellence" awards for each item on the list
- Search for a new location in the search bar
- New items are displayed when map moves to a different area
- Weather icon is diplayed using Open Weather Map API

## Install

Clone respository: `https://github.com/antonio-lopez/google-maps-travel-advisor.git`

```
cd google-maps-travel-advisor/
npm install
```

Create a `.env` file in the root `google-maps-travel-advisor/` directory, create two variables, add your API keys.

```
REACT_APP_GOOGLE_MAPS_API_KEY=
REACT_APP_RAPID_API_KEY=
```

## Usage

```
cd google-maps-travel-advisor/
npm start
```

## Author

👤 **Antonio Lopez**

- Website: [Antonio Lopez](https://www.antoniolopez.me/)
- Github: [@antonio-lopez](https://github.com/antonio-lopez)
