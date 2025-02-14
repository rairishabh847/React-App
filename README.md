# React-App

# Hospital Finder 🚑

Hospital Finder is a React-based web application that helps users find nearby hospitals using Google Maps API and Firebase for authentication and data storage. The app leverages modern technologies to provide real-time location services and accurate hospital information.

## Features ✨
- 🗺️ **Google Maps Integration**: Display hospitals on an interactive map.
- 🔍 **Hospital Search**: Search and filter hospitals by name or location.
- 🔒 **User Authentication**: Secure login and registration using Firebase.
- 📊 **Real-time Data**: Fetch and display hospital data in real-time.
- 🌐 **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used 🛠️
- **React**: Frontend library for building UI components.
- **Firebase**: Backend services for authentication and real-time database.
- **Google Maps API**: Display maps and locations of hospitals.
- **Axios**: Handle API requests.
- **React Scripts**: Configuration and build tools.

## Installation & Setup ⚙️

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/hospital-finder.git
   cd hospital-finder
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:  
   Create a `.env` file in the root of your project with the following variables:
   ```
   REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   REACT_APP_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
   ```

4. **Run the app**:
   ```bash
   npm start
   ```
   The app will be available at `http://localhost:3000`.

