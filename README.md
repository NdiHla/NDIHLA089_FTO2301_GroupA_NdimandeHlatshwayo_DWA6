# NDIHLA089_FTO2301_GroupA_NdimandeHlatshwayo_DWA6

It imports data from a file named data.js using destructuring assignment. The imported variables include books, authors, genres, and BOOKS_PER_PAGE.
It initializes variables such as page and matches.
It creates a document fragment named starting to hold the initial book previews.
It iterates over the first BOOKS_PER_PAGE matches and dynamically creates book preview buttons in the DOM. Each button contains an image, title, and author information.
It appends the book preview buttons to the starting element in the document.
It appends genre options to a <select> element with the attribute [data-search-genres] using a loop.
It appends author options to a <select> element with the attribute [data-search-authors] using a loop.
It changes the theme based on the user's choice of dark or light mode.
It updates the UI elements such as the list button, search button, and settings button based on the number of matches.
It adds event listeners to various elements, such as the cancel button in the search and settings overlays, search and settings buttons in the header, and list close button.
It adds an event listener to the settings form's submit event to handle theme changes.
It adds an event listener to the search form's submit event to perform a search and update the UI based on the search results.
It adds an event listener to the list button's click event to load and display more book previews.
It adds an event listener to the list items' click event to display the details of a clicked book in the active list view.