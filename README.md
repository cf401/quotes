# Lab 08
Use the file recentquotes.json to show random popular book quotes. 
Your program should use GSON to parse the .json file. 
The app needs no functionality other than showing the quote and the 
author when it is run. The app should choose one quote each time it is run.
Grab a quote from an API.
Ensure that if your app has errors in connecting to the Internet, 
you instead display a random quote from your file.
When we grab a random quote from the Internet, we could add it to our file 
of quotes, for use if the app goes offline in the future. 
Add that functionality: when a quote comes back from a request, 
it’s also cached in the json file.

## how to use
```
1. clone repo to local machine
2. cd into directory
3. TO TEST: run ./gradlew test
4. TO RUN: run ./gradlew run

It will show you a random text and author after run.

If the internet is connected, it will poll a ron swanson quote.
If the internet is not connected, it will pull from a local file.
```

## Collaborators
Jack Kinne
Trevor Dobson


## credits and contributions
- Nick Paro
- Joachen Busch
- Renee Messick 
https://stackoverflow.com/questions/27014417/how-to-use-gson-to-convert-json-to-arraylist-if-the-list-contain-different-class/27015959
https://www.mkyong.com/java/java-generate-random-integers-in-a-range/
https://stackoverflow.com/questions/1402005/how-to-check-if-internet-connection-is-present-in-java
