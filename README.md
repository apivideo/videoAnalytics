[![badge](https://img.shields.io/twitter/follow/api_video?style=social)](https://twitter.com/intent/follow?screen_name=api_video)

[![badge](https://img.shields.io/github/stars/apivideo/videoAnalytics?style=social)](https://github.com/apivideo/videoAnalytics)

[![badge](https://img.shields.io/discourse/topics?server=https%3A%2F%2Fcommunity.api.video)](https://community.api.video)

![](https://github.com/apivideo/API_OAS_file/blob/master/apivideo_banner.png)

[api.video](https://api.video) is an API that encodes on the go to facilitate immediate playback, enhancing viewer streaming experiences across multiple devices and platforms. You can stream live or on-demand online videos within minutes.

# videoAnalytics
NodeJS app to retrieve and process video analytics from you api.video video.

## Live demo

https://whoswatched.a.video

## Blog post

https://api.video/blog/tutorials/video-analytics-a-primer


## What this app does

The landing page is a simple form. It lists 3 videos in my api.video account.  Click one, and a new page loads.  On the backend, the NodeJS SDK calls the analytics endpoint for the video selected.  The API returns all of the views for the video, and the backend tabulalates view per: country, device, and Browser, 

These results and the video are displayed on the webapge.

##  What we are showing

This is a very simple application to demonstatrate how easy it is to access and parse the analytics that are created when a viewer watches your video with the api.video player.
