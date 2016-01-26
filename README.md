# pixels-theme
Pelican theme for pixels.ryanhaigh.net

Note that while pelican will generate pages for each article etc, this theme is for a single page website. Additional content is not linked to from the index template.


Note that while pelican will generate pages for each article, this theme provides a 

##pelicanconf.py variables##
The theme uses the follwing variables from pelicanconf.py:

 - SITENAME - standard pelican sitename
 - SITESUBTITLE - a subtitle for the site
 - AUTHOR - author name
 - TWITTER - twitter url
 - INSTAGRAM - instagram url
 - FACEBOOK - facebook url
 - HOME - homepage url
  
 
##article metadata variables##
The theme uses the following variables from the article metadata:

 - article.fullimage - the path to the full resolution image
 - article.thumb - the path to the thumbnail
 - article.focus - the section of the image which should stay visible on small screens - eg top left
 - article.title - title for article
 - article.contnt - the body of the article - expect only one or maybe two lines - put any links in here

