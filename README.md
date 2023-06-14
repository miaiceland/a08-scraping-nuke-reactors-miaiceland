# Activity: Scraping Nuclear Reactors

## Instructions  

- Complete the Scraping Nuclear Reactors Activity found in the DataComputing eBook
    - make sure you carefully follow the instructions and mirror the code in the activity as you work 
    - **every task in the activity should have narrative text describing your observations; most steps also require code chunks and corresponding output.**
    - you should make commits in GitHub as you complete the activity
- submit a completed R Notebook to Canvas before deadline


## Tips & Errors in Book

- Wikipedia is a dynamic resource, has changed slightly since the activity was written
    - The new link for the Wikipedia page to scrape is https://en.wikipedia.org/wiki/List_of_commercial_nuclear_reactors
- **Your Turn**: Reconstruct Info-Graphic of Japan Reactors
    - Tip: it's fine to use `mutate(status_change = !is.na(status))` to plot a generic marker for "status change" rather than points with different shapes for each possible status
    - Tip: you can adjust the figure dimensions in the code chunk options (gear icon)

    - There are too many unique status' for the number of unique shapes that ggplot has available. If you get the following warning when creating this graph, it is okay and you will not loose points: 
        - "Warning: The shape palette can deal with a maximum of 6 discrete values because more than 6 becomes difficult to discriminate; you have 14. Consider specifying shapes manually if you must have them."


## Grading

Assignment is worth a total of 15 points.

- [2 points] Successfully scrape raw data for Japan Reactors from Wikipedia
- [2 points] Your Turn: Tidy Data & Data Cleaning (Japan)
- [2 points] Your Turn: Plot Net Generation Capacity vs Construction Date
- [2 points] Your Turn: Scrape & Clean China Data (then merge with Japan)
- [2 points] Your Turn: Reconstruct Info Graphic of Japan Reactors (or other country of interest)


 
