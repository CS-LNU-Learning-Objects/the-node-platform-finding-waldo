# Finding Waldo
A assignment about EventEmitters

## About
In this assignment you should write a file searching module in node.js using EventEmitter.
The module should be able to search in a couple of text files after the phrase "waldo" (case-insensitive) and trigger/emit event with the phrase and the name of the file where it found.

The files to search is provided in this repo.

You should create your node application in in your GitHub repo calling "xx222xx-event-emitter", where xx222xx is your username. This repo should already be created for you.

##  Requirements
* Create a module that have two public methods, addFile and find.
* "addFile" takes a string with a file path to add files to search.
* "find" search for the phrase "waldo" in all the files and emits the event "found" when ever it founds the phrase in a file.
* Your app.js that is using the file searching module should present well suited textstring when every it founds "waldo" in a file

## Tips
In "find" loop through all files added to the module. Use a regex to find the word and emit and return on first hit.
