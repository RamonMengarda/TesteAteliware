# TesteAteliware
Dev hiring challenge for developer position @ Ateliware. Check full requirements here: https://github.com/ateliware/dev-hiring-challenge

This application was built with <b>Angular</b> and <b>.Net</b>, and the database was <b>SQL Server</b>.

The challenge was to build an application to search the main repositories of 5 different languages. Instead of coming up with fixed search terms, a 17 topics list was created, and the user is capable of selecting up to 5 topics at once and then click a button to search. If necessary, the list can be updated to contain as many topics as needed changing only one file, as all views are created dynamically.

<a href="github.com/octokit" target="_blank"><b>Octokit</b></a> is a GitHub API Client Library, wich allows to interact with the GitHub API and search for topics. It was used in this project in order to retrieve information.

The home page initially contains the list of topics in checkbox format. The user is able to select up to 5 of them. When the <b>Search</b> button is pressed, the selected values are sent to the server. There, the results are <b>stored</b> into the database. Then, the results are displayed in a <b>list</b> on the client app, and it's possible to <b>view each repository details</b>. In addition, there is an extra functionality wich is a <b>Favorite</b> button. When it is pressed, the repository database entry is updated in order to identify that repo as a favorite. On the upper region of the screen there's a navbar, and it's possible to click on <b>Favorites</b> to see a list of the marked repositories on the database.

The project was deployed using <b>Azure</b> here: <a href="https://testepraticoateliware.azurewebsites.net/" target="_blank">https://testepraticoateliware.azurewebsites.net/</a>
