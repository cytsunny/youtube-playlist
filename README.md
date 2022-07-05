# Youtube Playlist with Start and End Time

Long long time ago, one is able to set start time and end time when adding a video to a play list. This function is removed ( [Youtube Help ticket related to this](https://support.google.com/youtube/forum/AAAAiuErobUGipu_cCDScI/?hl=en&gpf=%23!topic%2Fyoutube%2FGipu_cCDScI]) ), but I thinks that function should be added back. So, I have written this minimalist player so I can personally use it, and if this page becomes popular, it should be acting as a proof to persuade Youtube to add this function back.

## But why would this function be needed?
The reason I want this function back is because I want to play the singing part of karaoke stream of Vtubers. Currently you can only download the full streaming video, cut out the section you want to play and upload it as new video. Not only it is time consuming, it is stealing view count from the Vtuber who actually sing that song. I feel that if I am listening to a Vtuber's singing plaback, the view count should go to the original creator.

And for meme, as you can see in my demo list right after you get into the page. 


## How to use?
Just click on the play button and you will get a feel how it works.
To change it to your own videos, you can just edit the JSON below. You may not know what is a JSON. Use some common sense and follow the format.

`videoId` is at the end of the video URL. For example,  
https://www.youtube.com/watch?v=EHpxi7khHb0  
The `videoId` is EHpxi7khHb0  

`start` is the start time in seconds. So if you want to start at 3:15, you will need to input ast 3 * 60 + 15 = 195.  
`end` is the end time in seconds. So if you want to end at 3:30, use similar calculation as above and the value should be 210.

## Known bug
If when you are playing the video and you accidentally click outside the time range. For example, your video is to play from 3:15 to 3:30, but you accidentally click 4:15 of the video, you can only play to the end to have the next video loaded.

## New functions?
You are free to fork and make your own version and add your own function.
However, as I said, I believe this should be a function added back to the official Youtube playlist, so hopfully this project should not exists for a long time.
