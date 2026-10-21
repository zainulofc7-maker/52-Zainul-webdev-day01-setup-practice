## Chrome DevTools network inspection

- Website: Amazon India (https://www.amazon.in)
- Date inspected: 21 October 2026
- Steps: Opened Chrome DevTools (F12), selected the Network tab, and reloaded the page with Ctrl + R.
- Request types observed: document, fetch, ping, gif, text/plain, images (jpeg, png, avif)
- Example status codes: 200, 204
- Observation:  The Amazon India homepage made about 130 requests and transferred around 1.2 MB. Most of the requests were images (jpeg, png, avif), and many others were small "ping" and "fetch" requests, which seem to be for tracking and analytics. Two requests showed red entries, one failed and one was blocked. Many images were loaded from the disk cache, so the browser did not download them again. The page kept making requests after it appeared, so the total finish time was long (about 57 seconds).
- Evidence: ![Network panel](screenshots/network-panel.png)

most of the request are images 
some of the request get fail
and some of the request are from cashe
