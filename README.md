# twittee-flexir-js
TWITEE is a mini and substandard runoff of Twitter. Users register and login and can put up
anything that crosses their mind. The whole world can view their twits and comment on their
twits /and like them. We want you to build this project using Node.JS as your backend tool.
After which you will then implement your solution using a frontend technology, the endpoint
created in your solutions will then be consumed with an interface


# DETAILED DESIGN
Please follow the detailed technical design below as closely as possible.
● Each user should have an account detail containing their name, email, password and
date created
● Your app should send onboarding email to the user
● Every authenticated user can comment or like every post that is posted.
● Only the user that owns a post can delete that particular post.
● Users can log out and get redirected to the login route
● Unauthenticated users cannot interface with the app.


In short, a feature list of the app will be
1. User registration and authentication
2. User Log in
3. User POST twit
4. User DELETE twit (if owned by user)
5. User POST comments under twits
6. Post page shows all posted twits and comments under twits (Each twit will show the
name of the poster, the date posted, the time posted, the posted content, like button and
a comment form)
7. User log out
