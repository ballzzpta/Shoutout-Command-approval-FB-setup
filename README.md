# Shoutout-Command-approval
Shoutout command with $target approval for playing of video clip

Heres a shoutout command that both the streamer and moderators can use from the trigger **!so @username**. This will also ask the target if they would like a random twitch clip to play. They must reply with the word **yes** in the allotted time (30 seconds) or nothing will happen.

## Things to note:
  * Make sure you disable any shoutout commands(manual trigger) in order for this to work.
  * You can also use the **Viewer arrived** trigger in the events section to allow for an auto shoutout with this function
  * If you want to test it as the streamer, you need to make sure that you go into the yes command and uncheck ignore streamer. Otherwise you need another account to test it

Credits to cky for the approval of playing of clips.


## Install
 To install simply download the Zip and unzip it to your file location 
 
 Import setup for Firebot by going to Settings > Setups > Import Setup
 
 Chose the file "**Shout_out_command_with_video_conformation_request.firebotsetup**" from the location you just unzipped it to, then click Import setup

## Changelog

v3. 5/12/23
 * removed the need for assigning usermetadata
 * removed the need for whileloops
 * added customVariable experation event. - set to 30 seconds

v2. 2/3/23
 * added custom role to only allow for the target to use the yes command. 
    this solves the race issue if more than one person says yes during the shoutout timeframe.
