# UFO

## Overview of the Analysis
We were tasked with helping Dana, a data journalist, to create a website to that will present a JavaScript file that is filled to the brim with sighting information as a table. Dana also wanted to have the website be dynamic and enable users to sift through it using a set of filters provided on the webpage. We initally created a single filter for the date of the sightings, but Dana wanted to provide a more in-depth analysis of UFO sightings. This meant adding additional table filters for the city, state, country, and shape of the UFO.

## Results
Our webpage is configured with the filter search fields on the left of the webpage, as pictured below.

![Screenshot 1](https://user-images.githubusercontent.com/114427019/213265952-f4df695b-4961-4f6c-8049-53bd1b7b104c.png)

The possible search fields are Date, City, State, Country, and Shape. One thing to note about these fields is the criteria entered should be in lowercase format.

To begin a a search, the user should choose a field to start off with. For this explanation, we'll start off with the State field. We entered "ca" into the field as seen below.

![Screenshot 4-ca](https://user-images.githubusercontent.com/114427019/213272701-c709e9ff-1010-4604-9930-ab9d2f9557fc.png)

As displayed in the image, just entering the value "ca" will not filter the data. The user will need to click away or press Enter to have the table return the filtered data. Once this happens, the table should look like the image below.

![Screenshot 5-ca results](https://user-images.githubusercontent.com/114427019/213274182-5402a1ea-d29e-4ad8-8099-82c5846518d3.png)

As indicated by the red box, the table now is displaying only entries with "ca" as the state. The end user can also add additional search critiera to the table. In the next image, we've updated the Shape field to include the word "light".

![Screenshot 6](https://user-images.githubusercontent.com/114427019/213278956-edad5b06-ab13-4737-8cda-ed5567da9796.png)

Once the filter is applied, we can see that the table now displays entries that have "ca" as the State and "light" as the Shape.

![Screenshot 7](https://user-images.githubusercontent.com/114427019/213279246-bb525ce3-5167-4be7-844f-efbbf1aa4af7.png)

The end user can add as many filters to the table as they would like, and the table will do it's best to return the entries that match the fields entered.

## Summary
While this project was successful, there is always room for improvement.

### Drawbacks
One drawback of this page is that end users aren't able to filter for a date range. As the page is now, end users are only able to filter for one date at a time. This means if a user wanted to look at a date range, they would have to input each date into "Enter Date" field of the filter search one at a time.

### Recommendations
The first recommendation would be to add a blurb or some other statement if nothing is found within the data based on the search criteria. This way, the user would be able to input a different value for the search fields rather than thinking the webpage is broken. The image below shows us entering the date "2/10/2010" into the Date field.

![Screenshot 2-Blank](https://user-images.githubusercontent.com/114427019/213279693-8cbf3272-a0e6-49d9-a64f-df3612d8d760.png)

Once the filter is applied, we can see in the next image that nothing was returned. The reason isn't clear, and if we had a larger data set, we may not be able to easily find the last date in the table. Adding a blurb or statement about why nothing was returned would help to cut down on confusion.

![Screenshot 3-Blank](https://user-images.githubusercontent.com/114427019/213280245-5328b572-411a-4f45-8143-3eb72f7a7f25.png)

An additional recommendation would be to add a results counter to the blank area to the side of the Filter Search title as pictured below. This addition would help users to perform their own analysis on the data if they know how many entries they are working with.

![Screenshot 8](https://user-images.githubusercontent.com/114427019/213268594-0d1f1466-3c3d-4cc6-ab0a-4e156a21b61a.png)

