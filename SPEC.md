# Tai Wai Weather App SPEC

## 1. Project Overview
A mobile-responsive web application specifically for Tai Wai residents to check local real-time weather and the 9-day forecast.

## 2. Technical Stack
- **Frontend:** Single-page `index.html` with Tailwind CSS (via CDN).
- **JavaScript:** Vanilla JS for fetching and rendering data.
- **API:** HKO Open Data API (JSON).
- **Deployment:** Netlify.

## 3. Core Features
- **Real-time Local Temperature:** Specifically showing "Sha Tin" station data (closest to Tai Wai).
- **9-Day Forecast:** Displaying date, week, icon, and temperature range.
- **Auto-Refresh:** Fetch data on load.
- **Mobile Responsive:** Clean, modern card-based UI.

## 4. API Endpoints
- **Current Weather:** `https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=rhrread&lang=en`
- **9-Day Forecast:** `https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=fnd&lang=en`

## 5. UI Design (Tailwind)
- **Background:** Gradient (Slate/Blue).
- **Main Card:** Centered, white/translucent background, rounded-xl, shadow.
- **Current Weather Section:** Large temperature display, Sha Tin station label.
- **Forecast Grid:** Horizontal scroll or vertical list on mobile, grid on larger screens.

## 6. Development Plan
1. Initialize Git repository.
2. Create `index.html` with structure and styling.
3. Implement `app.js` logic for API fetching and DOM updates.
4. Verify functionality locally.
5. Deploy to Netlify.
