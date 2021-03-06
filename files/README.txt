README: BETTR

Prototype Link: https://marvelapp.com/26f12fh/screen/34264464

HOW TO USE: 

For this medium-fi design, we used Marvel to prototype. The prototype consists of an iPhone screen, as well as clickable and swipeable features to emulate a user's finger with the mouse. Scroll functionality is also enabled on a few screens, which can be accessed with the scroll bar to the right side of the screen. 

The clickable areas are highlighted if the user clicks on a portion of the screen that is not swipeable.

FLOWS TO TRY:

1. Log in with your Facebook account. 
2. Press the plus button in the top right corner, and go through the discover bets flow. 
3. Press the plus button in the top right corner, and go through the add a new bet flow. 
4. In the main feed homepage, support your friend's bets by clicking the support button (shoutout icon) and commenting. Click into the bet to view the bet timeline, and click on parts of the timeline to see details of that time.
5. In the main feed homepage, select a bet to check into at the top of a page. 
6. Toggle to the analytics page using the bottom bar.
7. Toggle to the my bets page using the bottom bar. 


WIZARD OF OZ TECHNIQUES & HARD-CODED FEATURES:

We hardcode a user and simulate them logging in with their Facebook account. Then, we initialized the platform with mock bets, mock friends, mock photos, and mock notifications. Wizard of oz techniques include "magic" analytics for the user, such as a progress graph and description of key strengths, as well as auto-syncing of Facebook friends who are on the Bettr platform. 

LIMITATIONS: 

1. The users are guided through a single flow for most tasks, to test the key flows and reduce the amount of overhead involved with supporting every different option. 

2. Selection and typing functionalities are abstracted away, such as when selecting a photo and inputting bet times & details. This unfortunately makes it difficult to gauge user satisfaction with the amount of typing, which is key for mobile interfaces 

3. Due to the nature of Marvel (especially the highlight-next-actions-on-click feature), it is difficult for us to test the discoverability of these features. 

4. Some advanced functionalities are disabled for the sake of simplicity, such as clicking on key points in "My Overall Growth" chart. 

5. Adding a bet does not cause the bet to actually appear in the feed. 




