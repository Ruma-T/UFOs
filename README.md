# UFOs

#Overview of Project:  

##Purpose 

We have to create a dynamic webpage which will take user inputs and visually adjust accordingly whenever needed. The page will be built by inserting Javascript in HTML. We’ll use CSS and Bootstrap to present the data neatly on the webpage.

Link to the UFO Sighting Webpage :https://ruma-t.github.io/UFOs-Sightings/

##Results:  

The website looks like this picture below when filters were added:

![cap11.1](https://github.com/Ruma-T/UFOs/blob/main/Resources/cap11.1.PNG)




Here is the code for updated filterTable:

![cap11.2](https://github.com/Ruma-T/UFOs/blob/main/Resources/cap11.2.PNG)




Code for UpdateFilters replaced handleClick and created buildTable with updateFilters using d3 selectall function.



![cap11.3](https://github.com/Ruma-T/UFOs/blob/main/Resources/cap11.3.PNG)




In index.html, created four list of elements :city,state,country,shape.


![cap11.4](https://github.com/Ruma-T/UFOs/blob/main/Resources/cap11.4.PNG)







![cap11.5](https://github.com/Ruma-T/UFOs/blob/main/Resources/cap11.5.PNG)




Here is the result when we filtered city as 'benton' and country as 'us'



![cap11.6](https://github.com/Ruma-T/UFOs/blob/main/Resources/cap11.6.PNG)





This result shows the UFO sightings for state as 'ca'


![cap11.7](https://github.com/Ruma-T/UFOs/blob/main/Resources/cap11.7.PNG)













##Summary: 

•	We can search the UFO sighting information according to one or multiple filters based on date, city, country,and shape.

###Limitation 

•	It did not give the data about daytime or nighttime when it is viewed.

•	Information is limited to US only, we can compare other countries sightings too.

  As Javascript is case sensitive,it will not show any result if the we search in uppercase instead of lowercase.
  
  Here is the  search result with Tx and tx:
  

![cap11.8](https://github.com/Ruma-T/UFOs/blob/main/Resources/cap11.8.PNG)




![cap11.9](https://github.com/Ruma-T/UFOs/blob/main/Resources/cap11.9.PNG)

