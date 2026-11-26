# character-pages

## API
   -https://rickandmortyapi.com/api/character?page= 
## How paging works
    - adds 1 to page
    - tells the user which page they are on 
    -         let totalPages = Math.ceil(data.info.count / 20);
        console.log(totalPages);
        pageLabel.textContent = `Page ${page} of ${totalPages}`;
        nextButton.disabled = page === 42;
        prevButton.disabled = page === 1; 
    - totalPages tells what page the user is on, and nextButton.disabled and prevButton.disabled are disabled at the maximum number of pages 42 and the minimum number of pages, 1. Stopping the user from going to page 0 and below, and page 43 and above.
## Live site
https://LoganLM051.github.io/character-pages/