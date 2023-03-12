Codes for the cloud movie box project.

This is a website hosted on a server. The server stores a set of movies on the cloud data base. Each movie contains a picture, a title, a director and a set of comments.
On the main page the website shows the list of all movies. Users could select the movie they are interested in and they would be directed to the page corresponding to that movie.
On that page, they could choose a language to see the previously added comments in that language. For that, the server sent curl request to IBM's cloud translator service.
Users could also upload voices as comments. Comments would be stored on server. Using a curl request to IBM's cloud, the voice were converted to text and using another curl call to IBM, it was determined if the comment was appropriate to publish and be added to the database.

