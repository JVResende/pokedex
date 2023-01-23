# POKÉDEX

## 📄 About
Website that simulates the Pokédex, where the user can capture Pokémons, see their details and remove them from the Pokédex. The API used in the realization of this project is at https://pokeapi.co/.

## 🔗 Link to Access
https://pokedex-web.surge.sh/

## 💻 Functionalities
- Navigation between pages through properly defined buttons (including the Header logo that leads to the Pokémon list).
- Responsiveness.

- Pokémons List: 
     - List of cards with Pokémon information.
     - Pagination (16 cards rendered per page).
     - Button in the header to navigate to the Pokédex.
     - Card buttons:
        - Add: Adds the Pokémon to the Pokédex.
        - Details: Opens the Pokémon details page.
- Pokédex:
     - List of cards with information on pokémons that were added to the Pokédex.
     - Pagination (16 cards rendered per page).
     - Button in the header to navigate back to the pokemon list.
     - Card buttons:
        - Remove: Removes the Pokémon from the Pokédex.
        - Details: Opens the Pokémon details page.
- Details page:
     - List with the information of the Pokémon.
     - Buttons in the header to go back to the last page and to add to the Pokédex (if you clicked on the card in the Pokémon list) or remove from the Pokédex (if you clicked on the card in the Pokédex).
     
- Extra features:
     - When reloading the page (F5) the Pokémon that were added to the Pokédex are still there and they do not appear in the Pokémon list.
     - Filters by name or number and type.
     - Sorting by name or number.
     - Pagination manage all 151 Pokémons, working together with the filters.
     - Sounds when clicking on the navigation buttons, on the add and remove buttons from the Pokédex.
     - Exclusive sounds for each Pokémon when clicking on the details button.
     - Video 'RapPokémon' when catching all of them + different music when entering the pokédex.
     - A message is rendered when the Pokédex is empty.
     
## ⚙️ Setup

Clone down this repository. You will need node and npm installed globally on your machine.

- Installation:

```
  $ npm install
  $ npm install axios
  $ npm install styled-components
  $ npm install react-router-dom
```

- To start the project:

```
  $ npm start
```

Now just test it in your browser!

## 🛠 Technologies

- React.js
- API
- Axios
- React-Router-Dom
     
## 📷 Images
![1](https://user-images.githubusercontent.com/102267210/189549802-048814da-6a2e-45d3-b068-633c6f73b041.png)
![2](https://user-images.githubusercontent.com/102267210/189549804-83fe679a-7e79-49ca-9aba-ff6eda2a19a1.png)
![3](https://user-images.githubusercontent.com/102267210/189550834-ef8fa33b-175e-47b8-b2ed-edbd1ef61c29.png)
![4](https://user-images.githubusercontent.com/102267210/189549806-ea3add8a-18c9-41de-8049-1ebaa4d50d76.png)
