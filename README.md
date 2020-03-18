# Smart-Brain

Smart-Brain is a facial recognition app made with React on the front-end and Node on the back-end. This was the second React project I built while taking the Udemy course The Complete Web Developer in 2020: Zero to Mastery by Andrei Neagoie, as well as the first Node back-end I ever built. 

The app has basic user authentication by storing hashed passwords in the Postgres database. New users can register with their email and password, which don't actually have to be real. After logging in, users can submit the URL of a .jpg file and the app will outline the first face it detects in the image with a blue box.

The backend API was implemented in a separate repository, which can be found [here](https://github.com/djbowers/smart-brain-api).

My next step for this project is to bring the back-end into this repository and add test automation for the major user flows. 
