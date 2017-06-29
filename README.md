![Description](http://files.gamebanana.com/bitpit/description_e1c38.png)

This is a minimalistic flat designed List Style which focuses around showing the Anime's cover in a nice grid like structure, to be used on the website: MyAnimeList.net

Live Example: [animelist/RafaelDeJongh](https://myanimelist.net/animelist/RafaelDeJongh)

![Preview](http://files.gamebanana.com/bitpit/preview_67ec1.png)

![AnimeListPreview](http://www.rafaeldejongh.com/wp-content/uploads/2016/08/MyAnimeList.jpg)

![Features](http://files.gamebanana.com/bitpit/features_38a9e.png)

This list style offer various features:

- Fully responsive layout, works on desktop and mobile seamlessly 
- Flat, metro like design for an easy overview
- Custom Header Image
- Full cover generation with MAL-IMAGE
- Overrides for specific list settings

![Installation](http://files.gamebanana.com/bitpit/installation_b6439.png)

As this is a list style was made before the list style update, you have to make sure your Template settings is set to "Classic".

![Classic](http://files.gamebanana.com/bitpit/classic.png)

After the template settings has been set, you can now add the following code to your Advanced CSS List Design. 

### The code used for the Anime List:

<pre>/*Designed by Rafael De Jongh*/
@import url("//mal-image.appspot.com/anime/ENTERMALUSERNAME/?code=%23more%5BID%5D%7Bbackground-image%3aurl(%5BURL%5D)%7D");
@import url("//rafaeldejongh.github.io/MyAnimeList/styleMAL.css");
License{/*Profile Liststyle created for MyAnimeList.com by Rafael De Jongh - https://github.com/RafaelDeJongh/MyAnimeList*/}</pre>

### And the code for the Manga List:

<pre>/*Designed by Rafael De Jongh*/
@import url("//mal-image.appspot.com/manga/ENTERMALUSERNAME/?code=%23more%5BID%5D%7Bbackground-image%3aurl(%5BURL%5D)%7D");
@import url("//rafaeldejongh.github.io/MyAnimeList/styleMAL.css");
@import url("//rafaeldejongh.github.io/MyAnimeList/styleOR.css");
License{/*Profile Liststyle created for MyAnimeList.com by Rafael De Jongh - https://github.com/RafaelDeJongh/MyAnimeList*/}</pre>

**Make sure to change the "ENTERMALUSERNAME" of the first import link to make the cover generator work properly!**

### This list is developed with the following List Settings:

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

### To change the banner image please add the following code under the license line:

<pre>#list_surround:before{background-image:url(//URLTOIMAGE.JPG)}</pre>

### Using Template Overrides 

There are currently two template overrides:

- No Datum Anime Overrides
- No Datum Manga Overrides

Both fix/disable the usage of the date attribute for your list.

You can add these overrides to your list style by importing these overrides styles after the main style has been loaded by adding another import url:

<pre>@import url("//rafaeldejongh.github.io/MyAnimeList/TemplateOverrides/styleNDOR.css");</pre> 
