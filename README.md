

Key functions

See the cam and the bio without entering the room.
Write notes and show previews in the thumbnails.
Record the cam , also when not in the chat.
Translate the chat in real time to your desired language.
Show a lot of extra info in the bio.
Ban/ignore rooms or users.

Chaturbate reloaded userscript manual.

*Settings menu (next to your user name where you can also set the dark mode).

Thumbnail zoom off : The thumbnails will be bigger if you put your mouse cursor on it,
default is "On".
-Only on the standard thumbnail page.

Preview rooms off : The thumbnails will show a preview if you put your mouse cursor on it,
default is "On".
-Not available if you're a supporter.

Open rooms in new tab : All rooms will be opened in a new tab , default is "Off".

Auto refresh followed off : The page "followed rooms" will refresh if you bring the browser tab to the
foreground , default is "On".

Big Thumbnails : Makes the thumbnails bigger , default is "Off".
-Only on the standard thumbnail page.

Hide male/trans : All male and trans thumbnails will be hidden , the tab's male and trans will be
removed , default is "Off".
-you need to refresh to page to make it effective.
-Not on the page "tags" and page followed cams.
-At the bottom of a thumb page you will see how many rooms are hidden.

Save all settings : All above script settings will be saved and also the settings for "Clean profile",
Dark mode", "Video width", "Theater mode", "Volume" and "Search filters open".
-Only if you're logged-in.
-If you log in again these settings will be restored.

Clear all saved settings: all saved settings will be cleared, on the next log in they will have the
default value.

Ban/ignore this room: You will unfollow the room, erase DM, erase notes and you will ban the room (from seeing your profile,
sending you DM and following you).
The script will hide this room for you and you can never enter it again. It will also remove it from your thumbnails.
Ban's expire in 1 month but this can be made permanent

Manage bans: Unban users you previously banned and make bans permanent. Behind the name it shows how many days are left for the ban
or a lock if it's permanent

*Thumbnail page ( standard , discover and "more rooms like this").

recommended will be removed from your following page and in the following drop down menu.

In the thumbnail you see a note symbol , this symbol will be red if you wrote notes for that model.
If you click it a window will appear where you can write/edit the note.
-Typing "$" will show as the current date.
The model name got the color as she would have in an other chatbox. (grey, light blue, blue .. etc)
The window also got a link to a DM pop-up, if it's green you can send a DM to that model.
-Only if you're logged-in.
-If you made more then 4000 !! notes it may occur that the symbol is not red.

If a room is hidden it will show a "hidden" tag.

If you click the picture you go to the page with video/chat/bio (as normal).

If you click the name under the picture you go to a page that only shows the bio.
(you will not be in the room).
-Only if you're logged-in.

An extra sub-selector next to the gender tabs.

*Room with video. (with or without chat)

There will be a button "VIDEO CONTROLS ON/OFF",
if clicked a pop-up will be visible where you can control the brightness, contrast, saturation,
hue, mirror the video and invert the video.
With "drag" you can move the pop-up to any place on your screen.
There is also a "RECORD/PAUSE" and "STOP RECORD".
Press "RECORD/PAUSE" to start recording , the button will blink red.
Press "RECORD/PAUSE" again to pause the recording , the button will stay red.
and press it again to resume recording.
Press "STOP RECORD" to stop the recording and save it to disk.
-The video adjustments are not visible in the recording.
-You can not close the video control popup while recording.
-The quality of the recordings are reasonable but not extreme good, for good recordings use
an external recorder (the script got many options to copy the video URL).

Snapshots (in the context menu when you right click the video) will be saved as snapshot.jpg

*The chat-box

There will be a button "CHAT CONTROLS ON/OFF".
If clicked a pop-up will be visible where you can set:
-small emoticons , the emoticons will be the same size as the text.
-hide all notices.
-hide all subject change messages.
-hide all mod/fan enter leave messages (only on the English version of the site).
-hide all Grey user chat.
-hide all moderator chat.
-hide all Lovence messages (based on the most common words in those messages).
-hide all tips smaller then a set amount.
-enable translator with language selector. (see below).
-you can see the tokens the model received while you where in the room.
The script will remember it so you can leave or refresh the page and it will continue when you are
back. Click clear to set it back to zero.

The translator will translate all incoming messages to your selected language.
If you enable it the last few messages will be translated and then every incoming message.
When you switch between split mode and theater mode translation takes place when a message arrives.
It only translates real user messages.
It does not translate lovence messages.
It does translate PM messages.
!!!!! this function is experimental and can stop beyond my control. (in fact everything in this script is ... )

If you receive a PM and you are in an other browser tab the browser tab will blink until you open the tab again.

The script skips the "accept room rules" pop up.

*The Bio (on-line room , off-line room or the special bio only page).

Preview of broadcasters media will not be blurred , previews in the pop up are bigger.

There will be a button "CLEAN PROFILE ON or CLEAN PROFILE OFF".
If clicked it will hide/unhide all elements in the broadcaster bio that have a floating position.
It will move down all elements that are to far up.
It will remove all fancy mouse cursors.
-The button will only be there if there is something to clean in the profile.

Links in the profile will no longer be delayed.

Clicking the name on top of the bio will makes you switch between the normal bio and the bio
without cam and chat (it really switches and will not affect the browsers back function).

On a bio only page you have a video player (if on-line) or the last broadcast picture (if available)
or the card image (if available).
-The player got an error handler and will try to get a new video link if the old one fails.
-If the video stream fails too often it will fall back to a mjpg player for 10 seconds before it tries again.
-The player also plays protected streams (if you have access).
-You can resize the video player if you pull the bottom left corner.
-There is a button to open the video controls (see "room with video").
-The player will stop if the browser tab is not on top and resume when it's on top again.
-it will not stop if a recording is active.
-It will use the volume and mute setting of the normal player.

The bio will have a lot of extra information (see below), the button "RELOAD INFO" will reload
this information and it will copy the video URL to the clipboard.

The following info will be added:

-Note field where you can write notes.(Typing "$" will show as the current date).
-Link to a DM pop up that contains the room name.
-Private show costs (only if private enabled).
-Minimum private time. *
-Spy on private costs or disabled.
-Fanclub member spy on private costs. (only if different from normal user spy on private costs).*
-Premium private show costs. (if premium is enabled) *
-Minimum premium private time. *
-Private show recording. *
-Fanclub costs. (if fanclub enabled)
-Broadcasters region. (Not if appear on network sites is "NO" and only if index was made when online).
-Broadcasters nationality. * (Only if set)
-Broadcaster status (only if exhibitionist).
-Amount you tipped the last 24H (only if you tipped).
-Video URL , copy to clipboard/update status (also when off-line and then it will only update the status).
-Alarm On/Off (see below , not an exhibitionist page).
-Video status , on-line , off-line , etc.
-Video quality ( according to chaturbate ...).
-Hidden show message (only if in hidden show on a profile only page).
-Room topic (only if off-line or on profile only page).
-Fan club member (only if you're a fan club member).
-Moderator (only if you're a moderator).
-Low satisfaction score (only if low).
-Number of users in the room (see below).
-Last day online (only if offline). (this is in central American date !)
-Chat rules (click to read)(only if there are chat rules).
-Appear on network sites (only if no).
-A few links to some useful websites. (some are not there if appear on network sites is set to no)

If alarm is turned on a alarm symbol will appear in the browsers tab and the script will check the room
status every minute. You can select alarm only, if the status changes an alarm will sound and the browser tab will
show "ALARM" , or go to page if public.(only if not on a page with chat) If the status changes to public, this can be from offline,
private etc., the room will be opened and the browser tab will come to the foreground.
If you start the "open room when public" alarm while the room is public it must go to an other status first.
Turn it off to stop the alarm or click "reload info".
Remember that when you are in a normal offline room the broadcaster sees you in the chatlist.
The broadcaster will not see you when you're on the special profile page.

If there are users in the room there is next to the number a link that will show the user list.
This list will show the users as in the chat user list.
If they are a follower of the room a little star will show behind the name.
If the user is broadcasting a monitor symbol will appear in front of the name.
If the symbol is followed by a red cross the script has seen the user broadcasting and is now offline.
The online status is not real time, the script keeps a list of all broadcasters.
This list is updated when :
-You enter a room of a broadcaster that is not yet in the list.
-You press "reload info".
The names will link to a profile only page (so you won't enter the room).

*Rooms followed / offline.

In the blue bar is a link that unfollows the complete page and it erases the notes for those rooms.
if you want to keep a room on that page then unfollow it first and the script will follow it again.

*My collection / recorded private shows.

Download link under the video's.

*My collection / purchased media.

Download link under the video's.

*Broadcaster video's (must be opened in a new pop up or tab).

Download link under the video's.

*A room that banned you.

You will be redirected to a only profile page.

*Password room.

You can write notes, open DM window, follow/unfollow and it shows the video status.
This status can be "offline" or "password_protected", if password_protected the room is online.
You can set "check" on or off. If on it will check every minute if you can access the room.
If you can access the room will be opened.
A password room can also have banned your region or gender or you.
In that case you will never have access (nothing will happen if the password is removed)
and follow and DM will not work !

*A room that banned your region or gender.

You will have a mjpeg to video player (no sound, low frame rate) if on-line or the last available picture.
You can write notes.
You can update the video status.(this also updates the player)
Broadcasters region. (Only if broadcaster appears on network sites and if index was made when online).
Broadcasters nationality. (Only if set)
Some links to useful websites.
A link that will search for more info, it will try to find the thumbnail info and shows it on the page. This
only works if the room is public.
