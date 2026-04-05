# Project overview

Working on a social app, backend is about done for the most part, going through security and core features right now. I will continue posting updates. 

**March 21, 2026** Done with the security layer today. Rate limiting, token management, input validation, and a few other measures are all in effect, core features are next.


**March 22, 2026** Just finished building the notification system. I ran into a few issues where responses were coming back empty even tho the data was saving properly, I ended up figuring it out. The app now tells you when things happen.

**2nd update for March 22, 2026** Worked on the post favorites system today. Users can now privately save posts, nobody else can see what each user saved, not even the person who created the post. The favorites system was also runing into some issues that had to do with the system misreading a route name as a post ID, that got fixed.


**March 23, 2026** Made the QR code backup system for when NFC fails. If two people tap phones and the NFC doesn’t work they can swipe to a QR code instead. The system checks that both people are within 150 meters of eachother using GPS before allowing the connection to go through. The QR code expires in 60 seconds and can only be scanned once so there  isn’t a way to screenshot it and use it remotely.


**March 24, 2026** Built activity status, users can choose when to have this on or off. Green means active now, yellow means left within 5 minutes, nothing means offline or hidden. Also added automatic warning notifications that appear 48 hours before a private voice note thread expires so users have time to save what matters. Fixed a few field naming inconsistencies that would have caused bugs later on.


**April 4, 2026** Done with the memory map today. Every person you've ever added gets a pin on a private map at the exact spot where you met. The map only appears when you enable location but the coordinates are always captured at the moment of connection so nothing is ever lost. Enable it a year from now and all your pins sync automatically into the memory map. Took a few rounds of fixes to get the permission logic right but everything seems to be working now.
