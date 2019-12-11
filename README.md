![header](/pics/header.png)
# Goddard_Shannon_Mission-to-Mars

#### Table of Contents

[Project Overview](#project-overview)  
[Resources](#resources)  
[Objectives](#objectives)  
[Summary](#summary)  
[Challenge Overview](#challenge-overview)  
[Challenge Summary](#challenge-summary)  
[Limitations](#limitations)

## Project Overview


## Resources 


## Objectives


## Summary


## Challenge Overview
In this challenge, we will scrape additional content for the web app. This time, the focus is to add more images to the app.
Background  

## Objectives
- Use BeautifulSoup and Splinter to automate a web browser and scrape high-resolution images.
- Use a MongoDB database to store data from the web scrape. 
- Update the web application and Flask to display the data from the web scrape.
- Use Bootstrap to style the web app.

## Instructions
Visit the [Mars Hemispheres](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars)web site to view the hemisphere images and use DevTools to find the proper elements to scrape.  

To complete this task, follow these steps:

1.) Obtain high-resolution images for each of Mar’s hemispheres.
Note: You must click each hemisphere’s link to access the full-resolution image’s URL.  
2.) Save both the image URL string (for the full-resolution image) and the hemisphere title (with the name).  
3.) Use a Python dictionary to store the data using the keys `img_url` and `title.`   
4.) Append the dictionary with the image URL string and the hemisphere title to a list. This list will contain one dictionary for each hemisphere.  

## Bonus
Bootstrap components are designed to make polishing your webpage easier. Take advantage of the different options Bootstrap provides to create a tidy web app. For an extra challenge, make the following updates to your web app. The goal is to present the gathered data in a format that is easy to read but also pleasing to the eye. Feel free to experiment and familiarize yourself with the different available components.
- Update your web app to use more Bootstrap 3 components. The grid system needs to be used so your website will respond to different devices (such as a phone, tablet, or computer). Many people turn to their mobile devices to browse webpages, so the app needs to be responsive and look good on any device. Hint: Remember to test this using DevTools.
- Include at least three other Bootstrap 3 components from [this list](https://getbootstrap.com/docs/4.0/components/alerts/). Examples include: 
 - Adding a button that redirects users to the homepage of the web app.
 - Adding the hemisphere images as thumbnails
 - Customizing the facts table using a Bootstrap table
As you update your app, keep the following questions in mind.
- Is this page clean?
- Does the page stand out from other pages?
## Submission
Make sure your repo is up to date and contains the following:
- A README.md file containing a screenshot of your completed portfolio
- The coding files created during the module: 
 - Mission_to_Mars.ipynb
 - scraping.py
 - app.py
- The index.html template and its resources (images, stylesheet, etc.)
- A link to the GitHub repo for your portfolio