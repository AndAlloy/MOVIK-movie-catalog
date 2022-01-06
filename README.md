# MOVIK-movie-catalog
The project itself is a movie catalog with recommendation algorithm that uses IMDb API to collect information about different titles. It provides registration for making favourites list and writing reviews

Stack: Java, HTML/CSS.

Frameworks and tools: Maven, Spring, PostgreSQL, Spring Security, Hibernate, Lombok, Freemarker Template Engine, JPA/JDBC.

Features:

· add any title by IMdB identificator

· Mobile and PC adaptation for front-end (adaptive design)

· Main catalog page and separate page for every item with more info about it

· Recommendation system includes algorithm and page for displaying items. It is based on user favorite list and genres in it

· Spring Security for registration/login, password encoding. (checking unique email, etc)

· Email confirmation using Google account, profile verification

· Admin and moderator roles. The first can add/delete titles from catalog. The last can moderate user reviews to every title.

· Every user can add/delete comment for movie. At first it is visible only for moderator, who can approve or delete the comment, in addition he can block account or restrict user from writing reviews at all.

· User has his favourite list, where he can add titles from catalog
