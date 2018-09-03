Python for web development
 
The probject is a blog where users register and sign in order to view an send posts.

Registered users can follow and unfollow others user.

There is a messaging system to inform users that their favorite user, whom they follow, has posted a new post.
Users can send privite message to other users registered in the system. 

The application has four pages: index/home, explore, profile and log-in/log-out.
	The index page has user's posts and the posts of user he/she follows. 
	The profile page have information about the user, and his or her posts only.
	The explore page has all posts from all users in the system arranged according to the time the post was send. 
	Log-in/Log-out for logging in and logging out respectively,
		Within there is a registration page for new members not registered yet,
		and Reset password for users who have forgotten their password.
			Email implemetation with google-mail for recognifiguring forgotten passwords. 

It has a search engine implemented in Elasticsearch to search for natural language with the posts.

Pagination is developed and the number of posts diplayed per page is set at 25.

There is a time feaature implemented that shows when a post was made, and the last time a user visited on the application.

The project uses Flask web framework and SQLITE, but its delpoyment uses MySQL. 

It implements all the securuty features that are needed for any web application using Flask extensions. 

