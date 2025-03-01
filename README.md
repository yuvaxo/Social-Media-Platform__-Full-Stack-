<h1 align="center" style="font-size: 52px;" > Social - A Social Media Platform</h1>

This is a full-stack web application that functions as a social media platform. The application includes key social media features, enabling users to create, like, and comment on posts. The aim is to provide a user-friendly and engaging platform where individuals can share their thoughts, interact with others, and stay connected. Each feature is designed with an emphasis on ease of use, promoting a seamless social media 

## 🛠 Installation & Set Up

1. Clone the Repository

```shell
git clone https://github.com/MSarmadQadeer/SocialSpace.git
```

2. Install Composer Dependencies

```shell
cd SocialSpace
composer install
```

3. Create a .env File

```shell
cp .env.example .env
```

4. Generate an App Key

```shell
php artisan key:generate
```

5. Create an empty database

-   Create an empty database of name **socialspace** or any other name you want, using the database tool you prefer.

6. Configure your .env File

-   Open the **.env** file in your editor and set the **DB_HOST**, **DB_PORT**, **DB_DATABASE**, **DB_USERNAME**, and **DB_PASSWORD** environment variables to match the credentials of the database you just created.

7. Migrate the Database

```shell
php artisan migrate
```

8. Run the Project

```shell
php artisan serve
```

## :whale: Docker Installation & Set Up

1. Download and Install **Docker**
2. Run the following commands:

```shell
git clone https://github.com/MSarmadQadeer/SocialSpace.git
cd SocialSpace
cp .env.docker-example .env
docker-compose up -d
```

## For Jenkins

You need to specify your Docker Hub username and password as environment variables in your Jenkins instance, using the **DOCKER_HUB_USERNAME** and **DOCKER_HUB_PASSWORD** variables respectively.

### Implemented

✅ Log In

✅ Sign Up

✅ Create Post

✅ Edit Post

✅ Delete Post

✅ Like Post

✅ Comment on Post

✅ View Profiles

✅ Upload Profile Pic

✅ Edit Bio

✅ Log Out

### Remaining

❗ Change Password

❗ Delete Account 

## 🧑 Author

#### K YUVA SHANKAR 

If you liked the repo then kindly support it by giving it a star ⭐!

Copyright (c) 2025 K YUVA SHANKAR 
**Developed 
by:** [K.YUVA SHANKAR](https://www.linkedin.com/in/yuva-shankar-4ba786228?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

