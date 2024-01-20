Youtube music's playlist duration counter stops at 8 hours (outputs 8+ hours),
so this will log to your console the accurate duration of your playlist.

Steps:
1. Navigate to your playlist on youtube music via your web browser
2. Now you want to scroll down to the bottom of the page to make sure all songs are loaded onto screen.
3. Right click a blank space between last song of playlist and the side menu bar (near the bottom of the page) and click "Inspect element"
    (if you're using safari on mac this option becomes available after enabling "Show features for web developers" from  the Advanced tab of Safari Settings/Preferences (CMD + ,)
4. Expand the highlighted tab (should be labeled   <div id="contents" class="style-scope ytmusic-section-list-renderer">...</div>  )
5. After expandidng, highlight the line immediately undernearth it by clicking it once.
6. after it's highlighted right click and press Copy > HTML.
7. From here you can enter you playlist's name in between the quotes of PLAYLIST_NAME on line 1 and finally paste the HTML of your playlist in between the backticks (slanted single quotes) of const SONGS on line 2.
8. Run and enjoy the info!

Happy Listening!
