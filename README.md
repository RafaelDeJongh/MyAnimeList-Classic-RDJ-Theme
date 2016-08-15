# MyAnimeList
This is a fullwidth flatdesigned List template to be used on the website: MyAnimeList.net

Live Example: http://myanimelist.net/animelist/RafaelDeJongh

###The code used for the Anime List:

<pre>/*Designed by Rafael De Jongh*/
@import url("http://mal-image.appspot.com/anime/ENTERMALUSERNAME/?code=%23more%5BID%5D%7Bbackground-image%3aurl(%5BURL%5D)%7D");
@import url("http://rafaeldejongh.github.io/MyAnimeList/styleMAL.css");
License{/*Profile Liststyle created for MyAnimeList.com by Rafael De Jongh - https://github.com/RafaelDeJongh/MyAnimeList*/}</pre>

###And the code for the Manga List:

<pre>/*Designed by Rafael De Jongh*/
@import url("http://mal-image.appspot.com/manga/ENTERMALUSERNAME/?code=%23more%5BID%5D%7Bbackground-image%3aurl(%5BURL%5D)%7D");
@import url("http://rafaeldejongh.github.io/MyAnimeList/styleMAL.css");
@import url("http://rafaeldejongh.github.io/MyAnimeList/styleOR.css");
License{/*Profile Liststyle created for MyAnimeList.com by Rafael De Jongh - https://github.com/RafaelDeJongh/MyAnimeList*/}</pre>

**Make sure to change the "ENTERMALUSERNAME" of the first import link to make the cover generator work properly!**

###This list is developed with the following List Settings:

**Anime**

- Numbers
- Score
- Type
- Episodes
- Rating
- Start/End Dates
- Priority

**Manga**

- Numbers
- Score
- Chapters
- Volumes
- Start/End Dates

**If you do not want to make use of the Start/End Dates, then you can use the Template overrides mentioned below.** 

###To change the bannger image please add the following code under the license line:

<pre>#list_surround:before{background-image:url(http://URLTOIMAGE.JPG)}</pre>

###Using Template Overrides 

There are currently two temeplate overrides:

- No Datum Anime Overrides
- No Datum Manga Overrides

Both fix/disable the usage of the date attribute for your list.

You can add these overrides to your list style by importing these overrides styles after the main style has been loaded by adding another import url:

<pre>@import url("http://rafaeldejongh.github.io/MyAnimeList/TemplateOverrides/styleNDOR.css");</pre> 
