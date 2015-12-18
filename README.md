# dbproject  Columbia Universtiy 4111 introduction to database
The application is called Epoch TV. 
The app provides the following functions for the users: 
1) Search for TV-Series (Advanced Search, user choose from the drop-down menu and get the the list of TV Series related to the choices)
2) Show search list, wish list, watch list for the user based on the search history, rate and wish list
3) Recommend TV Series to the user based on watch list of his or herself or other users in the same age or sex, search list and wish list.
Entities and relationship
Entities includes 
1. TV series 
2. Character 
3. Actor 
4. Creator 
5. Broadcasting company 
6. Multimedia website 
7. Award 
8. User 
Relationship includes the followings
1. TV series –Character (one specific character can only belong to one TV series and one TV series can have several characters, one to many)
2. TV series –Actor (many to many)
3. TV series – Creator (many to many)
4. TV series – Multimedia Website (One TV series can have several websites and one website refer to different TV series, many to many)
5. TV series – Broadcasting Company (One broadcasting company can have many TV series while one TV series can only belong to one broadcasting company)
6. TV series- Award (A specific award can only be given to one TV series while a TV series can get many different awards)
6. Character –Actor (there is a constraint to this relationship, which is one specific character can only be played by one Actor, one Actor can play several characters)
7. User- TV series (many to many)

The E-R diagram can be seen in the file
