---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "BookingApp"
date: 2022
published: true
labels:
  - Java
  - git
  - fxml
  - junit
summary: "A desktop application that handles the bookings for a hotell."
---

<img class="img-fluid" src="../img/booking-app/booking-square.png">

The BookingApp is a desktop application that could be implementet by any hotel! The app has an interactive view of all the rooms on a current date, displays current and previous bookings and let you add new bookings. And the most important: it lets you know how much these bookings will cost.

How to use the app is enclosed on the right hand side of the screen. This part is all in Norwegian. The application requires the user to log in. Due to this being a school project, the credentials are listed on the log in screen, this would of course be removed before giving the application to customers.

The application has only one view, so you get all your info in one place. A table showing the hotel's 9 rooms is live updated, and will show availability immediatly when you change the date. The bookings and booking archive is stored in local .csv-files. The applicatoin will always start up with displaying today's date, and will not let you add bookings back in time. The price for the room is calculted based on formulas including type of room and how many days in advance the booking happens. You can close your applicatoin any time and be safe that the new bookings are already saved, and will be shown the next time you open the application.

The project was done as a part of a intro to OOP-class. I wrote it together with a partner, Benjamin Bøe, and this was our first time using Java, fxml and junit. The fxml files were created interactivly with the program SceneBuilder. As this was my first major project, I developed a much bigger understanding of how programs can use a variety of files, and how important it is to write good tests for your code. The juint-test revieled several mistakes in our code, that we wouldn't have discovered without them.

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>
