# FIPY ~ Downloader
Facebook, Insta, Pinterest and YouTube downloader.



## About

This repository contains the source code for a video downloading website that supports Facebook, Instagram, Pinterest, and YouTube. The code is made publicly available to encourage collaboration and reuse. Whether you're a developer looking to build upon this project or just someone who wants to see how it works, feel free to explore the code and use it for your own purposes. With a focus on simplicity and ease of use, this website is a great starting point for anyone looking to build a similar tool.

## DEMO
`Facebook:`

![Alt Text](demos/Facebook.gif)

`YouTube:`

![Alt Text](demos/YouTube.gif)

`Pinterest:`

![Alt Text](demos/Pinterest.gif)


## Installation

You need you just clone this repo like:

```groovy
git clone https://github.com/JoshimOfficial/FIPY_downloader.git
```


## Usage (Most important)

First of all create a DB named `yt_scraper` then create a table named `webfixer` with id, url, created_date, and created_time column.
set as  

- id = int (primary);
- url = varchar;
- created_date = date;
- time = time.

And now manually insert a data url to your current localhost project location like:

http://localhost/downloader/FIPY_downloader



- Note: Never put the slashes `/` to the end like: 

http://localhost/tailwind/10/test/FIPY_downloader/

This is wrong way.



- You should put the url like:

http://localhost/tailwind/10/test/FIPY_downloader


Now run you project index.php file to your localhost. 


## Feature

- Download from Facebook.
- Download from Pinterest.
- Download from YouTube.


## Limitation

There are some limitation on code. 


`Facebook:`
- Facebook video can be downloaded if url contains `https://fb.com/watch/XXXX`.
- Facebook video uploader name can be shown wrong sometimes.

`YouTube:`
- Youtube video download section may not be shown sometimes.
- Youtube all urls sometime may not work properly.

`Pinterest:`
- Pinterest all urls not working in sometimes.


## About me on this project:

```
Only I designed the font-end and also made the back-end.
Building the logic, breaking the rules, scraping from web, taking help from google, stackoverflow, chatGPT etc
for just updating my this project. 

Thank you 💜

```
