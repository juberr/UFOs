# UFOs - The Truth is Out There!

## Overview of the Project

### Introduction

In the pursuit of the truth surrounding UFOs, we can use JavaScript, HTML, and CSS to create an interactive app that allows users to read and filter through a table containing UFO sightings from the United States and Canada. The more people aware of these sightings the better!

## Results

### Initial Load

Upon the initial loading of the app, users are presented with a brief introduction on the background that inspired this app's creation, and the UFO data table in its entirety below. Asking users to parse through this data themselves would prove inaccessible and hard to draw conclusions from. Thats where the "Filter Search" section of this app comes in.

[INSERT IMAGE HERE]

### Filter Search

If the user inputs a search term into one or more of these fields and presses enter, the table will be rebuilt consisting only of data that matches what the user inputted into the search field. This works the other way too, if the user removes a search term from a field, the table will be rebuilt with the new specifications.

[INSERT IMAGE HERE]

## Summary

This app provides important data for UFO-enthusiasts in a user-friendly format, which will make the hunt for the truth all the easier!

### Drawbacks

One drawback of this app in its current state is the user must input exact search terms to find what they're looking for. For example, if a user wants to search for Canadian sightings and inputs "Canada" nothing would show up because Canadian sightings are listed as "ca" in the dataset.

Another drawback of this app in its current state is the user cannot filter by a UFO sighting's duration or associated comments. This feature could prove useful in finding trends among certain types of sightings!

### Recommendations for Further Development

To increase the functionality for users of this app, we should consider the following developments:

* Incorporate a more sophisticated searching algorithm that allows for more than exact matches. Allowing partial or even misspelled words to still yield results will give users more flexibility in their search terms.


* To keep this dataset more up-to-date and dynamic, this app could implement a database (either SQL or NoSQL) for the table. Moving the data to a database means new UFO sightings can be added to the dataset. Keeping the data up-to-date means the app will stay relevant as UFO research goes on.


