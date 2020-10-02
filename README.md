# flixster

Flixster is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

---

## Flixster Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="http://g.recordit.co/gzDg90atXn.gif" width=250><br>

### Notes
I ran into issues when trying to create the grid view for my movies. At first I ended up creating a UIView instead of a UIImageView which caused an error when I tried to run the program. When I went back to fix this I also re-created my collection view, but didn't realize at some point I accidentally resized it. When I changed my "estimate size" setting to none in order to fix the small poster issue, I ended up just getting one small scrollable cell instead of having my posters fill the whole screen! At first I thought it was an issue with the cell size, but then after some tinkering realized it was actually the entire collection view that had become too small and was able to fix it. I learned that it's important to pay attention to details and make sure to be careful when going back and updating things! I also really liked learning how to create variable sizing based on the size of the phone screen since I'm a sucker for good design and didn't like how my app would originally not look how I wanted it on various phone sizes!


## Flixster Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="http://g.recordit.co/vuFFTwmep5.gif" width=250><br>

### Notes
This app was really fun to make and I learned a lot about the basics of app creation, including formatting tables and receiving information from APIs to use in my apps. Using a podfile was something very new to me and I enjoyed seeing how it transformed my app from plain ol' cells with writing into actual movie posters! 
