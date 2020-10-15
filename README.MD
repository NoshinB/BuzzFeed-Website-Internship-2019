Noshin Begum - BuzzFeed Software Engineer Intern 2019 test

I chose to complete Option One task of creating a Story Application. The task was to build a user interface that allows the user to explore and consume the stories in a web browser, with options to filter and page through the stories.

I spent in total: 4 hours 35 minutes to complete this task.

To run my application, you will need access to a code processor (I used Brackets- http://brackets.io/ as my text editor, to design and run my code in browser).

The first page I designed was for the users to see an overall idea of what the whole site consists of. This is my homepage; users can see a slideshow promoting articles with links to the relevant pages. Users can also access more information about BuzzFeed in general through the links I put clearly in the footer. From the homepage, you can navigate through the different pages which I have clearly separated into different article categories. 
The next 5 pages have the data from the JSON file (articles.json). I converted the JSON file into a JavaScript file (as a variable, with the different data in as arrays- story.js). 
I used FOR loops and IF statements to go through the different articles and specifically print out the information based on what ‘section’ the article was in. For example, on my ‘World’ HTML page- I used a JavaScript For Loop to iterate through the arrays and used an IF statement to print out the title, description, URL and views if the article ‘section’ was ‘World’. I also used HTML DOM appendChild() Method to print the images. 

On all the pages I added 2 different search bars. The first search bar I created contains certain article key words users can search from this website (all pages) and it will navigate to the relevant page where the user can click on the links and read full articles. The second search engine- is a custom google search engine which allows users to search anything from https://www.buzzfeed.com/ also they can also filter the search results based on 'Relevance' and 'Date' . I made the decision to this to allow users the freedom to filter and search any articles to read from the ones mentioned on the site I created to the numerous articles on BuzzFeed’s site. 

On all pages I also added a ‘Night Mode’ button to allow users to comfortably and safely use my site. It also allows user to save certain devices power when switching to night mode. 

On all pages I included a “Print Page” button for users to have any articles summaries from any page printed easily, clearly and quickly.
I also ensured all my pages are responsive to any device and screen size so all the users can clearly use the site without compromising on the aesthetics or information.

I made the decision to create one main stylesheet (style.css) for all my pages. This is beneficial as splitting the stylesheets into separate files leads to extra HTTP requests which can slow things down- single CSS has a faster loading time.

I have included features specifically for accessibility:
-	Night mode
-	Responsive design
-	All content laid out easily
-	Chose clearer contrast colour schemes
-	Used headers to structure my page
-	Search bars are clearly labelled
-	Did not use any tables

If I had more time- I would try style and reposition images and I would work on creating a more accessible site. To create a better accessible site, I would include:
-	Make site keyboard friendly
-	Adding alt text to all images
-	Allowing users to resize text