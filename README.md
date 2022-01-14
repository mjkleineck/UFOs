# UFOs

## Overview
The purpose of this project is to create a dynamic webpage so that a user can input criteria to filter the data in a table and view UFO sightings on a date, in a city, state or country, and by the shape of the UFO. By leveraging a front end language, in this case JavaScript, we are able to accept user inputs and adjust the webpage accordingly.

## Results
When a user comes to Dana's UFO webpage, the user has access to the full data of UFO sightings within the table. Only a limited number of sightings are displayed. The user can interact with the filters to display sightings on a certain date, in a certain location, by a certain shape, or a mixture of filter inputs.

Sighting Data Filtered by Date

![Sightings filtered by Date](https://github.com/mjkleineck/UFOs/blob/main/static/images/Screen%20Shot%202022-01-14%20at%2011.41.57%20AM.png)

Sightings Data Filtered by City

![Sightings filtered by City](https://github.com/mjkleineck/UFOs/blob/main/static/images/Screen%20Shot%202022-01-14%20at%2011.42.25%20AM.png)

Sightings Data Filtered by State, Country, Shape

![Sightings filtered by State, Country, Shape](https://github.com/mjkleineck/UFOs/blob/main/static/images/Screen%20Shot%202022-01-14%20at%2011.43.42%20AM.png)

## Summary
One drawback to the current design is that a user can only filter by a certain date. The ability to filter by a date range would also be benefitial.

In the original design, there was a line in the `handleClick` function that filtered by the `datetime` key explicitly. Instead of using an `if` statement in a `for` loop to iterate through the `data` object, I refactored the code so that if the data's keys and values are updated, we would only need to update the headers of the table accordingly.

Original Design

![Original Design](https://github.com/mjkleineck/UFOs/blob/main/static/images/Screen%20Shot%202022-01-14%20at%2011.52.06%20AM.png)

Refactored

![Refactored](https://github.com/mjkleineck/UFOs/blob/main/static/images/Screen%20Shot%202022-01-14%20at%2012.00.10%20PM.png)

