# YelpCamp

Full stack application created during the "Web Developer Bootcamp" course on Udemy by Colt Steele.
YelpCamp is a campground review application for campground visitors. Users have the ability to create and review campgrounds all over the world as well as comment and review campgrounds created by other users.

## Images

> #### Homepage

> ![homepage](https://user-images.githubusercontent.com/75185644/128648585-49098947-d776-45c4-b59d-ef6c546a42d9.PNG)

> #### Campgrounds Page

> ![campgrounds](https://user-images.githubusercontent.com/75185644/128648592-5f8c69c7-ef7e-4d2b-9841-09585aac6459.PNG)

> #### Campground Review Page

> ![campground](https://user-images.githubusercontent.com/75185644/128648593-5d1c7d50-1d68-42f1-a341-9b539bda8b80.PNG)

> #### New Campground Page

> ![newcamp](https://user-images.githubusercontent.com/75185644/128648594-46dfee27-331e-42b6-913f-49281898dbc1.PNG)

## Functionalities

- All registered users have CRUD capabilities while logged in.

- From the campgrounds route, users can view all the campgrounds and a map showing their respective locations throughout the world. If logged in, users will also have the ability to create a new campground from this route

- From an individual campground route, users have the ability to rate and comment on that campground. If the user is the creator of the campground, they may also edit or delete the campground from this route.

## Technologies Used

### Frontend & Backend

- Javascript
- Express
- Node
- MongoDB
- Mongoose
- Nodemon
- HTML5
- CSS3
- Passport
- Heroku
- Mapbox
- Cloudinary

## Getting Started

This app contains API secrets and passwords that have been hidden in an .env file for security purposes, so the app cannot be run with all of its features on your local machine without these variables. However, feel free to clone this repository, create an .env file and add values to the following variables:

```
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_KEY=
CLOUDINARY_SECRET=
MAPBOX_TOKEN=
DB_URL=
SECRET=
```

### Clone or download this repository

```sh
git clone https://github.com/dev382/YelpCamp.git
```

### Install dependencies

In the directory of the folder named YelpCamp, which contains the files of the repositiory, run the following command from your terminal:

```sh
npm install
```

or

```sh
yarn install
```

### Run the app from your terminal

Once installation is complete, run the following command from your terminal:

```sh
npm start
```

### Launch the app from your web browser

Open your web browser and navigate to:

```sh
localhost:3000
```

The app should now be running.
