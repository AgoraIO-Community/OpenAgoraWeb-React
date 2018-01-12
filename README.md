# Agora Video Call

This repository gives you an example about how to integrate AgoraRTC SDK with ReactJs to realize a simple video chat application (just like Skype).

With this sample app, you can:

- Join a meeting room contains 7 people at most (audiences will not be counted) with custom configuration

Type  | Options
------------- | -------------
Identity  | Audience/Audio-Only/Video
Resolution  | Go to [Document Center](https://docs.agora.io/en/) for detail
Transcode  | VP8, H264 (for safari) 
Channel Name  |  As you please

- Disable/Enable video and audio
- Two kinds of layout
- Hide remote window
- Share screen (Install [chrome extension](https://chrome.google.com/webstore/detail/agora-web-screensharing/minllpmhdgpndnkomcoccfekfegnlikg?utm_source=chrome-ntp-icon) first.)
- Leave the room



## Running the App
First, create a developer account at [Agora.io](https://dashboard.agora.io/signin/), and obtain an App ID.

Update "Agora.config.js" in "/src/library/" with your App ID.

``` javascript
export const AOGRA_APP_ID = 'abcdefg'
```

Then download our SDK 'AgoraRTC-*.js', rename it to 'AgoraRTC.js' and put it under the path '/src/library/'. 

Run npm to install dependency.

``` bash
# install dependency
npm install

# serve with hot reload at localhost:3000
npm run start

# build for production with minification
npm run build
```


## Contact Us
- You can find full API document at [Document Center](https://docs.agora.io/en/)
- You can file bugs about this demo at issue

## License
The MIT License (MIT).