**Single Page Movie Application(React)**

*This application fetches json data from TMDB API and uses it to populate the related reach pages(trending, popular) with help of two buttons. You can check the movie details via clicking on that specific movie that you want to check. It also contains a search query for movies and a categories sections that you filter the movies by their categories.*

![Screenshot_1](https://user-images.githubusercontent.com/32496821/205926452-ad25c364-2e68-49a8-92d6-af3ecfe6ef9c.png)

**For more details, check the youtube video please:** https://youtu.be/TGzIcTnVMvg

<details>
 <summary>Latest Update Log</summary>

**December 4, 2022 Update**

- *[Added]Specific navigation bar javascript file generated and implemented to the project in order to improve the readability of the code.*
- *[Added]Searching with no input will get an alert to the screen thanks to alertify.*
- *[Fixed]The button called "Popular" which is located at navigation bar no longer refresh the page when clicked.*
- *[Fixed]The search function no longer crash the page when user don't enter an input.(empty input issue)*

**December 5, 2022 Update**

- *[Added]Instead of "Alertify", application is using "react-toastify" to improve the visual quality of the project.*
- *[Added]Implemented a category section that will help you to filter movies by their categories.*
- *[Fixed]Further optimizations in order to acquire a responsive design.(not all of them.)*

**December 6, 2022 Update**

- *[Changes]More natural CSS decision changes.*
- *[Changes]File structure of the project is more professional now.*
- *[Fixed]Responsive design bugs fixed thanks to react-bootstrap*
- *[Added]Hover CSS to genre list*

**December 7, 2022 Update**

- *[Added]React Router added to the project.*

**December 8, 2022 Update**

- *[Changes]File structure arrangements.*
- *[Added]A responsive details page implemented via react router. You can access the page via "modal" and "more details" button.*

**December 11, 2022 Update**

- *[Added]Footer foundation added to the respective pages with a responsive design.*

</details>

**1. Actively used technologies are;**

- *React*
- *Javascript*
- *Bootstrap*
- *React Bootstrap*
- *React Router*
- *CSS*
- *ReactToastify*

**2. Roadmap;**

- [Done]*Expanding the router structure with detailed movie info page.*
- *Adding a lot more information to details page and fixing the navigation bar bugs.*

**3. How to start the project**

- *npm start*

**4. Significant API ENDPOINTS**

*API_POPULAR="https://api.themoviedb.org/3/movie/popular?api_key=<<API_KEY>>"*
*API_TRENDING="https://api.themoviedb.org/3/trending/all/day?api_key=<<API_KEY>>"*
*API_GENRE_LIST="https://api.themoviedb.org/3/genre/movie/list?api_key=<<API_KEY>>"*
*API_GENRE="https://api.themoviedb.org/3/discover/movie?api_key=<<API_KEY>>&with_genres"*
*API_SEARCH="https://api.themoviedb.org/3/search/movie?api_key=<<API_KEY>>&query"*
*API_IMG="https://image.tmdb.org/t/p/w500/"*

**5. How to Obtain a API Key**
- *You have to create a https://www.themoviedb.org/ account. You can see the API category at the profile/settings part. Just follow the guides from there and you will be fine.*
