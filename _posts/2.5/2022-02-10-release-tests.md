---
layout: page
title: 'Testing a release'
category: 2.5
date: 2022-02-10 21:59:03
order: 6
---

This document is meant to be a combination of manual and (labeled so) automated tests, listed per feature of BigBlueButton.

The <b>automated tests</b> are only a portion of the testing done before a release. Ideally they should be triggered often, for example when testing pull requests, or once a day automatically.

The <b>manual tests</b> really help to ensure release quality. They should
be performed by humans using different browsers. It is usefull to have multiple
humans performing these tests together. You should plan at least an hour to perform
all of these tests.

## Presentation

### Uploading a Presentation

1. As a moderator, select Moderator/Presenter Action menu (+)

2. Choosing "Manage presentations"

3. Uploading presentation options:

   - using Drag and Drop
   - Upload presentation using File Explorer(browsing for files.)

4. You should see the notification displaying the upload progress

5. Presentation should appear on All Clients in sync with updates, and All Clients should see the notification with the new presentation name

### Enabling and Disabling Presentation Download

1. Select Moderator/Presenter Action menu

2. Choose "Manage presentations"

3. Set current file as enabled/disabled for download:

   3.1 Setting current file as enabled for download will allow users to download current file.

   3.2 Removing presentation for download will no loner allow users to download current file.

### Deleting Presentation

1. Select Moderator/Presenter Action menu

2. Choose "Manage presentations"

3. Selecting trash icon to delete

4. Choose confirm

### Uploading multiple presentations

1. Select Moderator/Presenter Action menu

2. Choose "Manage presentation"

3. Select multiple presentations at once using Browse for files option

4. Set a current presentation

5. Select upload

6. You should see the notification displaying the upload progress

7. Current selected file should appear for all clients

### Navigation

1. Locate slide navigation bar

2. Select next slide (>)

3. Select previous slide (<)

4. Use dropdown to select a specific slide.

5. The selected slide should appear

### Zoom

1. Zoom in (+) and out (-) by clicking in the buttons or using the scroll

2. Using the Pan tool, move document around while zoomed in.

### Draw and Pan

1. Zoom in by (+)

2. Changing pan tool to pen tool

3. Draw in the whiteboard area

4. Hold down the space while moving mouse to pan.


### Minimize/Restore Presentation

1. Clicking on Share webcam.

2. Minimizing presentation.

3. Presentation should be minimized, the button should change to "Restore presentation"

4. Selecting "Restore presentation"

5. Presentation should be restored.

(Note : Presentation area will auto expand when the presenter engages Screen Sharing or YouTube Link Share)

### Full Screen option

1. Click on full screen button ("Make presentation fullscreen")

2. Application should go to full screen

3. Draw on the whiteboard

4. Select Escape key on local keyboard.

5. Application should return to normal screen

6. Click on full screen button again

7. Click on "Undo Presentation fullscreen" button

8. Application should return to normal screen

### Fit to width option

1. Click on "Fit to width" button

2. Presentation should be re-positioned to fit to width

3. Click on "Fit to page" button

4. Presentation should return to normal view

### Make viewer a presenter

1. Click viewer icon from users list

2. Selecting make presenter for the user.

3. Viewer selected should have all presenter capabilities and presenter Icon should appear over user icon in the users list.

### Taking presenter status back

1. In order to take back the presenter, can be done in following ways:

   1.1

- Click on your user icon in users list.
- choose "Take presenter"

  1.2

- Select Moderator/Presenter Actions menu (+)
- choose "Take presenter"

You should now have presenter capabilities and presenter icon should appear over your icon in the users list.

## Webcams

### Joining Webcam

1. Click on "Share webcam" icon

2. Allow browser permissions if prompted

3. Select your webcam

4. Choose the video quality from the available option

5. Select the virtual background setting

6. Click "Start sharing"

7. A small webcam video should show up and the camera share will start highlighting

8. Click "Stop sharing webcam"

9. The webcam video should disappear

### Make webcam fullscreen

1. Click the webcam's fullscreen button ("Make [user name] fullscreen").

2. The webcam should appear in fullscreen.

3. Press the Esc key.

4. The webcam should exit the fullscreen and go back to normal size.

5. Click the webcam's fullscreen button again.

6. Click the undo fulscreen button ("Undo [user name] fullscreen").

7. The webcam should exit the fullscreen and go back to normal size.

### Focus/unfocus a webcam

1. Join meeting with at least 3 webcams.

2. Hover over one of the webcam's user name.

3. Select dropdown and choose "Focus".

4. The chosen webcam should expand (not fullscreen), while other webcams become smaller.

5. Hover over the focused webcam's user name.

6. Select dropdown and choose "Unfocus".

7. The webcams should get back to normal sizes and positions.

### Maximize/minimize webcam

- With webcams shared, click on the Hide Presentation icon to minimize presentation area and maximize webcam.

The presentation will be minimized, and a button will be highlighted to restore the presentation.

### Mirror webcam

1. Join meeting with a webcam.

2. Hover over the webcam's user name.

3. Select dropdown and choose "Mirror".

4. Webcam's stream should flip horizontally.

5. Hover over the webcam's user name.

6. Select dropdown and choose "Mirror" again.

7. Webcam's stream should get back to normal.

### Drag webcams

1. Share webcams

2. Drag to middle, top or bottom.

3. Release webcams in greyed area on screen.

Webcams will be moved when mouse is released. (Note: When only one webcam is shared user can drag and drop webcam anywhere in the presentation area)

### Switching to Default webcam

1. Click the share/stop sharing webcam icon twice (once to remove current webcam connection and again to re-prompt the webcam join modal)

2. Allow browser permissions if applicable

3. Choose webcam (switch from previous default device)

4. choose the video quality

5. click on Start Sharing

### Resizing one or multiple Webcams

A. Resizing one single webcam.

- Share a webcam
- Drag the bottom of the webcam window
- Increase or Decrease the size of the webcam.

The webcam will be resized as per the size we want.

B. Case of more than one webcam.

- Share atleast 2 webcams
- Drag the bottom of the webcams container
- Increase or Decrease the size of the webcams.

The webcams should be resized as per the size we want.

### Stop Sharing webcam

1. Start sharing webcam.

2. Click "Stop sharing webcam".

3. The webcam sharing should stop.

4. Start sharing webcam again.

5. Click "Open advanced settings" icon near the "Stop sharing webcam" button.

6. Click "Stop sharing".

7. The webcam sharing should stop.

## Screenshare

### Sharing screen in Full Screen mode

1. Clicking on share screen icon

2. select full screen mode or share entire screen (browser dependent)

3. Choose a screen to share

4. select share

The screen is displayed for the presenter/moderator and the viewer,
while the sharescreen button is highlighting and displayed only for the presenter and (for the viewer or the moderator, the presentation will be replaced with the screensharing)

### Sharing screen in Application Mode

1. Click on share screen icon

2. Select application mode

3. choose application to share (note : application must already be open on the desktop)

4. select screen to share

5. select share

The screen is displayed for the presenter and the viewers, the screen share updates for the viewers when the presenter makes changes in the application - no secondary windows or pop ups appear.

Note : When sharing in application mode any secondary windows, pop up messages or search menus are not transmitted to the viewer even if they generate from within the application being shared, and When using microsoft office applications, while using application mode any and all updates to the application are not transmitted by the browser to the viewers

### Stop screen sharing

- Click on stop sharing screen toast message

  OR

- select screen share / stop screen share icon

The screen sharing stops, a sound effect of disconnection is heard and the presentation is restored.

## Breakout rooms

### Moderators creating breakout rooms and assiging users

1. Click "Manage users" (cog wheel icon in the user list).

2. Select "Create breakout rooms".

3. "Breakout Rooms" modal should appear.

4. Choose number of rooms and duration.

5. Two ways to assign users: Drag and drop users to the rooms or .

6. Click "Create" button.

7. Viewers: invite screen should pop up. Moderators: "Breakout Rooms" section should appear in the left-hand panel.

8. Viewers: click "Join room" button, viewer should successfully join the breakout room. Moderators: click "Breakout Rooms", click "Join room" (moderators should only see that button for the rooms they got invited to), moderator should successfully join the breakout room.

9. All the selected settings are applied to the rooms.

### Viewers choosing the breakout rooms

1. Click "Manage users" (cog wheel icon in the user list).

2. Select "Create breakout rooms".

3. "Breakout Rooms" modal should appear.

4. Choose number of rooms and duration. Select the "Allow users to choose a breakout room to join" checkbox.

6. Click "Create" button.

7. Viewers: invite screen should pop up (including the rooms dropdown). Moderators: "Breakout Rooms" section should appear in the left-hand panel.

8. Viewers: select the room using the dropdown, click "Join room", viewer should successfully join the selected breakout room. Moderators: click "Breakout Rooms", click "Ask to join" for the specific room, moderator should successfully join the breakout room.

9. All the selected settings are applied to the rooms.

### Logout from a Breakout Room

1. Join breakout room.

2. Click "Options" and then "Leave meeting".

3. You should successfully leave the breakout room and shouldn't be redirected to the feedback screen.

### Switch between breakout rooms

1. Create breakout rooms.

2. As moderator, click on the breakout rooms control panel and choose "Ask to join" or "Join room" to join specific room.

3. Moderator should successfully join the room you chose.

### Destroy breakout rooms

1. Join breakout room as moderator.

2. Inside the breakout rooms control panel ("Breakout Rooms" button in the left-hand panel), select the "Breakout options" dropdown and choose "Destroy breakouts".

3. All of the breaout rooms should end and all users should get back to the main room. If users already got the audio on, they shouldn't get propmted for the audio modal.

### Reset duration for a breakout room

1. Join breakout room as moderator.

2. Inside the breakout rooms control panel ("breakout Rooms" button in the left-hand panel), select the "Breakout options" dropdown and choose "Manage duration".

3. Edit the duration and click "Apply".

4. The duration of the breakout room should reset.

## Audio

### Join audio

1. Join a meeting.

2. Click microphone and allow for browser permissions (if applicable).

3. Verify if you can hear yourself in the echo test.

4. Click "Yes".

5. You should be redirected to the meeting and your microphone button and avatar in the in the user list should indicate the you are unmuted.

### Mute/unmute

1. Join a meeting.

2. Click microphone and allow for browser permissions (if applicable).

3. Verify if you can hear yourself in the echo test.

4. Click "Yes".

5. The microphone button should indicate the unmuted state.

6. Click the microphone button several times. You should change between unmuted and muted states and the button should indicate it.

### Leave audio

1. Join meeting with audio.

2. Click "Leave audio".

3. You should hear the disconnect sound and leave audio. "You have left audio conference" notification should appear.

### Join without audio

1. Join a meeting.

2. Click "x" in the audio modal.

3. You should be redirected to the meeting and your microphone button should not be highlighted.

### Listen Only Mode

1. Join a meeting.

2. Click "Listen only" in the audio modal.

3. You should be redirected to the meeting and your microphone button and user list avatar should indicate that you are in listen only mode.

### Testing microphone

Click on microphone and go through echo test and then click No.

- You should see Change your audio settings dialog

### Choosing different sources

1.  In the Change your audio settings, choose different microphones
2.  choose different speakers
3.  click Play test sound
4.  click Retry and then click Yes.

- You should be able to use different microphones and speakers and hear yourself in the echo test with varying combinations of microphone/speakers. When you click 'Yes', your microphone should be highlighting.

#### Joining with phone

- Joining the audio conference with a phone: The viewer should mute/unmute with the moderator's actions.

- For mute/unmute: Press the '0' key on the phone's keypad to mute/unmute (Note : In production Moderator cannot unmute other users unless enabled at the account level)

- For moderator mute/unmute dial in (select dial in from users list and choose mute/unmute) : The audio state should mute/unmute accordingly. (Note : In production Moderator cannot unmute other users unless enabled at the account level )

- Remove dial in : As a moderator click the phone number in the Users list and choose remove user. The phone hangs up and user no longer appears in the Users list

### Talking Indicator

Enable Microphone : This will cause a user name to appear on left top corner of the Presentation Area whenever a User talks.

#### Muting user from Talking Indicator

1.  As Moderator: Click on the name of User appearing in top left corner of the Presentation area.

- The Talking User gets muted.

2.  As Viewer: Click on the name of User appearing in top left corner of the Presentation area.

- The Talking User should not get muted

## Closed Captions

### Launch closed captions menu (and toggle the menu)

1. Join meeting as moderator.

2. Click "Manage users" (cog wheel icon in user list) and select "Write close captions".

3. Select the language. Click "Start".

4. The closed captions button should appear in left-hand menu (above the shared notes) and it should indicate the chosen language.

5. Type text into closed captions panel.

6. Click on the language button in the closed captions menu.

7. The closed captions menu should close.

8. Click on the closed captions button above the shared notes in the left-hand menu.

9. The closed captions menu should open.

10. Click the same button again.

11. The closed captions menu should close.

### Closed captions formatting

1. Join meeting as moderator.

2. Click "Manage users" (cog wheel icon in user list) and select "Write close captions".

3. Select the language.

4. Type text into closed captions panel.

5. Test all of the available formatting tools that are available (Bold, Italic, ...). Whatever is typed as text should be shown exactly as intended.

### View/Hide closed captions

1. Join as viewer or moderator.

2. Click "Start viewing closed captions" button.

3. The closed captions button should be highlighted.

4. Choose the language and other UI settings for closed captions. Click "Start".

5. Join meeting as moderator.

6. Moderator: click "Manage users" (cog wheel icon in user list) and select "Write close captions", then select the language.

7. Moderator: Type text into closed captions panel.

8. User: should see the closed captions on top of the whiteboard. The text should be the same as the one typed by moderator. The closed captions should appear according to the UI settings chosen by the user.

9. User: click the closed captions button.

10. User: closed captions button should not be highlighted anymore, the closed captions should disappear.

## Whiteboard

### Use pencil tool

1. Join meeting with two or more users.

2. Presenter: Click "Tools" whiteboard button.

3. Presenter: Select "Pencil".

4. Presenter: Draw on the whiteboard area.

5. All clients should see the drawing.

### Change pencil tool thickness

1. Join meeting with two or more users.

2. Presenter: Click "Tools" whiteboard button.

3. Presenter: Select "Pencil".

4. Presenter: Click "Drawing thickness" button.

5. Presenter: Select a new thickness.

6. Presenter: Draw on the whiteboard area.

7. All clients should see the drawing and the drawing should appear according to the chosed thickness.

### Changing pencil tool colour

1. Join meeting with two or more users.

2. Presenter: Click "Tools" whiteboard button.

3. Presenter: Select "Pencil".

4. Presenter: Click "Colors" button.

5. Presenter: Select a new color.

6. Presenter: Draw on the whiteboard area.

7. All clients should see the drawing and the drawing should be colored accordingly.

### Use shape tools

1. Join meeting with two or more users.

2. Presenter: Click "Tools" whiteboard button.

3. Presenter: Select available shapes one by one and draw on the whiteboard area. All clients should see the shapes on the whiteboard.

### Change shape tool thickness and color

1. Join meeting with two or more users.

2. Presenter: Click "Tools" whiteboard button.

3. Presenter: Select available shapes one by one and draw on the whiteboard area. Change their thickness and color. All clients should see the shapes on the whiteboard with the correct thickness and color.

### Use text tool

1. Join meeting with two or more users.

2. Presenter: Click "Tools" whiteboard button.

3. Presenter: Select "Text".

4. Presenter: Adjust the font size and color.

5. Presenter: Create a text box on the whiteboard and type text inside. Click somewhere else on the whiteboard.

6. All clients should see the text inside a text box. The text should appear according to the selected font size and color.

### Undo last annotation

1. Join meeting with two or more users.

2. Presenter: Click "Tools" whiteboard button, choose annotation and put two such annotations on the whiteboard.

3. All clients should see both annotations.

4. Presenter: Click "Undo annotation".

5. All clients should see only the first annotation now.

### Clear all annotations

1. Join meeting with two or more users.

2. Presenter: Click "Tools" whiteboard button, choose annotation and put two such annotations on the whiteboard.

3. All clients should see both annotations.

4. Presenter: Click "Client all annotations".

5. Both annotations should disappear for all clients.

### Multi-user whiteboard

1. Join meeting with two or more users.

2. Presenter: click "Turn multi-user whiteboard on", the button's icon should change and the counter of the current number of viewers should appear.

3. All clients should be able to draw and see each other's changes on the whiteboard.

3. Join meeting with another viewer.

4. The counter of multi-user whiteboard viewers shouldn't change. The recently joined viewer shouldn't be able to draw.

5. Presenter: click "Turn multi-user whiteboard off", button's icon should change back to normal. All clients shouldn't be able to draw anymore.

6. Presenter: click "Turn multi-user whiteboard on", the button's icon should change and the counter should include the recently joined viewer.

7. All clients should be able to draw and see each other's changes on the whiteboard (including the recently joined viewer).

## YouTube Video sharing

### Start YouTube video sharing

1. Join a meeting.

2. Presenter: Click on the action ("+" icon) button.

3. Presenter: Select "Share an external video".

4. Presenter: The popup modal should appear. Paste a YouTube link there.

5. Presenter: Click "Share a new video".

6. All clients will see the YouTube video playing in the presentation area.

### Volume/Skipping/Pausing

1. Join a meeting.

2. Presenter: Click on the action ("+" icon) button.

3. Presenter: Select "Share an external video".

4. Presenter: The popup modal should appear. Paste a YouTube link there.

5. Presenter: Click "Share a new video".

6. Presenter should be able to perform all the available actions on the YouTube video such as muting, increasing/decreasing the volume, pausing/resuming.

7. The result of those actions should be visible for all clients.

### Stoping Youtube Video Sharing

1. Join a meeting.

2. Presenter: Click on the action ("+" icon) button.

3. Presenter: Select "Share an external video".

4. Presenter: The popup modal should appear. Paste a YouTube link there.

5. Presenter: Click "Share a new video".

6. All clients will see the YouTube video playing in the presentation area.

7. Presenter: Click on the action ("+" icon) button.

8. Presenter: Select "Stop sharing external video".

9. All clients will see the video disappear and the presentation visible again.

### Playing another Video

1. Join a meeting.

2. Presenter: Click on the action ("+" icon) button.

3. Presenter: Select "Share an external video".

4. Presenter: The popup modal should appear. Paste a YouTube link there.

5. Presenter: Click "Share a new video".

6. All clients will see the YouTube video playing in the presentation area.

7. Presenter: Click on the action ("+" icon) button.

8. Presenter: Select "Stop sharing external video".

9. Presenter: Click on the action ("+" icon) button.

10. Presenter: Select "Share an external video".

11. Presenter: The popup modal should appear. Paste a new YouTube link there.

12. Presenter: Click "Share a new video".

13. All clients will see the new YouTube video playing in the presentation area.

## Shared Notes

### Using shared notes panel

1. Join a meeting with two or more users.

2. Click "Shared Notes" on the left-hand panel.

3. Start writing in the opened shared notes panel.

4. Notification should appear on the "Shared Notes" button for those users whose shared notes panel is closed.

4. After opening the shared notes panel, all clients should see the writing as well. The username will appear near the test that user is currently typing.

### Exporting Shared notes

1. Selecting "export"

2. Choosing available format, should work with all the formats.

3. Save as to local device

Share notes should export and download in the chosen format.

### Using shared notes formatting tools

1. Join a meeting with two or more users.

2. Click "Shared Notes" on the left-hand panel.

3. Use the available formatting tool (Bold, Italic, etc.).

4. Make a bulleted list.

5. Make a numbered list.

6. After opening the shared notes panel, all clients should see the text according to the formatting.

## Lock Settings

### Webcam

1. As a moderator, click on the manage users list cog

2. Click on ON/OFF Webcam

3. As a Viewer, try to click or enable Webcam(turn ON) and Viewers whose Webcams are ON, automatically turns OFF for all Viewers.

- Once Webcam Lock is turned ON, none of the Viewers is able to turn ON their Webcams and all the Viewers Webcams already turned ON should all turn OFF.

4. As a new Viewer joins, he shouldn't be able to turn
   ON his Webcam

- All the newly joining Viewers should get affected with the Webcam Lock Setting

5. As a moderator, try to turn ON/OFF their Webcams.

- Moderator should be able to turn ON/OFF their webcams.

6. Checking if a demoted Moderator, should not be able to turn
   ON his Webcam, and if already with Webcam turned ON, it should automatically turn OFF.

Note : All the newly joining Moderators should be freely able to turn ON/OFF their Webcams

### See other viewers webcams

1.  Click on the user list cog

2.  click ON/OFF Webcam as a Moderator and as a Viewer

3.  check if a Viewer can see other Viewers Webcams

4.  check if a Viewer can see Moderators Webcams

5.  check if a demoted Moderator Webcam is visible to other Viewers and if he can see other Viewers Webcams

6.  check if a promoted Viewer is now able to see other Viewers Webcams

- Once See other Viewers Webcams is turned ON, none of the Viewers can see other Viewers Webcams

- All the promoted Viewers can see the other Viewers Webcams

- All the demoted Viewers aren't able to see the other Viewers Webcams

- All the newly joining Moderators should be freely able to see other Viewers Webcams

- All the newly joining Viewers should be unable to see other Viewers Webcams.

### Microphone

1. Click on the user list cog

2. Click ON/OFF Webcam as a Moderator and as a Viewer

3. Check if a Viewer can join the audio conferance with
   Microphone or not

4. Check if a Viewer can click to join conferance with
   Microphone or not

5. Check if a demoted Moderator is affected with the Lock of
   the use of the Microphone or not

6. Check if a promoted Viewer is affected with the Lock of
   the use of the Microphone or not.

- Once Microphone Lock is enabled, none of the Viewers can use his Microphone

- All the promoted Viewers can unmute their Microphones

- All the demoted Moderators can't unmute their Microphones

- All the newly joining Moderators should be freely able to mute/unmute their Microphones

- All the newly joining Viewers should be unable to unmute their Microphones.

### Public chat

1. Click on the user list cog

2. Click on Public Chat Tab as a Moderator and as a Viewer

3. Check if a Viewer can write a message in the Public Chat
   box

4. Check if a Viewer can click the Send Message Button

5. Check if a demoted Moderator can send a message in
   Public Chat

6. Check if a promoted Viewer can send a message in Public
   Chat

- Once Public Chat Lock is enabled, none of the Viewers can send a Public Chat
  message

- All the promoted Viewers can send a Public Chat messages

- All the demoted Moderators can't send a Public Chat message

- All the newly joining Moderators should freely be able to send messages in Public Chat

- All the newly joining Viewers should be unable to send Public Chat messages

### Private chat

1. Click on the user list cog

2. Click on a Viewer to Private Chat him

3. Check if a Viewer can send a Private Chat message to
   another Viewer

4. check if on Viewer's click on another Viewer, there will be
   Start Private Chat button displaying or not

5. Check if a demoted Moderator can send Private Chat
   message or not to another Viewer

6. Check if an already open Private Chat Tab with another
   Viewer is still open or not

7. Check if a promoted Viewer is now able to send
   Private Chat message or not

- Once Private Chat Lock is enabled, none of the Viewers can send Private Chat messages to others Viewers anymore

- All the promoted Viewer can send a Private Chat messages to the Viewers

- All the demoted Moderators can not send anymore Private Chat messages to the other Viewers

- All the newly joining Moderators should freely be able to send messages in Private Chat to the Viewers

- All the newly joining Viewers should be unable to send Private Chat messages to the other Viewers

- On a Viewer click on another Viewer, he should not be able to see any available user option

- On a Moderator click on a Viewer, he should be able to see the user options

- If there was an existing open private chat tab between 2 users, they should be unavailable to Viewers when the Lock is enabled.

### Shared notes

1. Click on the user list cog

2. Click on a Shared Notes as a Viewer

3. Check if a Viewer can write in Shared Notes

4. Check if on click on Shared Notes a Viewer can Export
   the Shared Notes

5. Check if a demoted Moderator can write in Shared Notes

6. Check if a Viewer is already able to write in Shared Note at Shared Notes Lock, it should reload for him with avoiding him to write in Shared notes or even see the writing tools

7. Check if at a Viewer promotion to Moderator, the Shared Note should reload for him with granting him access to write in Shared Notes.

- Once Shared Notes Lock is enabled, none of the Viewers is able to write or to modify
  text neither

- All the promoted Viewers can write in Shared Notes

- All the demoted Moderators can not write in Shared Notes

- All the newly joining Moderators should freely be able to write in Shared Notes

- All the newly joining Viewers should be unable to write in Shared Notes or to use the writing tools neither.

### See other viewers in the Users list

1. Click on the user list cog

2. Check if a Viewer can see other Viewers in the Users list

3. Check if a Viewer can see Moderators in the Users list

4. Check if a demoted Moderator is able to see other Viewers
   in the Users list

5. Check if a promoted Viewer is now able to see other
   Viewers in the Users list

- Once See other viewers in the Users list is turned ON, none of the Viewers can see
  other Viewers in Users list

- All the promoted Viewers can see the other Viewers in the Users list

- All the demoted Viewers aren't able to see the other Viewers in the Users list

- All the newly joining Moderators should be freely able to see other Viewers in the Users list

- All the newly joining Viewers should be unable to see other Viewers in the Users list

### Unlock a specific user

1. Click on the user list cog

2. Block some feature

3. Go back to users list

4. Click in a user and select unlock user

- You can completely unlock a specific student and let the others locked yet

- The unlocked user must have all features unlocked and other users must keep locked

## Chat (Public/Private)

### Public message

1. Click on Public Chat Tab

2. Type a message in the text box

3. Press Enter key or click the send button

A message should be sent to the public channel and can be seen by any type of user.

### Private message

1. Click on any available user

2. Click on Start a Private Chat

3. Type a message in private chat text box

4. Press enter or click on send button.

A private message will be sent to the user we chose from the online users, and its been sent in a new message tab with the name of the selected user.

### Chat Character Limit

1. Click on public chat tab

2. Enter max number of characters (max message length is 5000 per single message)

A Warning message should appear to inform user message is over max limit.

### Sending Empty chat message

1. Click on public chat tab

2. Hit enter or select send

3. Type in public chat and erase

4. Press enter or select send button.

Message will not be send and a warning message will be displayed "The message is 1 characters(s) too short"

Note :

- As a Presenter/Moderator(feature):
  "Save Chat/Clear Chat/Copy Chat
  (if Private Chat) += Close Private Chat Tab"

- As a Viewer(feature):
  "Save Chat/Copy Chat
  (if Private Chat) += Close Private Chat Tab"

## Polling

### Starting a Polling

(Presenter feature)

1. As a presenter, click on the presenter menu (+) button in the bottom left corner of the screen

2. click Start Poll

3. Choose one of the Poll options

4. wait for Poll votes by the users.

5. Click on Publish Poll Results

- A Poll will show up for all of the available
  users except the Presenter
- A sound effect notification is heard to notify all of the available Viewers/Moderators that there is a Live Poll and the options to vote
  on it are available.
- A live Poll Results Tab will show up to the presenter.

### Sending Poll votes

(Moderator/viewer feature)

1. As a viewer/user, Click one of the available Poll options
   from the Poll Options Card showing in the Bottom Left corner of the Presentation.

- After hearing the Notification sound effect, Poll Vote Options are shown in the bottom right corner of the screen.

### Publishing Poll Results

(Presenter feature)

1. As a presenter, wait for the submissions of the Poll votes

2. click on Publish polling results.

- Poll Results displays in the live results table will show in the presentation to all of the available Viewers/Moderators in the bottom right corner of the presentation.

### Custom Poll

(Presenter feature)

1. Click on the highlighting (+) button in the bottom left corner of the screen

2. click Start Poll

3. select Custom Poll

4. Fill the desired Poll options which is less than 5 options

5. Click Start custom poll

- A Poll shows up for all of the available users except for the Presenter
- A sound effect notification is heard to notify all of the available Viewers/Moderators that there is a Live Poll and the options to vote
  on it are available
- A live Poll Results Tab will show up to the presenter.

### Loading Poll from files

(Presenter feature)

1. Click on the highlighting (+) button in the bottom left corner of the presentation screen

2. Click upload a Presentation

3. Load your Quick Poll file

4. Click upload

- The custom Quick Poll file uploaded is displaying in the Presentation screen
- A Quick Poll button is highlighting in the bottom left corner of the Presentation screen.

### Quick Poll Option

(Presenter feature : Choosing Quick Poll Options from the current Slide which is loaded from the Quick Poll file)

1. Click on the highlighting (+) button in the bottom left corner of the presentation screen

2. Click upload a Presentation

3. Load your Quick Poll file

4. Click upload

5. Click on the Quick Poll button highlighting in the bottom left corner of the screen next to the (+) button

6. click one of the available quick poll options available in the current presentation screen

- The chosen Poll options shows in the bottom right corner of the screen for all the users except the Presenter.

### Hiding Poll Results

(Presenter feature :Hiding Poll Results from the screen.)

1. Click on the Trash icon.

- The Poll result will disappear from the screen.

## User list settings

### Set status

(Viewer: Set Status/Raise hand)

1. As a viewer, select your user icon from user list

2. From menu options choose set status

3. Set a status/raise hand.

- Icon in the users list will update to display emoticon chosen by the user, when status is set by a user the moderator will see their user icon move to the top of the list.

### Clear status

(Moderator: Clear all status icon)

1. Select manage users icon (cog wheel in users list)

2. choose clear all status icons.

- All status icons in the users list will clear.

### Mute users

(Moderator: Mute all Users)

1. Select manage users icon (cog wheel in users list)

2. In lock viewers, select share microphone is locked.

3. Click apply.

- All users (moderator/presenter included) who are already joined in the client with a functioning mic will be muted (if unmuted) and unable to unmute their mics. All users (moderator/presenter included) who join after setting is applied will be automatically joined listen only with no mic options available.

### Unmute users

(Moderator: Undo mute all users)

1. Select manage users icon (cog wheel in users list)

2. In lock viewers, click share microphone to unlock in the status and click apply.

- All users will remain muted until they unmute themselves. All users who enter after the meeting mute is removed will have the option to join with a mic

### Mute and unmute users except Presenter

(Moderator: Mute all users except for presenter)

1. Select manage users icon (cog wheel in users list)

2. Choose lock viewers and select shared microphone to locked, mute all users except for presenter.

- All users except the current presenter who are already joined in the cliend with a functioning mic will be muted (if unmuted) and unable to unmute their mics. All users who join after the setting is applied will be automatically joined listen only with no mic options available.

(Moderator: Undo mute all users except for presenter)

1. Select manage users icon (cog wheel in users list)

2. Choose lock viewers and selecting shared microphone is unlocked and undo meeting mute.

- All users will remain muted until they unmute themselves. All users who enter after the meeting mute is removed will have the option to join with a mic

### Saving Usernames

(Moderator: Save user names)

1. Select manage users icon (cog wheel in users list)

2. Choose save user names.

- Users list names will download as a TXT based document to local device.

### Shared Notes

As a moderator:

1. Select manage users icon (cog wheel in users list)

2. Choose lock viewers

3. Lock shared notes

4. exit menu

As a viewer:

1. Open shared notes panel

2. Attempt to contribute to shared notes to confirm if it's locked.

## Options menu

### Access Options Menu

1. Clicking on Option Menu in top right (three dots)

- A dropdown list appears with a list of
  available commands.

### Make Full screen

1. Click on Make Full-screen in the Options Menu

- The Presentation goes in Full Screen Mode

### Settings

1. Click on Settings in the Options Menu

- Settings screen appears with serval options.

### Application Settings

#### A. Animations

1.  click on the [On/Off] the switch button
2.  Enable/Disable Animations
3.  click Save to Validate your new Settings

- The Animations is now Disabled/Enabled

#### B. Audio Alerts for Chat

1.  Click on the [On/Off] the switch button to Enable/Disable Audio Alerts for Chat

2.  Click Save to Validate your new Settings.

- The beeps alerts for chat are now Disabled/Enabled

#### C. Popup Alerts for Chat

1.  click on the [On/Off] the switch button to Enable/Disable Popup alerts for Chat

2.  click Save to Validate your new Settings.

- The Popup Alerts for Chat are now Disabled/Enabled.

#### D. Application Language

1.  click on the Application Language Options List

2.  choose a language from the dropdown list

3.  click Save to Validate your new Settings

- The screen quickly reloads to apply the language change action

#### E. Font Size

1.  click on (+) or (-) buttons to increase or decrease the font size of Presentation

2.  click Save to Validate your new Settings

- The font size increases/decreases according to the set percentage

### Data Savings Settings

#### A. Enable/Disable Webcams

1.  click on the [On/Off] the switch button to Enable/Disable Webcams

2.  click Save to Validate your new Settings

- The Webcams are now Disabled/Enabled

#### B. Enable/Disable Desktop Sharing

1.  click on the [On/Off] the switch button to Enable/Disable Desktop Sharing

2.  click Save to Validate your new Settings.

- Desktop Sharing is Disabled/Enabled

### Shortcut keys

#### Keyboard Shortcuts

1. click on the Keyboard Shortcuts in the options menu.

2. Press the below keys to get the desired results.

- Alt + O ------> Open Options
- Alt + U ------> Toggle UserList
- Alt + M ------> Mute / Unmute
- Alt + J ------> Join audio
- Alt + L ------> Leave audio
- Alt + P ------> Toggle Public Chat (User list must be open)
- Alt + H ------> Hide private chat
- Alt + G ------> Close private chat
- Alt + R ------> Toggle Raise Hand
- Alt + A ------> Open actions menu
- Alt + K ------> Open debug window
- Spacebar ------> Activate Pan tool (Presenter)
- Enter ------> Toggle Full-screen (Presenter)
- Right Arrow ------> Next slide (Presenter)
- Left Arrow ------> Previous slide (Presenter)

### Log out

1.  Click on Options Menu in top right (three dots)

2.  Select log out.

- User who selects log out is only user who is disconnected from the meeting and a feedback should prompt to the user

#### (For Moderator) : End meeting on log out

1. Click on Options Menu in top right (three dots)

2. Select end meeting and choose yes.

   - All users kicked from meeting, meeting feedback form appears and meeting ends

## Guest Management

## Custom Parameters

## iFrame