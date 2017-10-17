# Reverb-MVC
##### (aka Rock-Metal-MVC)


## [Reverb MVC deployed on Azure](http://reverbaudio.azurewebsites.net/)


*A music site that offers information about songs. Add new songs and then listen to them. (gasp)*

![ReverbSplash](http://picbg.net/u/21482/62342/866227.png)

### 1. Administrative functionality:

* Edit songs

"~/song/editsong?songId=GUID"

* Add songs, albums, genres and artists

"~/create/creationchoice"

"~/create/createsong"

"~/create/createartist"

"~/create/createalbum"

"~/create/creategenre"



### 2. Mundane users:
* Favorite songs

Button on song cards in "/song/library" or "/song/details?songId=GUID"

* View song details and play videos

"~/song/details?songId=GUID"


### 3. Anonomys users:

* Search for songs in the music library

Access only to "~/song/library" where you can searchg for songs by name, albumm, artist and order by each of them.
