# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [x] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

![Alt Text](https://media.giphy.com/media/ZHGtVS4NuBjMEsivK9/giphy.gif?cid=790b76114c599763043ce5646234d90afa7989b3bc3e4ec0&rid=giphy.gif&ct=g)

### Notes
Used the same view controller for accessing movie details from either table or collection views. Currently working on adding movie trailer view. 

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
