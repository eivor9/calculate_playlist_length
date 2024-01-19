Youtube music's playlist duration counter stops at 8 hours (outputs 8+ hours),
so this will log to your console the accurate duration of your playlist.

Steps:
1. Navigate to your playlist on youtube music via your web browser
2. Now you want to scroll down to the bottom of the page to make sure all songs are loaded onto screen.
3. Right click a blank space between Suggestions and the side bar, near the bottom of the page and click "Inspect element"
    (if you're safari on mac this option shows after enabling "Show features for web developers" from  the Advanced tab of Safari settings (CMD + ,)
4. Expand highlighted tab (should be <div id="contents" class="style-scope ytmusic-section-list-renderer">...</div> )
5. After expandidng, highlight the line immediately undernearth it by clicking it.
6. after it's highlighted right click and press Copy > HTML.
7. From here you can copy this in between the backticks (slanted single quotes) of const SONG.
8. Run and enjoy the info!


Happy Listening
