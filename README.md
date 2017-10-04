# Reindeer

## Synopsis

The Reindeer exercise used JavaScript to loop though an array of colors and reindeer and write them to the DOM.

## What to Expect
A page displays with colors and reindeer.

![DEMO](https://github.com/hagansmith/reindeer/blob/master/reindeer.png)

## Requirements

Paste the following code into the `<body>` of the HTML file.

```
<div id="reindeer"></div>
```

Paste the following code into your JavaScript file.

```
var colors = ["Blue", "Red", "Orange", "Purple", "Hazel", "Aquamarine", "Periwinkle", "Azure", "Fuchsia", "Chocolate", "Amber", "Amaranth"];
var reindeer = ["Dasher", "Dancer", "Prancer", "Vixen", "Comet", "Cupid", "Donner", "Blitzen"];


var hohohoElement = document.getElementById("reindeer");
```

Your task is to loop through all the reindeer in the array, and add the name of the reindeer to the single HTML `<div>` element provided. The name of the reindeer should be prepended with the corresponding color from the other array.

> **Example output:**  
>  
> Blue Dasher  
>  
> Red Dancer  
>  
> ...


## How to run (Node must be installed on your machine):

1. Go to: `https://www.npmjs.com/package/http-server` and install "http-server".  
2. Navigate to the project folder in command line interface and type: `http-server -p 8080`  
3. This will show at: `http://localhost:8080` in your internet browser.

```
git clone git@github.com:hagansmith/reindeer.git
cd reindeer
npm install http-server -g
hs -c-1
```
Navigate to: http://localhost:8080
