# FoxTrailer

Discover Movies and TV shows


![FoxTrailer-screenshots](https://firebasestorage.googleapis.com/v0/b/lovemate-5fd27.appspot.com/o/Screenshot_20191004-161929.png?alt=media&token=a5a725bc-1f55-40b9-8e25-376d5272ab10)


### Download Foxtrailer

- [Download foxtrailer from play store - v0.0.1](https://play.google.com/store/apps/details?id=com.foxtrailer)

### What's included

|                                      Name                                      | Description                                          |
| :----------------------------------------------------------------------------: | ---------------------------------------------------- |
|    [React Native](http://facebook.github.io/react-native/releases/0.61.2/)     | Build Native Mobile Apps using JavaScript and React. |
| [React Native Router Flux](https://github.com/aksonov/react-native-router-flux) | define all the routes in one central place           |
|                          [Redux](https://nodejs.org/)                          | Predictable state container for JavaScript apps.     |
|             [Redux Thunk](https://github.com/gaearon/redux-thunk)              | Thunk middleware for Redux                           |
|                          [ESLint](http://eslint.org/)                          | The pluggable linting utility for JavaScript and JSX |

### Requirements

- [Node](https://nodejs.org/) >= v10.15.3
- [npm](https://npmjs.com) >= 6.8.0

### Installation

Clone this repo

```sh
$ git clone https://github.com/adescode/foxtrailer.git
$ cd foxtrailer
$ yarn install
```

Create `.env` file in your root directory and add the following

```sh
TMDB_URL=https://api.themoviedb.org/3
TMDB_IMG_URL=https://image.tmdb.org/t/p
TMDB_API_KEY=your_tmdb_api_key_here

YOUTUBE_URL=https://www.googleapis.com/youtube/v3/videos
YOUTUBE_API_KEY=your_youtube_api_key_here

```

Get api key -
[TMDB](https://www.themoviedb.org/) -
[Youtube](https://console.developers.google.com)

### How to start

```sh
$ react-native run-android
```

or

```sh
$ react-native run-ios
```

## Extra


React-native >= 0.60 now auto link modules, but some modules require
some manual additions for it to function properly, Modules like

### General
Default image might not work on android debug version, but it works on ios.

## TODO

- [x] Add splash screen and Icon(- [x] Android, - [ ] iOS)
- [x] Add Image gallery
- [x] Implement fast image loader(Implemented still not fast enough)
- [x] Add download button and function to image gallery
- [x] Publish to Google playstore
- [x] Implement Firebase Analytics
- [x] Implement functional share button 
- [ ] Implement functional favorite movie details
- [ ] Remove inline style
- [ ] Allow Android back button on some other screens
- [ ] Create separate element for some functions in details page
- [ ] Clean up the entire code
- [ ] Image download on ios not working.
