# GeeksterPok-https://iamsurbhi1503.github.io/GeeksterPok/

This readme provides an overview of the Pokemon Pokedex web application, including its features, structure, and usage.

### Features

1. **Pokemon Data Retrieval:**
   - The app uses the PokeAPI (https://pokeapi.co/) to fetch data for the first 151 Pokemon.

2. **Filtering by Pokemon Type:**
   - Users can filter Pokemon cards by type using a dropdown filter.

3. **Search Functionality:**
   - Users can search for specific Pokemon by name, and the Pokedex dynamically updates to display matching results.

### Project Structure

#### HTML

- **index.html:**
  - Contains the main structure of the web page.
  - Includes the Pokedex container, search form, and type filter dropdown.

#### JavaScript

- **script.js:**
  - Defines the behavior and functionality of the web app.
  - Fetches Pokemon data from the PokeAPI.
  - Dynamically generates Pokemon cards based on the retrieved data.
  - Handles search input and updates the Pokedex accordingly.
  - Generates and populates the Pokemon type filter dropdown.
  
#### CSS

- **styles.css:**
  - Defines the styles for various elements in the web app.
  - Includes styles for Pokemon cards, search form, type filter.

### How to Use

1. **Fetching Pokemon Data:**
   - Upon loading the page, the app fetches data for the first 151 Pokemon from the PokeAPI.

2. **Viewing Pokemon Cards:**
   - Pokemon cards are dynamically generated and displayed in the Pokedex container.
   - Each card includes the Pokemon's image, name, ID, type, and a link to more details.

3. **Filtering by Type:**
   - Use the type filter dropdown to select a specific Pokemon type.
   - The Pokedex updates to show only Pokemon of the selected type.

4. **Searching for Pokemon:**
   - Enter a Pokemon name in the search form.
   - The Pokedex updates in real-time to display Pokemon whose names match the entered text.

### Additional Information

- **PokeAPI:**
  - The app relies on the PokeAPI to retrieve Pokemon data. Ensure an active internet connection for proper functionality.

- **Type Filter:**
  - The type filter dropdown is populated based on the unique Pokemon types present in the dataset.

- **Code Comments:**
  - The JavaScript code includes comments to explain the purpose and functionality of key sections.

### Future Enhancements

- **Pagination:**
  - Implement pagination to display Pokemon in smaller, more manageable sets.

- **Additional Pokemon Details:**
  - Expand the displayed information on Pokemon cards to include more details.

- **Loading Indicators:**
  - Add loading indicators during data retrieval to enhance user experience.

### Feedback and Contributions

Feedback and contributions are welcome. If you encounter issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

Enjoy exploring the Pokemon Pokedex web app!
