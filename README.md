# Project 2 - *TwitterEmulator*

**TwitterEmulator** is an android app that allows a user to view his Twitter timeline. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User can **sign in to Twitter** using OAuth login
- [x]	User can **view tweets from their home timeline**
  - [x] User is displayed the username, name, and body for each tweet
  - [x] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
- [x] User can refresh tweets timeline by pulling down to refresh

The following **optional** features are implemented:

- [x] User can view more tweets as they scroll with infinite pagination
- [ ] Improve the user interface and theme the app to feel "twitter branded"
- [ ] Links in tweets are clickable and will launch the web browser
- [ ] User can tap a tweet to display a "detailed" view of that tweet
- [ ] User can see embedded image media within the tweet detail view
- [ ] User can watch embedded video within the tweet
- [ ] User can open the twitter app offline and see last loaded tweets
- [ ] On the Twitter timeline, leverage the CoordinatorLayout to apply scrolling behavior that hides / shows the toolbar.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='/walkthroughTwitter.gif' title='Video Walkthrough' width='400' alt='Video Walkthrough' />

## Notes

This application is built off of a REST Client Template source, provided by CodePath for Android University. This source included under-the-hood managing of API calls and Asynchronous HTTP requests. Handling the OAuth login and managing a RecyclerView were the main challenges in this assignment. However, the process was functionally very similar to the Flicks application created for Project 1.

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
- [RestClientTemplate](https://github.com/codepath/android-rest-client-template/) - Template for a REST client to interact with Twitter API
- [TimeFormatter.java](https://github.com/nesquena/TimeFormatter) - To support converting from absolute JSON timestamp into relative timestamp
- [EndlessRecyclerViewScrollListener.java](https://gist.github.com/nesquena/d09dc68ff07e845cc622) - To support implementing infinite pagination within the application

## License

    Copyright 2021 Joseph Barshay

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.