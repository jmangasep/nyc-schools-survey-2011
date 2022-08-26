# Evaluating New York City Schools: Data from the 2011 Survey

## Project Overview

This project uses the NYC data portal's publicly-available files from the city's school surveys of 2011. The surveys covered various topics like feelings of safety, academic expectations, and more to better understand vital stakeholders in education: students, parents, and teachers. You can learn more about the survey and acquire the open-source data [here](https://data.cityofnewyork.us/Education/2011-NYC-School-Survey/mnz3-dyi8). 

The NYC Department of Education also provides data in this time frame for related areas of interest. Therefore, I opted to use six of these files to contextualize the responses in the survey data. The files I used in addition to the 2011 survey data are listed below with links to their source and direct quotes from the data portal about the given file.

1. [2006 - 2012 School Demographics and Accountability Snapshot](https://data.cityofnewyork.us/Education/2006-2012-School-Demographics-and-Accountability-S/ihfw-zy9j): **10,075 observations, 38 variables**. "Annual school accounts of NYC public school student populations served by grade, special programs, ethnicity, gender and Title I funded programs." This file shows annual accounts per NYC school *and* school year.

2. [SAT (College Board) 2010 School Level Results](https://data.cityofnewyork.us/Education/SAT-College-Board-2010-School-Level-Results/zt9s-n5aj?category=Education&view_name=SAT-College-Board-2010-School-Level-Results): **460 observations, 6 variables**. "New York City school level College Board SAT results for the graduating seniors of 2010." Though it would be better to have the 2011 SAT results, 2010 is the only available year for SAT data. However, this is very close to our year of interest and, therefore, will still serve as a useful metric of academic performance.

3. [2009-2012 Historical Daily Attendance By School](https://data.cityofnewyork.us/Education/2009-2012-Historical-Daily-Attendance-By-School/wpqj-3buw): **831,800 observations, 7 variables**. "Daily listing (counts) of students registered, present, absent and released by School DBN." This file shows counts per NYC school and *day*.

4. [2010 - 2016 School Safety Report](https://data.cityofnewyork.us/Education/2010-2016-School-Safety-Report/qybk-bjjc): **6,310 observations, 34 variables**. "Since 1998, the New York City Police Department (NYPD) has been tasked with the collection and maintenance of crime data for incidents that occur in New York City public schools. The NYPD has provided this data to the New York City Department of Education (DOE). The DOE has compiled this data by schools and locations for the information of our parents and students, our teachers and staff, and the general public." This data is *building location*-level, NOT school-level.

5. [2010 AP (College Board) School Level Results](https://data.cityofnewyork.us/Education/2010-AP-College-Board-School-Level-Results/itfs-ms3e): **258 observations, 5 variables**. "New York City school level College Board AP results for 2010." Like the 2010 SAT data, this is the only available year for this kind of open data, but I still find it useful for my purposes.

6. [2005-2015 Graduation Rates Public - School](https://data.cityofnewyork.us/Education/2005-2015-Graduation-Rates-Public-School/35ey-ieq4): **17,095 observations, 23 variables**. "Graduates are defined as those students earning either a local or regents diploma and exclude those earning either a special education (IEP) diploma for GED." 
