# POLYVHACK
SAVE YOUR TIME. AND SAVE ELECTRICITY FOR MINING.


My mom is a healthcare worker who is about to retire, But her leader will ask her to take some unrelated exams, such as the Internet, AI, technological innovation, etc.
This is not environmentally friendly.
  
She can only ask me for help, I find the video play by HTML5 player, but I can't skip the video and it will be paused by a popup window for questions in class, so I have to watch the teaching video completely.
  
As a developer, I am curious how to achieve. The truth is a video product by POLYV, I read their code and documentation.
  
https://dev.polyv.net/2020/videoproduct/v-player-sdk/v-player-sdk-web/v-player-sdk-web-feature/play/


function ban/banByLimitTime implement ban seek by setting this currentTime property. so reset ban_seek/ban_seek_by_limit_time to skip the video, set is_interaction as off to stop the popups.
  
However, If backend detection of video progress, you still can't skip, but we can set video triple speed:
  
`document.getElementsByTagName("video")[0].playbackRate = 3;`

