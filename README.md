# Country_Flags_Analysis
Analyzing "Country_Flags" data-set in Hadoop using HiveQL and HDFS.  

<h1>Problem Statement</h1>
<ol type='A'>
A.	Count number of countries based on landmass.<br></li>
B.	Find out top 5 country with Sum of bars and strips in a flag.<br>
C.	Count of countries with icon.<br>
D.	Count of countries which have same top left and top right color in flag.<br>
E.	Count number of countries based on zone.<br>
F.	Find out largest county in terms of area in NE zone.<br>
G.	Find out least populated country in S.America landmass.<br>
H.	Find out largest speaking language among all countries.<br>
I.	Find most common colour among flags from all countries.<br>
J.	Sum of all circles present in all country flags.<br>
K.	Count of countries which have both icon and text in flag.
</ol>

<h1>Dataset Description</h1>
<ol>
<li>Title: Flag database</li>
<li>Source Information
   	-- Creators: Collected primarily from the "Collins Gem Guide to Flags":
      	Collins Publishers (1986).
   	-- Donor: Richard S. Forsyth 
             		8 Grosvenor Avenue
             		Mapperley Park
             		Nottingham NG3 5DX
             		0602-621676
   	-- Date: 5/15/1990
</li>
<li>Past Usage:
-- None known other than what is shown in Forsyth's PC/BEAGLE User's Guide.</li>
<li>Relevant Information:
   	-- This data file contains details of various nations and their flags.
      	In this file the fields are separated by spaces (not commas).  With
      	this data you can try things like predicting the religion of a country
      	from its size and the colours in its flag.  
   	-- 10 attributes are numeric-valued.  The remainder are either Boolean-
      	or nominal-valued.
</li>
<li>Number of Instances: 194</li>
<li>Number of attributes: 30 (overall)</li>
<li>Attribute Information:
<ol>
1.	name	Name of the country concerned<br>
2.	landmass	1=N.America, 2=S.America, 3=Europe, 4=Africa, 4=Asia, 6=Oceania<br>
3.	zone	Geographic quadrant, based on Greenwich and the Equator 1=NE, 2=SE, 3=SW, 4=NW<br>
4.	area	in thousands of square km<br>
5.	population	in round millions<br>
6.	language 1=English, 2=Spanish, 3=French, 4=German, 5=Slavic, 6=Other Indo-European, 7=Chinese, 8=Arabic,      9=Japanese/Turkish/Finnish/Magyar, 10=Others<br>
7.	religion 0=Catholic, 1=Other Christian, 2=Muslim, 3=Buddhist, 4=Hindu,
5=Ethnic, 6=Marxist, 7=Others<br>
8.	bars     Number of vertical bars in the flag<br>
9.	stripes  Number of horizontal stripes in the flag<br>
10.	colours  Number of different colours in the flag<br>
11.	red      0 if red absent, 1 if red present in the flag<br>
12.	green    same for green<br>
13.	blue     same for blue<br>
14.	gold     same for gold (also yellow)<br>
15.	white    same for white<br>
16.	black    same for black<br>
17.	orange   same for orange (also brown)<br>
18.	mainhue  predominant colour in the flag (tie-breaks decided by taking the topmost hue, if that fails then the most central hue,
and if that fails the leftmost hue)<br>
19.	circles  Number of circles in the flag<br>
20.	crosses  Number of (upright) crosses<br>
21.	saltires Number of diagonal crosses<br>
22.	quarters Number of quartered sections<br>
23.	sunstars Number of sun or star symbols<br>
24.	crescent 1 if a crescent moon symbol present, else 0<br>
25.	triangle 1 if any triangles present, 0 otherwise<br>
26.	icon     1 if an inanimate image present (e.g., a boat), otherwise 0<br>
27.	animate  1 if an animate image (e.g., an eagle, a tree, a human hand) present, 0 otherwise<br>
28.	text     1 if any letters or writing on the flag (e.g., a motto or slogan), 0 otherwise<br>
29.	topleft  colour in the top-left corner (moving right to decide tie-breaks)<br>
30.	botright Colour in the bottom-left corner (moving left to decide tie-breaks)<br>
</li>
</ol>
<li>Missing values: None</li>
</ol>
