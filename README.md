# MOVIK-movie-catalog
The project itself is a movie catalog with recommendation algorithm that uses IMDb API to collect information about different titles. It provides registration for making favourites list and writing reviews

<b>Stack:</b> Java, HTML/CSS.

<b>Frameworks and tools:</b> Maven, Spring, PostgreSQL, Spring Security, Hibernate, Lombok, Freemarker Template Engine, JPA/JDBC.

<b>Features:</b>

· add any title by IMdB identificator

· Mobile and PC adaptation for front-end (adaptive design)

· Main catalog page and separate page for every item with more info about it

· Recommendation system includes algorithm and page for displaying items. It is based on user favorite list and genres in it

· Spring Security for registration/login, password encoding. (checking unique email, etc)

· Email confirmation using Google account, profile verification

· Admin and moderator roles. The first can add/delete titles from catalog. The last can moderate user reviews to every title.

· Every user can add/delete comment for movie. At first it is visible only for moderator, who can approve or delete the comment, in addition he can block account or restrict user from writing reviews at all.

· User has his favourite list, where he can add titles from catalog

<b>Screenshots:</b>
<p><b>PC view:</b></p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/50303118/148396098-df08a6f1-675c-4410-825a-16cfd846872f.png" width="600px" alt="Main page">
  <img src="https://user-images.githubusercontent.com/50303118/148396485-c03c5ac4-765a-43d4-9385-a194fb549348.png" width="600px" alt="Item page">
  <img src="https://user-images.githubusercontent.com/50303118/148397126-01ea4c3b-c83d-41dc-8111-925d1109acf2.png" width="600px" alt="Item page">
</p>
<p><b>Mobile view:</b></p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/50303118/148397311-fe22fe4d-8790-4366-9a86-d7f1e3b78858.jpg" width="200px" alt="Item page">
  <img src="https://user-images.githubusercontent.com/50303118/148397318-764c8948-341e-45d5-97f7-0fc4eaf04864.png" width="200px" alt="Item page">
</p>



