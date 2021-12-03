# UFO Sightings

![image](https://user-images.githubusercontent.com/67409852/144519241-f411f9a0-7a6e-4045-afc0-c07d68856ad0.png)
## Overview of Project

Our client's webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, added will be a table filter for the city, state, country, and shape.

## Results

To find the date you want to filter by, input the date in the format "1/10/2010". The data that matches your search criteria will display. For example, here the date filter is set to January 14th, 2010.

![image](https://user-images.githubusercontent.com/67409852/144556850-d214c6b6-12aa-4415-b71a-8eb523d341c4.png)

To find the city you want to filter by, input the city name. The data that matches your search criteria will display. Here, the city filter is set to "Cleveland".

![image](https://user-images.githubusercontent.com/67409852/144558689-9d9e9924-6aec-4199-9917-f310346bac76.png)

To find the state you want to filter by, input the two letter state abbreviation. The data that matches your search criteria will display. "OH" is the abbreviation for Ohio.

![image](https://user-images.githubusercontent.com/67409852/144558540-86b1d8b5-b93e-4878-bf45-54310ca51636.png)

To find the country you want to filter by, input the two letter country abbreviation. The data that matches your search criteria will display. "US" is the abbreviation for United States.

![image](https://user-images.githubusercontent.com/67409852/144558872-cb65e5fa-8a02-4cd9-a62c-20146dd12fe6.png)

To find the shape you want to filter by, input the name of the shape. The data that matches your search criteria will display. Here, the user chose the shape "Triangle."

![image](https://user-images.githubusercontent.com/67409852/144559056-a9d76abf-5d48-4c4d-b2a7-723597f1c181.png)

Using all the filters, this is the result from the data:

![image](https://user-images.githubusercontent.com/67409852/144559292-cc8fccbe-67bb-4517-82b8-75001d0e3516.png)

## Summary

### Drawbacks:

A drawback of the original code was that unless the user input their filters in all lowercase, nothing would appear. Adding toLowerCase() to our code remedied this.

```
let eleValue = changedElement.property("value").toLowerCase();
```

Another drawback is that there is no "enter" or "filter" button. The user has to press the Enter button on their keyboard. They may not automatically know to do this, which makes the search function less user-friendly. 

### Additional Recommendations:

Adding an "enter" or "filter" button would make the search function would increase functionality. Also, adding more search elements, as well as the ability to search by keywords within the comments would be a great addition to the webpage.
