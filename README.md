## Scrape-Site-Face

Scrape a given site for images and extract faces into different files from them. The project can be divided into two parts, first part involves Webscraping while the second part involves using Computer vision algorithms for extracting faces out of given images. Participants can work simultaneously on both aspects of the project.

## Explanation:

* **Webscraping:** Given a link, say www.foo.com, prepare a python script preferably by using webscraping modules like *BeautifulSoup4, requests, scrapy, etc* and gather all the images found located in the website directories. Save all the images in a local directory.

* **Computer Vision:** Let us assume that the image shown below is one of the images found by the webscraper.

    ![sample-image](static/sample.jpg)

    Now, use a face detection algorithm to detect the faces in the individual images, crop the found faces from it and save the cropped section of the faces as separate images. 

    Some of the face images that can be generated from the sample image are:

    ![](static/1.jpg)
    ![](static/2.jpg)
    ![](static/3.jpg)
    ![](static/4.jpg)

## Guidelines

* The cropped image generated should include 30% extra image section along the widthh and 50% extra along the height, so as to give the output images the look of a passport photograph.

* The logs generated during the scraping should be stored in a scrape.log file for debugging

## Bonus Task - Optional:

If the same face is found more than once during the scraping. The images of the individual should be stored under a separate folder.
