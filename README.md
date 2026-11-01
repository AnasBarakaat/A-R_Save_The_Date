# Anas & Reem — Save the Date

A build-free page for 12 December 2026. Upload `index.html`, `save-the-date.mp4`, and `anas-and-reem.ics` together to your GitHub Pages publishing folder. If placed at the repository root, visit the site's root URL; if kept in this subfolder, visit `/save-the-date/`.

The video attempts autoplay with sound at full player volume inline, without visible video controls. If browser autoplay policy blocks sound, a “Tap to play with sound” button starts it with a user gesture. Websites cannot override browser autoplay rules or the device volume setting. Each ending holds the final frame for 10 seconds while the pill fades in. The pill then fades out over 650 milliseconds before playback restarts. Reduced-motion preferences shorten the fades. The video covers the entire viewport, cropping its edges as needed for the screen aspect ratio. The calendar pill is centered over the video.

The calendar event is all-day, since the video specifies a date but no time or venue. Its end date is exclusive. To change the date, update the ICS file and both calendar URLs' parameters in the HTML.

The main button opens a standard ICS invitation. The operating system/browser controls preview, download, import, or app choice; websites cannot force a native calendar chooser or silently save an event. Apple/Samsung/Outlook support depends on installed handlers and browser behavior. Google and Outlook web links appear after tapping the pill as fallbacks. Guests must confirm saving in their calendar. Test the deployed HTTPS page on your intended phones before sharing.

The original video is approximately 34 MB. Upload it using Git rather than GitHub's browser uploader if its file-size limit prevents uploading. There are no external libraries, fonts, analytics, or build steps.
