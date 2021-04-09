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



<img src="https://raw.githubusercontent.com/sundries-hub/LifeReviewFile/master/uPic/Kapture 2021-04-09 at 16.43.01.gif" style="zoom:67%;" /><br>

### Notes

I found that some superhero movies don't have a backdrop, and open their detail page would result an error. Finally I use a Nil-Coalescing Operator to set the backdrop path to empty value if the movie has no backdrop.

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

**Normal (iPhone 8)**

<img src="https://raw.githubusercontent.com/sundries-hub/LifeReviewFile/master/uPic/flix_wt1.gif" alt="flix_wt1" style="zoom: 75%;" />



**Larger Screen (iPhone 12 Pro Max)**

<img src="https://raw.githubusercontent.com/sundries-hub/LifeReviewFile/master/uPic/Kapture 2021-04-01 at 13.18.17.gif" style="zoom: 67%;" />



**Horizontal** 

<img src="https://raw.githubusercontent.com/sundries-hub/LifeReviewFile/master/uPic/Kapture 2021-04-01 at 13.27.41.gif" style="zoom:67%;" />



**Running on real device (iPhone 12 Pro)**

<img src="https://raw.githubusercontent.com/sundries-hub/LifeReviewFile/master/uPic/RPReplay_Final1617590538.gif" style="zoom:67%;" />



### Notes
I had some difficulty when dealing with the autosize configuration. It's not easy to decide which side to align and align to where. I spend about 30 mins to set and fix autosize. 

I use iOS 14.5 beta on my phone so I found I need to use the Xcode beta to build on my phone. I also had some issue with the signature, and it took me some time to resolve it.