# Event flow for precedent "Browsing and searching information about products"
## Main flow:
1. Use case begins when user clicks section products from the navigation bar. 
2. User gets web page with table view of products and inputs for searching products. If error occurs error flow E1 executed.
3. User can browsing more products by scrolling or use form for searching, in second case alternative flow A1 executed.
4. Use case ends.
## A1 flow:
1. A1 flow begins.
2. User inputs information for searching into form inputs.
3. User clicks search button.
4. User gets results of searching.
5. A1 flow ends.
## E1 flow:
1. E1 flow begins.
2. User gets error page with description of error.
3. E1 flow ends.

# Event flow for precedent "Downloading documents about conferences and publications"
## Main flow:
1. Use case begins when user clicks download reference in sections conferences or publications. 
2. User waits for document downloading . If error occurs then executed error flow E1.
3. User gets downloaded document in his computer file system in folder downloads.
4. Use case ends.
## E1 flow:
1. E1 flow begins when error occurs.
2. User gets error page with description of error.
3. E1 flow ends.

# Event flow for precedent "Searching for information about publications"
## Main flow:
1. Use case begins when user clicks section publications on the navigation bar. 
2. User gets web page with form for searching. If error occurs error flow E1 executed.
3. User selects department for searching using combo box element.
4. User inputs pattern for searching.
5. User clicks search button.
6. Below the searching form user gets results of searching.
7. Use case ends.
## E1 flow:
1. E1 flow begins.
2. User gets error page with description of error.
3. E1 flow ends.

# Event flow for precedent "Browsing content of web app"
## Main flow:
1. Use case begins when user clicks any section from the navigation bars. 
2. User gets web page according selected section. If error occurs error flow E1 executed.
3. Use case ends.
## E1 flow:
1. E1 flow begins.
2. User gets error page with description of error.
3. E1 flow ends.

#Event flow for precedent "Switching language of the web app content"
##Main flow:
1. Use case begins when user clicks one of two buttons for switching language: button "En" (English), button "Ru" (Russian). 
2. User gets content of web app in selected language. If error occurs then executed error flow E1.
3. Use case ends.
##E1 flow:
1. E1 flow begins when error occurs.
2. User gets error page with description of error.
3. E1 flow ends.