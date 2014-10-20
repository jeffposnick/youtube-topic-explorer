YouTube Topic Explorer
======================
YouTube Topic Explorer allows you to view a personalized list of ([Freebase/Open Knowledge Graph](http://www.freebase.com/))
that you might be interested in, based on your YouTube watch history, likes, favorites, watch later list, and uploads.

Try It!
=======
You can view a live demo at http://jeffposnick.github.io/youtube-topic-explorer/

Technologies Used
==================
The data retrieval is powered by the [YouTube Data API v3](https://developers.google.com/youtube/v3/) and the [Freebase API](https://developers.google.com/freebase/v1/).

This project is a reimplementation of an [earlier project](https://code.google.com/p/yt-topic-explorer/), and is written
using [Polymer](https://www.polymer-project.org/) web components.

The project makes use of the following Polymer elements:
  - [`<google-youtube-video-wall>`](https://github.com/GoogleWebComponents/google-youtube-video-wall)
  - [`<google-signin>`](https://github.com/GoogleWebComponents/google-signin)
  - [Material Design/Paper elements](https://www.polymer-project.org/docs/elements/paper-elements.html)

