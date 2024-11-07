# final-model2-exam
Blog Site
A website where a person can sign up, share a post, follow other people, comment on any post, and get notifications on who started following them and on comments after their posts.

Features of the Project
User Registration
Users are registered with Name, Username, Email, Password, Avatar.
Username - Unique
Email - Unique, verification link will be sent to verify an email address.
Password - At least 6 characters long.
Avatar should be an image file only.
User Login
The user can log in via e-mail and password.
Only the verified email can be used for login.
Posting and Commenting
Home Page: On the home page, the posts of the users you follow appear.
All Posts: All the posts would be shown to registered and unregistered users.
Post Details: Every registered and unregistered user is allowed to see the posts, but can comment only when registered; all users are able to read the comments.
Create Post: Only registered users can create new posts. The criteria for creation are that the title must have 5 or more characters; description, 25 or more characters; and one image attached in a file format. Edit Post: It allows only registered users to edit their respective created posts. The criteria remain the same: title and description. In regard to uploading any new image, it will replace the old one. Delete Post: Registered users are allowed to delete only their respective created posts along with the image in storage. Comments and Notifications
Comments: Users can delete only their own comments.
Notifications: Users receive notifications under the following conditions:
Someone follows them
Someone comments on their post.
Profile and Follow System
Each user has their own profile page-unique, for example /azizdevfull.
Profile View:
If viewed your profile, then it displays as my-profile.html
If you view another user's profile, then it displays as user-profile.html.
Follow/Unfollow: Users can follow/unfollow others. It shows the count of followers/following.
User's Posts: Shows the posts of only the selected user.
Notifications
Notifications to Follow: "Azizbek followed you" - it creates a link to his profile when clicked.
Notifications to Comments: "New comment on Post Title" - it creates a link to the post when clicked.


Project Setup
This project can be setup by following the steps below:

1. Clone the Repository
bash

git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
2. Set Up a Virtual Environment
bash

python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\\Scripts\\activate`
3. Install Required Libraries
bash

pip install -r requirements.txt
4. Configure Environment Variables
Create a .env file in the project root and add the necessary environment variables, example:

makefile

SECRET_KEY=your_secret_key
DEBUG=True
ALLOWED_HOSTS=localhost,127.0.0.1
EMAIL_BACKEND

python manage.py createsuperuser
7. Start the Development Server
bash

python manage.py runserver
8. Access the Project
Open your browser and go to http://127.0.0.1:8000 and you will have the Blog Site.
