# UFOs - The Truth Is Out There!

## Project Overview
This project uses JavaScript, HTML, and CSS to create a custom webpage that showcases different UFO sightings around the world. The collected UFO data provided is too large for anyone to search through manually for specific events. Therefore, a script was written to allow users to filter the data provided in a dynamic table based on specific data values: Date, City, State, Country, and Shape.

## The Webpage
With the Bootstrap grid system, we have organized the webpage's content to display a navigation bar, a page header, a section for the article title and paragraph, and a section for filters and table of data.


![UFOs_webpage](https://github.com/Lora-Borja/UFOs/blob/main/static/images/UFOs_webpage.PNG)
![UFOs_tablefilters](https://github.com/Lora-Borja/UFOs/blob/main/static/images/UFOs_tablefilters.PNG)


## Multiple Search Results
There are five filters available where users can set multiple inputs and search for UFO sightings based on the data's table columns. 

- Enter a Date
- Enter a City
- Enter a State
- Enter a Country
- Enter a Shape

This allows users to be able manipulate the table output and to sift through the findings based on multiple criteria at the same time. The one drawback of this design is that its assuming the users would already know to type in text format specific information they would like to filter. What if a user does not necessarily know a city name, a state, or a country? Also, the text input is specific to how the data is structured, such as a lowercase input for all the text fields and a specific date format field. There is a placeholder input that can show as an example of how to enter the filters, however, not all users would intuitively comply until they start playing around with entering the filters. Should a user not enter a field correctly or actually inputs a blank (i.e. clears the placeholder input) the table will not display any data to output.

## Recommendations for Further Development
One recommendation I would make is to change the set up of the filters to instead have a drop-down option for users to be able to go through and click to select a date, city, state, country, or a shape of the sightings. Users can choose the information available which would allow for a better interaction with the table, which may further peak more interests in sifting through the large dataset provided.

Another recommendation is to have a "Refresh" or "Reset" button somewhere in the filter search section. Right now, in order to reset the table data, you must either clear the filter inputs or enter new combinations of inputs, which means depending on whether the inputs correspond to the dataset it can possibly show no data at all. I know the navigation bar's purpose is to refresh the page and the table of sightings, but the way it is currently set up at the top of the webpage with a label "UFO Sightings" can simply mean its a title bar and is not intuitive to a user to click on it to refresh the table output. Having the "Refresh" or "Reset" filters in the same section as the search criteria is more clear way to tell the user where to click in order to reset the filters. Also, having a "Refresh" or "Reset" button gives the user the option to start from a new set of parameters to search which can be a cleaner way to set the criteria.
