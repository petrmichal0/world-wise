# WorldWise

## Project Title and Description
WorldWise is an interactive web application designed to track your travel adventures. Users can add cities they visited, explore city details, and visualize their travels on a world map.

## Badges
![Static Badge](https://img.shields.io/badge/status-online-brightgreen)

## Quick Look
<img src="https://github.com/user-attachments/assets/76949f7b-4e99-4084-8401-e9ada1702629" width="700" alt="WorldWise App Demo" style="border-left: 1px solid black; border-top: 1px solid black; border-bottom: 1px solid black;">

## Table of Content
- [Project Title and Description](#project-title-and-description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Demo (link)](#demo-link)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Third-Party Libraries](#third-party-libraries)
- [License](#license)

## Features
- Add cities with location data
- View detailed city information including country, date visited, and personal notes
- Track visited countries and cities on an interactive map
- Secure login system for tracking personalized information
- Geolocation feature to identify your current position

## Installation

### Prerequisites
- Node.js (v12 or higher)
- npm (v6 or higher)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/petrmichal0/worldwise.git
    ```

2. Navigate to the project directory:
    ```bash
    cd worldwise
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

## Usage
To start the application, run the following command:
```bash
npm run dev
```

After starting, go to http://localhost:3000 in your web browser.

## Screenshots

<table>
  <tr>
    <th>Homepage</th>
    <th>Pricing</th>
    <th>Product</th>
  </tr>
  <tr>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <a href="https://github.com/user-attachments/assets/c07222fb-a44e-45e0-a3a9-18110b3fda5c" target="_blank" rel="noopener noreferrer">
        <img src="https://github.com/user-attachments/assets/c07222fb-a44e-45e0-a3a9-18110b3fda5c" width="300" height="300" alt="Homepage">
      </a>
    </td>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <a href="https://github.com/user-attachments/assets/d0a71219-b6c7-4482-ab8b-dac9496d11b0" target="_blank" rel="noopener noreferrer">
        <img src="https://github.com/user-attachments/assets/d0a71219-b6c7-4482-ab8b-dac9496d11b0" width="300" height="300" alt="Add Friend">
      </a>
    </td>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <a href="https://github.com/user-attachments/assets/13f54a84-814e-47e4-b7bc-8b3a9d72d0a5" target="_blank" rel="noopener noreferrer">
        <img src="https://github.com/user-attachments/assets/13f54a84-814e-47e4-b7bc-8b3a9d72d0a5" width="300" height="300" alt="Split Bill">
      </a>
    </td>
  </tr>
  <tr>
    <th>Login</th>
    <th>Map</th>
  </tr>
  <tr>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <a href="https://github.com/user-attachments/assets/03cb279e-e0a9-4c0a-9e81-c97a3970101b" target="_blank" rel="noopener noreferrer">
        <img src="https://github.com/user-attachments/assets/03cb279e-e0a9-4c0a-9e81-c97a3970101b" width="300" height="300" alt="Split Bill">
      </a>
    </td>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <a href="https://github.com/user-attachments/assets/9d8cffa4-8f63-4565-89be-5e96dee0b09b" target="_blank" rel="noopener noreferrer">
        <img src="https://github.com/user-attachments/assets/9d8cffa4-8f63-4565-89be-5e96dee0b09b" width="300" height="300" alt="Split Bill">
      </a>
    </td>
  </tr>
</table>

## Demo (link)

Check out the live demo of the application here.

## Project Structure

```bash
WorldWise/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   ├── robots.txt
├── src/
│   ├── components/
│   │   ├── AppNav.jsx
│   │   ├── BackButton.jsx
│   │   ├── Button.jsx
│   │   ├── City.jsx
│   │   ├── CityItem.jsx
│   │   ├── CityList.jsx
│   │   ├── CountryItem.jsx
│   │   ├── CountryList.jsx
│   │   ├── Form.jsx
│   │   ├── Logo.jsx
│   │   ├── Map.jsx
│   │   ├── Message.jsx
│   │   ├── PageNav.jsx
│   │   ├── Sidebar.jsx
│   │   ├── Spinner.jsx
│   │   ├── SpinnerFullPage.jsx
│   │   ├── User.jsx
│   ├── contexts/
│   │   ├── CitiesContext.jsx
│   │   ├── FakeAuthContext.jsx
│   ├── hooks/
│   │   ├── useGeolocation.js
│   │   ├── useUrlPosition.js
│   ├── pages/
│   │   ├── AppLayout.jsx
│   │   ├── Homepage.jsx
│   │   ├── Login.jsx
│   │   ├── Pricing.jsx
│   │   ├── Product.jsx
│   │   ├── ProtectedRoute.jsx
│   │   ├── PageNotFound.jsx
│   ├── App.jsx
│   ├── data/cities.json
│   ├── index.css
│   ├── main.jsx
├── .gitignore
├── README.md
├── package-lock.json
├── package.json
├── vite.config.js
```

## Technologies Used

### Third-Party Libraries
- **React Router**: For navigating between different views in the app.
- **React-Leaflet**: For displaying interactive maps.
- **JSON Server**: For mocking a RESTful backend.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
