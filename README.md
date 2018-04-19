# Motivation
I will be adding a Spotify client for my LG Smart TV because their App Store does not currently have a Spotify App or a music listening app that I subscribe to. Currently, there is no plan to get this approved on the app store due to potential licensing issues with Spotify/LG/Sony. This is for demonstration purposes only and I will only be using the 30s audio clips. It might be possible to use the [Web Playback SDK](https://beta.developer.spotify.com/documentation/web-playback-sdk/) to get full tracks.

# Challenges
Smart TVs have the following restrictions and challenges:
- Limited hardware specs
- Navigation challenges compared to traditional mouse/keyboard
- React renders computationally expensive (for TVs)

# Tools to Use
- React to manage UI
- Redux to manage state
- webOS SDK to run on emulator and on my own TV
- Spotify API
- Webpack bundle files

# How to Run (Initial)
- yarn start
- visit [localhost:8000](localhost:8000)

# Progress
- [x] Set up initial repo
- [x] Set up initial folder structure
- [ ] Set up initial views (no data or dummy data)
- [ ] Implement OAuth for Spotify
- [ ] Pull in data from Spotify
- [ ] Create initial Spotify Components
- [ ] Create Redux store
- [ ] Deploy onto live TV app
- [ ] Add screenshots/gifs demo
