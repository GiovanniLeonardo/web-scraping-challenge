# web-scraping-challenge
Web Scraping Homework - Mission to Mars

Mission ![Mission-To-Mars](/mission_to_mars/images/mission_to_mars.png)

### NASA Mars News
- Scrape the <a href="https://mars.nasa.gov/news/" target="_blank">NASA Mars News Site</a> and collect the latest News Title and Paragraph Text. Assign the text to variables that you can reference later.

**News Title:** Alabama High School Student Names NASA's Mars Helicopter.
** News Paragraph:** Vaneeza Rupani's essay was chosen as the name for the small spacecraft, which will mark NASA's first attempt at powered flight on another planet.

### JPL Mars Space Images - Featured Image
- Visit the url for JPL Featured Space Image <a href='https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars' open=blank_page>here</a>.
- Use splinter to navigate the site and find the image url for the current Featured Mars Image and assign the url string to a variable called featured_image_url.
- Make sure to find the image url to the full size .jpg image.
- Make sure to save a complete url string for this image.

Featured Image ![Featured_image](https://www.jpl.nasa.gov//spaceimages/images/largesize/PIA17661_hires.jpg)

### Mars Weather
- Visit the Mars Weather twitter <a href='https://twitter.com/marswxreport?lang=en/' open=blank_page>here</a> and scrape the latest Mars weather tweet from the page. 
- Save the tweet text for the weather report as a variable called mars_weather.

### Mars Facts
- Visit the Mars Facts webpage <a href='https://space-facts.com/mars/' open=blank_page>here</a> and use Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc.
- Use Pandas to convert the data to a HTML table string.

[Fact_table](https://space-facts.com/mars/)
[Fact_panda_table](mission_to_mars/images/fact_table_pd.PNG)

### Mars Hemispheres
- Visit the USGS Astrogeology site <a href='https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars/' open=blank_page>here</a> to obtain high resolution images for each of Mar's hemispheres.
- You will need to click each of the links to the hemispheres in order to find the image url to the full resolution image.
- Save both the image url string for the full resolution hemisphere image, and the Hemisphere title containing the hemisphere name. Use a Python dictionary to store the data using the keys img_url and title.
- Append the dictionary with the image url string and the hemisphere title to a list. This list will contain one dictionary for each hemisphere.



