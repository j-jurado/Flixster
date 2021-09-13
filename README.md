# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [x] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device.

### App Walkthrough GIF
![Alt Text](https://media.giphy.com/media/oxvP1p51wWPa0DCJH7/giphy.gif?cid=790b7611543887b1985ebb18e03c4612e72bb66f7d74ffe3&rid=giphy.gif&ct=g)

Link if GIF not working: [GIF Link](https://i.imgur.com/QWLLUpD.gifv)

### Notes
Had difficulties implementing auto-layout so that the positioning of the logo on the launch screen was predictable across all platforms. My best solution included centering the logo horizontally and vertically on the screen and placing the text a few pixels underneath it (it's hard to see in the gif as the app loads quickly). Also had issues with movie titles extending as much as the screen would allow. After setting right contraints to 0, this was solved.