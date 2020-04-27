# algolia
Algolia SE Take Home Assignment

For the project, I decided to use the Algolia provided datasets for Basketball Teams and Basketball Players. My project incorporates some frameworks and technologies that I'm most familiar with: jQuery, Bootstrap, Javascript, HTML and CSS. The project is built on Bootstrap, using jQuery to get the data from Algolia using the Algolia SDK. I built out a single page application to avoid needing to download multiple files (.html, .js, .css), and in this way a user can download one file and view it through their web browser.

The intent of the project was to give users a search input field that dynamically queries Algolia and the results are refined by each letter typed into the search field. When the user picks a team, a grid will be populated with the top scorers from that team. The jQuery function makes two calls to Algolia. The first is to get the teams, and the second is to get the top scoring players. The players are sorted by points in descending order. The teams are sorted alphabetically in ascending order (A > Z), and teams are searched first by team name and second by location/city. One challenge that I faced was with the Bootstrap Table which is used for the grid. It easily populates the data for the first team selected, but I would need further time to understand the API to get it to refresh the data when a second, new team is picked.

Overall, I enjoyed the project. It was interesting to learn for the Algolia SDK works and how easy it is for customers to implement the solution. I defaulted to upload JSON files direclty into platform instead of using the API. I enjoyed the project, and it was fun to test everything out.

Thanks!
