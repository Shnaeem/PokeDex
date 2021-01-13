# PokeDex
React Components and AJAX
This exercise is to demonstrate working with API Requests inside of React Components using React Hooks, specifically the useEffect hook. 
Use Axios to query the PokéAPI: https://pokeapi.co/ in this exercise.
Let's go ahead and start a React Project:
$ npx create-react-app pokedex
$ cd pokedex
 
Add the Axios package to the application
$ npm install axios
Start the application
$ npm start
Requirement 1: Generate List of Pokemon from an API call
Modify the PokeList component so that it uses axios to make a request to the Pokéapi (https://pokeapi.co/api/v2/pokemon/) and then renders a "list" of Pokemon components where each Pokemon component contains data from the results from the API call.
For each pokemon, display it's name inside of a url.
Requirement 2: Toggle Pokemon Details
Modify the Pokemon component so that when clicked it displays detailed information about that Pokemon. If the Pokemon is clicked again, then the detailed information will be hidden (so the click should serve as a toggle that displays a pokemon's details if the details are currently hidden or hides the pokemon's details if the details are currently displayed).
