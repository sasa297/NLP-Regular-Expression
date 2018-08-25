**Problem statement:** Write a python script using regular expression for extracting the date and time pattern from a text.

Date pattern should consider valid name of months, number of days (1 to 31), number of months (1 to 12) and different styles of writing date patterns.   

**Correct date patterns:**<br>
15 November 1989<br>
16/11/2016<br>
16.11.2016<br>
16-11-2016<br>
9.9.1994<br>
6.02.2006<br>
    
**Incorrect date patterns:**<br>
02-29-2011  ---- (months should be between 1 to 12) <br>
32-12-2011  ---- (day should be between 1 to 31)<br>
01@11@2011  ---- (we don't use special symbols like @,#,$,%,^,&,*,*! for writing date pattern)<br>
Cricket 2013 ---- (cricket is not a month name here)<br>
		
Time pattern should consider valid hours, minutes and different styles of writing patterns. 

**Correct time patterns:**<br>
04:30 <br>
8:30 <br>
00:59 <br>
12:00 <br>
06:06 <br>
   
**Incorrect time patterns:**<br>
30:12....... (hours should be between 0 to 24) <br>
1:70 ........(minutes should be between 0 to 60)<br>
