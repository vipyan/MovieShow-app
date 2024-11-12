# MovieShow App 🎬

## Overview

MovieShow is a web application that allows users to explore popular movies and TV shows, view detailed information, and search for their favorites. It leverages The Movie Database (TMDb) API to fetch real-time data, providing an engaging experience for movie enthusiasts.

## Features

- **Browse Popular Movies**: View a list of current popular movies.
- **Browse Popular TV Shows**: Explore trending TV shows.
- **Movie and TV Show Details**: Click on any movie or TV show to see detailed information, including ratings, genres, and production details.
- **Search Functionality**: Search for movies or TV shows by name.
- **Responsive Design**: Optimized for both desktop and mobile devices using Flexbox and Grid layouts.
- **Now Playing Slider**: A dynamic slider showcasing movies currently playing in theaters.

## Demo

[Live Demo](https://gleaming-entremet-d35496.netlify.app)

## Technologies Used

- **HTML5**: Structure and content of the web pages.
- **CSS3**: Styling and layout, including Flexbox and Grid.
- **JavaScript (ES6+)**: Dynamic content rendering, API requests, and state management.
- **[TMDb API](https://www.themoviedb.org/documentation/api)**: Fetching movie and TV show data.
- **[Swiper.js](https://swiperjs.com/)**: Implementing the slider for the "Now Playing" section.
- **[Font Awesome](https://fontawesome.com/)**: Icons used throughout the app.
- **[Google Fonts](https://fonts.google.com/)**: Custom fonts for better typography.

## Installation

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge).
- A code editor (optional, for viewing/modifying the code).

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/movieshow-app.git
   cd movieshow-app
   ```

2. **Obtain an API Key from TMDb**

   - Sign up at [The Movie Database](https://www.themoviedb.org/) to get a free API key.
   - **Note**: Keep your API key secure and do not expose it publicly.

3. **Add Your API Key**

   - Open `js/script.js` in your code editor.
   - Locate the `global` object and replace `'your_api_key_here'` with your actual API key.

   ```javascript
   const global = {
     //...
     api: {
       apiKey: 'your_api_key_here',
       apiUrl: 'https://api.themoviedb.org/3/',
     },
   };
   ```

4. **Open the Application**

   - Open `index.html` in your web browser to start using the app.

## Usage

- **Home Page**: Browse popular movies and see the "Now Playing" slider.
- **Movies and TV Shows**: Navigate using the header links to switch between movies and TV shows.
- **Details Page**: Click on any movie or TV show card to view detailed information.
- **Search**: Use the search bar to find movies or TV shows by name.

## File Structure

```
movieshow-app/
├── css/
│   ├── spinner.css
│   └── style.css
├── images/
│   └── MovieShow.png
├── js/
│   └── script.js
├── lib/
│   ├── fontawesome.css
│   └── swiper.js
├── index.html
├── movie-details.html
├── tv-details.html
├── shows.html
├── search.html
└── README.md
```

## Customization

- **Styling**: Modify the CSS files in the `css/` directory to change the look and feel of the app.
- **Scripts**: The main JavaScript functionality is in `js/script.js`. You can enhance or modify features as needed.
- **Images**: Replace `images/MovieShow.png` with your own placeholder image if desired.

## Dependencies

- **[Swiper.js](https://swiperjs.com/)**: Included via the `lib/swiper.js` file.
- **[Font Awesome](https://fontawesome.com/)**: Included via the `lib/fontawesome.css` file.
- **[Google Fonts - Poppins](https://fonts.google.com/specimen/Poppins)**: Loaded in the HTML `<head>` via CDN.

## Responsiveness

The app is designed to be responsive and works well on various screen sizes. Media queries and responsive units are used to adjust layouts for mobile, tablet, and desktop views.

## Potential Improvements

- **Backend Integration**: Implement a backend to securely handle API requests and protect the API key.
- **Pagination**: Improve the pagination system for better navigation through search results.
- **Error Handling**: Enhance error handling for network requests and invalid API responses.
- **User Authentication**: Allow users to create accounts and save their favorite movies and shows.

## License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this software as per the terms of the license.

## Acknowledgments

- **The Movie Database (TMDb)**: For providing a comprehensive and easy-to-use API.
- **Swiper.js**: For the smooth and responsive slider component.
- **Font Awesome**: For the great icon library.
- **Google Fonts**: For the beautiful typography.
- **Community Tutorials**: Thanks to all the tutorials and resources that helped in building this app.

## Contact

Feel free to reach out if you have any questions or suggestions!


- **LinkedIn**: [Vipin Varughese Kaniyanthara](https://www.linkedin.com/in/vipinvvk/)
- **GitHub**: [vipyan](https://github.com/vipyan)

---

*This README provides an overview of the MovieShow App, its features, installation instructions, and other essential information to help users and contributors get started.*
