************************************************* SWIRL HAND COUNTING APP README ***************************************************

This is a single-file web app that allows for smoother hand counting of swirl meters and digital output of data. The concept is simply a clicker and a timer, with some added functionality and data processing specifically for swirl. With creativity, it can be repurposed to count any series of events in the lab. The web app can be accessed from the URL https://fmoran-vdts.github.io/swirl-handcounter/ on mobile or browser, or you can download the most recent version to a laptop/desktop and run it locally in-browser without an internet connection. Mobile browsers cannot run HTML or JS locally, as a general rule.

DIRECTIONS FOR USE 
1. Go to the URL https://fmoran-vdts.github.io/swirl-handcounter/ or download and open the HTML file.
2. Enter the project name and a unique test identifier. As a best practice the test identifer should include at a minimum the test phase, test number, and pump number.
3. Enter the event type (type of swirl meter rotations) you are counting (e.g. half-turns). This sets the numeric weight for each event (0.5 for half turns, 1 for full turns, etc.). This allows for convenient calculation of turns per second and stats like 30-second maximum and 10-minute average to compare to your swirl pass/fail threshold, but the total number of events recorded is always preserved in the logged data. You can completely ignore the numeric weight and just use the number of events if you'd like.
4. Verify the time of each interval and number of intervals are set correctly. Default values are 10 second intervals and 61 total intervals.
5. Turn up device volume if desired. Mobile will require silent mode to be off.
6. Click "Start." The app will count down one interval to allow you to get ready to count.
7. Once the warmup interval is done, you will hear a beep and you can start recording events. Click the button or hit spacebar to record an event. Hit "Pause" to temporarily pause intervals.
8. The app will automatically stop logging when the desired total number of intervals is reached.
9. The table has a full log of intervals and their stats. Relevant stats like long-term average and 30-second maximum are calculated on the page for convenience. The data is best saved by exporting to CSV.
10. Hit "Reset" and start again with the next pump or test.
