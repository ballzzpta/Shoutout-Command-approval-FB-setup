# Shoutout-Command with video approval & auto shoutout support
## Shoutout command with $target approval for playing of video clip

Heres a shoutout command that both the streamer and moderators can use from the trigger **!so @username** or !so username. This will also ask the target if they would like a random twitch clip to play. The target can reply with **yes** or **no**. If yes is supplied, it will store their response for future streams and not ask them again when a shout out is given, meaning it will automatically allow a clip to play. If a no is given, it will store their response for future streams and not ask them again when a shout out is given. meaning no clip will play, only shout out will be given. The response will need to be given with in the allotted time (30 seconds) or nothing will happen. As a conformation of time expiring regardless of reply, one final shout out will be given.

## Auto shout out support
In this version, the streamer and moderators now can run a command to add or remove a target from the auto-shoutout list. If a user is on this list, they will now receive a shout out with their respected response for a clip being played. 
!asoadd @target will add the user to the auto-shoutout list
!asosub @target will remove the user from the auto-shoutout list

## Changing clip approval
Users can change their stored response with the following commands
!optin allows a user to start sharing their clips if their previous response was no
!optout allows a user to stop sharing their clips if their previous response was yes

## Things to note:
  * Make sure you disable the following commands or change the names to not interfere in order for this to work.
  * !so
  * !yes
  * !no
  * !optin
  * !optout
  * !asoadd
  * !asosub

## Install
 To install simply download the Zip and unzip it to your file location 
 
 Import setup for Firebot by going to Settings > Setups > Import Setup
 
 Chose the file "**Shout_out_command_with_video_and_auto-shoutout_support.firebotsetup**" from the location you just unzipped it to, then click Import setup

## Changelog

v4. 2/21/24
 * added support for autoshoutout list
 * added ability to store user's response for future streams
 * added ablitiy to change user's prefrences for future streams

v3. 5/12/23
 * removed the need for assigning usermetadata
 * removed the need for whileloops
 * added customVariable experation event. - set to 30 seconds

v2. 2/3/23
 * added custom role to only allow for the target to use the yes command. 
    this solves the race issue if more than one person says yes during the shoutout timeframe.
