# Project 2: Hero Directory

Using an online API which stores near 750 comic book characters (including Star 
Wars, Godzilla and some Japanese manga characters) we created a Superhero/Super 
Villain directory. A user can view characters by scrolling through a table or 
with search bar capability to look up a specific character by name. When the 
search is used, it’ll yield a response with three fields: character name, real 
name, and image. This prevents any confusion between characters with the same 
or similar names. Once characters are selected, the user is redirected to a 
Character Profile page which will contain information such as a biography, 
alliances, and statistics. The user has the option to add the character to a 
“Fantasy Team.” The user is also able to search up other teams (whether premade 
or user made) which yields clickable results containing the team name and the 
user who created them (in the case of premade teams, the creator will be 
Marvel/DC/Dark Horse/etc.). 

One of the major issues we had while developing this project was implementing the 
Git workflow correctly. For starters we used separate branches for the client and 
server on the same repository as opposed to separate repositories or folders. 

Implementing session management was another issue. I had set up session management 
using HttpServlets, but we couldn't get the session management to work with the 
client side requests. We ended up using client side validation on the last days 
before code freeze, which involved some refactoring of the Controllers. 

As a side note, I included some basic programs I quickly threw together in the 
first day to help us process information from the API. These are stored in the
PullFromApi folder, as they were in a separate folder from the main 
project. These were used to populate our database with hero information as we 
had a limit to our number of uses of the API we used and no good way of searching 
the API for specific heroes. Instead we implemented searching and other functionality 
that would require many repeated requests on our own copy of the API information. 

We used the following technologies in our stack: 
* HTML
* CSS
* AJAX
* SQL
* Java
* Spring
* DevOps
* Angular
* Hibernate

Link to Main Repository:
https://github.com/MaxEffect13/project2