# goals:
1. get rid of mouse drag-selection operation
2. minimize mouse work
3. other tools

## operations for automaiton:
1. select and copy to clipboard innerHTML of element: name and last name, company name
    - LI, LI recruiter, other websites
2. check if name is in the DB already
3. create and fill out profile in INV

## additional:
* creating new profiles: chain prompt asking to point at data to grab and add: 

## JS solution with browser extension:
Chrome Extension for select and copy
1. using background script https://developer.chrome.com/extensions/background_pages
2. to get inner html of element pointed at
3. and put it to clipboard https://stackoverflow.com/questions/400212/how-do-i-copy-to-the-clipboard-in-javascript

## PY solution with selenium
App for automation of all tasks
