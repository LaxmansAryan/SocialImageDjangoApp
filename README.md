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
