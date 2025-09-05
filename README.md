# Web Browser and Search Engine

Designing and implementing a mini search engine capable of handling a collection of web pages hosted on a local server. The project is divided into four main parts, each focusing on a critical component of search engine functionality. The overarching goal is to create a web tool with the following capabilities:

- **Displaying Web Pages:** Given a URL, the tool can display the corresponding web page.

- **Connectivity Information:** The tool can display and answer questions about the connectivity of web pages.

- **Search Functionality:** Users can input queries to find relevant web pages, which will be displayed in order of best to worst match. The tool can automatically display the best matching result.

- **GUI Enhancements:** A graphical user interface allows for interactive use of the tool, including displaying search results and navigating web pages.

- **Analyzing the Content of Web Pages:** Analyze pages based on their content by counting the frequency of words on each page, which correlates to the content’s relevance.

- **Processing User Queries:** Determine the relevance of a web page to a given query using word-frequency counts; initially, relevance is the sum of the frequency counts of query words.

- **Adding a Cache and GUI Front-End:** Improve response times and provide a user-friendly interface by caching query results and offering a GUI for easy interaction.

- **Adding a Hyperlink Graph:** Visualize and explore web connectivity by building a graph of URL links parsed from pages, allowing exploration of reachable URLs and the shortest paths between them.
