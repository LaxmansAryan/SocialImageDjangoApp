# Social Image Sharing App
This is a social application that allows users to share images they find on the internet. It provides a platform for users to discover, share, and interact with images from various sources. The application is built using the Django framework and utilizes PostgreSQL as the database management system.

## Features
The social image sharing app incorporates the following key features:

- Authentication System: Users can register an account, log in, and manage their profile. The authentication system also includes functionality for users to change or reset their passwords securely.

- Follow System: A follow system enables users to connect with each other on the website. Users can follow/unfollow other users, allowing them to curate their content feed based on the people they follow.

- Image Sharing: Users can easily share images from any website by providing the image URL. The application fetches the image and stores it in the database, associating it with the user who shared it. The shared images are displayed in the user's profile and the activity stream.

- Activity Stream: The activity stream provides a personalized feed for users to view the content uploaded by the people they follow. Users can stay updated on the latest images shared by their connections, fostering engagement and interaction.

## Installation and Setup
To set up the social image sharing app locally, follow these steps:

- Clone the repository:
git clone https://github.com/LaxmansAryan/SocialImageDjangoApp.git
- Install dependencies:
  cd bookmarks
  pip install -r requirements.txt

- Configure the database:
  Install and configure PostgreSQL.
  Update the database settings in settings.py to connect to your PostgreSQL instance.

- Apply database migrations:
  python manage.py migrate

- Start the development server:
  python manage.py runserver

- Access the app:
  Open your web browser and visit http://localhost:8000 to access the social image sharing app.

## Usage
Once the application is up and running, users can perform the following actions:

- Register a new account or log in with existing credentials.
- Edit their profile information, including avatar, bio, etc.
- Follow/unfollow other users to customize their content feed.
- Share images by providing the image URL.
- View images shared by people they follow in the activity stream.
- Interact with shared images through likes, comments, etc.

## Contributing
Contributions to the social image sharing app are welcome! If you'd like to contribute, please follow these steps:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and commit them with descriptive messages.
- Push your changes to your fork.
- Submit a pull request detailing the changes you've made.
- Please ensure that your contributions align with the project's coding standards and adhere to the existing style guide.

## Contact
If you have any questions, suggestions, or feedback, please feel free to contact us sawantaryan16@gmail.com.

## Screenshots
- Login Page
<img width="960" alt="1" src="https://github.com/LaxmansAryan/SocialImageDjangoApp/assets/102072945/d991ec1e-ed63-451b-a2c6-5a5987eea627">


- Forgotten Password
<img width="960" alt="2" src="https://github.com/LaxmansAryan/SocialImageDjangoApp/assets/102072945/920250c4-0e8c-4e42-93a6-37da507cd154">


- Registration
<img width="947" alt="3" src="https://github.com/LaxmansAryan/SocialImageDjangoApp/assets/102072945/f2d701eb-42bb-4920-b3c6-a8dfc2eede05">


- Welcome Page
<img width="960" alt="4" src="https://github.com/LaxmansAryan/SocialImageDjangoApp/assets/102072945/22c4762e-4491-4c29-99ac-135bf83564c5">


- Dashboard
<img width="960" alt="5" src="https://github.com/LaxmansAryan/SocialImageDjangoApp/assets/102072945/641fba9e-a8a3-48c5-afa6-7547057c9d88">


- Edit Page
<img width="947" alt="6" src="https://github.com/LaxmansAryan/SocialImageDjangoApp/assets/102072945/329d1810-116f-42e1-8bda-8f6cb37ffbb3">


- Dashboard with Latest Updates
<img width="960" alt="7" src="https://github.com/LaxmansAryan/SocialImageDjangoApp/assets/102072945/07569065-40d3-4d07-9673-991f2a11b1de">


- Dashboard Again 
<img width="960" alt="11" src="https://github.com/LaxmansAryan/SocialImageDjangoApp/assets/102072945/96d64927-280c-437b-b44e-b090778a9d08">


- Images Bookmarked
<img width="960" alt="8" src="https://github.com/LaxmansAryan/SocialImageDjangoApp/assets/102072945/e381df9c-603f-44cb-8fdd-6a657a493e84">


- Image detail
<img width="948" alt="9" src="https://github.com/LaxmansAryan/SocialImageDjangoApp/assets/102072945/a6536834-6582-421f-84e4-089161bbbf98">


- Accounts
<img width="960" alt="10" src="https://github.com/LaxmansAryan/SocialImageDjangoApp/assets/102072945/520e08f0-fef4-4ee5-9c34-0ba62497db7c">
