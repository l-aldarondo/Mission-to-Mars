# Mission-to-Mars
Web Scraping with HTML/CSS

## Background
### Purpose

To use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

## Resources

Software:
- Python 3.7.6, Visual Studio Code 1.68.1, MongoDB Compass 1.32.6, HTML/CSS, Flask 2.1.2
 
<br/>

## Overview 
This project consists of three technical analyses:

- Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles.

- Deliverable 2: Update the Web App with Mars Hemisphere Images and Titles.

- Deliverable 3: Add Bootstrap 3 Components.

<br/>

## Summary of Results
### Deliverable #1

We confirmed that we had the image URLs and titles for all four hemisphere images, and a code to quit the browser (Figure a).

![images_url](./images/image_url.png)
<sub>Figure (a) Mars hemisphere images URLs.

<br/>

### Deliverable #2

We were able to scrape all the data, confirm that our webpage had the full-resolution images and the titles of the four hemisphere images, as shown below (Figure b).

![4_hemisphere_images_with_titles](./images/Mars_hemisphers_img.png)
<sub>Figure (b) Four Mars hemisphere images with titles.
    
<br/>

### Deliverable #3

- We updated our web app to make it mobile-responsive,
    - It was tested for Ipad air and Pixel 4 mobile devices and confirmed that it was functional (Figure c).

![mobile_responsive](./images/mobile_responsive.png)
<sub>Figure (c) Screen capture of the web app mobile version displayed in an ipad screen.  
         
<br/>

- We added two additional Bootstrap 3 components.
    - Table header was increased in size and added a secundary header to the table (Figure d and e).

    ![bootstrap_component 1](./images/Bootstrap%203%20Component%201.png)
    <sub>Figure (d) Screen capture of code adding bootstarp component to table title.

    <br/>

    ![bootstrap_component 1](./images/Bootstrap%203%20Components_1_display.png)

    <sub>Figure (e) Mars facts table after adding bootstrap components.

<br/>    

- We modified the Mars Hemisphere images to be displayed in a thumbnail format (Figure f and b).
      
    ![bootstrap_component 2](./images/Bootstrap%203%20Component%202.png)
    <sub>Figure (f) Screen capture of code adding bootstarp component to display images as thumbnail.


    ![4_hemisphere_images_with_titles_thumbnail](./images/Bootstrap%203%20Component_2_display.png)
    
    <sub>Figure (g) Four Mars hemisphere images with titles displayed as thumbnail.
        
<br/>


## References

[Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
 
[Bootstap Grid system](https://getbootstrap.com/docs/3.3/examples/grid/)
 
[Bootstrap CSS](https://getbootstrap.com/docs/3.3/css/)