SELECT DISTINCT(CITY)
<br>
FROM STATION
<br>
WHERE
<br>
CITY LIKE '%a'
<br>
OR CITY LIKE '%e'
<br>
OR CITY LIKE '%i'
<br>
OR CITY LIKE '%o'
<br>
OR CITY LIKE '%u';<br>
<br>
<br>
Alternative:
<br>
SELECT DISTINCT(CITY)
<br>
FROM STATION
<br>
WHERE RIGHT(CITY, 1) IN ('A', 'E', 'I', 'O', 'U');



