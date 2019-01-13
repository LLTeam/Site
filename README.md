# Example of collaboration between Flask and PIL
- The site is able to generate images with text.
  - At the moment, the site can generate 2 image.
    1. card with profile information of the site ```shikimori.org```.
    2. and quotes.
#
**The website creates pictures without any temporary files**
#
# Quote example
[Quote](https://watashis.herokuapp.com/test)

![Quote](https://watashis.herokuapp.com/test)



# Api to get a quote
Send a post request to the link ``http://watashis.herokuapp.com/quotes`` data ```name``` (name quoted) ```text``` (text quote) ```date``` (year-month-day of the quote) ```ava``` (link to the avatar or photo quoted)
