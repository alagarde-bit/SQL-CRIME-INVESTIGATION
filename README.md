# SQL-CRIME-INVESTIGATION
SQL Crime Investigation involving a murder at SQL City on Jan.15.2018

In master you will find my code in .txt files.

Given the two parameters about the crime, I started by investigating the crime scene report table using the date, city, and the crime type 'murder'. I used the description field to read details on two witnesses. One was named 'Annabel' on Franklin Rd and the other was not named with the last house on Northwestern Dr. 

I looked in the person table to find annabel on franklin and morty schapiro on Northwestern. I took their ids to search in the interview table. There I found one person who said the murderer was seen at the gym on january 9th 2018 and the other said they saw them run off with a membership id to the gym that started with '48Z', gold status member, and had a license plate that contained 'H42W'

The murderer was Jeremy Bowers after checking the get_fit_now_member table and left joining with person and drivers_license tables

It said the murderer was a hitman though. To find who hired him, he said the woman had red hair, drove a tesla model s, and was 65 to 67 cm tall. She also attended the SQL Symphony Concert three times. I used an interesect to find matching person id from two independent queries. I looked in the facebook_event_checkin table and person for the 'SQL Symphony Concert' and drivers_license and person for the tesla and description. 

Found her name was Miranda Priestly. Mission Accomplished!


