# movie_credits
Machine learning program to flag new credits

 RULES:
 1       Movies and recurring TV roles only, no TV guest appearances
 2       Please submit entries in the format outlined at the end of the list
 3       Feel free to submit new actors

 "xxxxx"        = a television series
 "xxxxx" (mini) = a television mini-series
 [xxxxx]        = character name
 <xx>           = number to indicate billing position in credits
 (TV)           = TV movie, or made for cable movie
 (V)            = made for video movie (this category does NOT include TV
                  episodes repackaged for video, guest appearances in
                  variety/comedy specials released on video, or
				  self-help/physical fitness videos)


Please look at this in **Raw**


### Observations
* A television series is placed inside a string `""`
* we do not need *character names* which are placed inside `[]`
* (TV) and (V) seem to be still considered movies
	* Documentaries lie in (TV), [A documentary is a broad term to describe a non-fiction movie](http://www.desktop-documentaries.com/what-is-a-documentary.html)
	* (V) Music feature films lie in (V) 
	
