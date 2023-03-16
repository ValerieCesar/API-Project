Netifly Deployment
https://master--luxury-fenglisu-974934.netlify.app/

README: Valerie's Anime List

Introduction:
This project is a React application that allows users to search for and save anime to a list. The application uses the Jikan API to fetch anime data and displays the information in a responsive layout. Users can add and remove anime from their list and view details about each anime.

## Technology Stack
 
React.js

## Usage
-	Enter the name of the anime you want to search for in the search bar.

-	The search results will appear below the search bar.

-	To add an anime to your list, click on the "Add to List" button.

-	To remove an anime from your list, click on the "Remove from List" button.

## Code Structure
The code is structured into different components that handle different functionalities of the application. The main component of the application is the App component, which handles the state of the application and renders the other components.

The main component is App.js, which renders the header, search box, and two AnimeList components for the anime search results and the user's saved list. The AnimeList component renders a list of anime using data passed in from the App component. The AddToList and RemoveFromList components render buttons that add and remove anime from the user's list, respectively. The application uses React Hooks to manage state.

## Components
AnimeList: This component is responsible for rendering the list of anime.

AnimeInfo: This component displays information about a selected anime.

AddToList: This component adds an anime to the user's list.

RemoveFromList: This component removes an anime from the user's list.

## Styling
The styling of the application is done using CSS. The CSS code is located in the style.css file, which is imported into the App component.

## API Used
This project uses the Jikan API to search for anime. The API URL used is:

## Bash
Copy code
https://api.jikan.moe/v4/anime?q=${search}&limit=20

License
This project is licensed under the MIT License. See the LICENSE file for details.
