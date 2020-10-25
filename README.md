# goals:
1. get rid of mouse drag-selection operation
2. minimize mouse work
3. other tools

## operations for automaiton:
1. [x] solved thise one with chrome extension. select and copy to clipboard innerHTML of element: name and last name, company name
    - LI, LI recruiter, other websites.
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
* create and fill out profile in INV
1. new-> candidate to create profile: browser
2. get data from candidate page: name, company
3. get email from zoominfo
4. insert data to inv form

## Best case
1. press hotkey1 - check if in INV, if yes - hotkey2, if no - hotkey3. 
2. press hotkey2 - add link to googlesheet (old people)
3. press hotkey3 - add link to googlesheet (new people)
4. press hotkey4 - parse pages on LI and return data (name, company, LIlink, city) 
5. press hotkey5 - get emails from zoom (one by one)
6. import via inv web.

## Progress
- installed windows terminal
- installed node.js with npm
- installed selenium (chromedriver and selenuim IDE)
- inititated node package, needed to add path to have NODE and NPM working, starting a project
