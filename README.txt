SRI LANKA BUS SIMULATOR 3D — PHONE-ONLY STARTER

WHAT THIS IS
A small low-poly 3D browser game prototype. It is NOT yet a native APK and has not been tested on every phone. It loads Three.js from a CDN, so internet is required to load the 3D engine. Touch controls: left/right, accelerate, brake. Landscape is recommended.

FILES
- index.html : game and source code
- manifest.json : PWA metadata
- sw.js : basic service worker cache

EASIEST PHONE-ONLY WAY TO PLAY
1. Upload these files to a static website host using your Android phone. One option is GitHub Pages (create a repository, upload the three files, enable Pages in repository Settings).
2. Open the published HTTPS site in Chrome on Android.
3. Use Chrome menu > Add to Home screen (or Install app, if offered).
4. Turn the phone sideways and play.

HOW TO TRY TO PACKAGE AS APK WITHOUT A PC
1. First publish the site on HTTPS as above.
2. Visit PWABuilder.com in Chrome and enter the published site URL.
3. Follow its Android package workflow and its current requirements. APK/AAB packaging may require signing keys and/or an account/tooling; it is not guaranteed to be a one-tap process.
4. Review permissions and signing details before installing. Do not upload private credentials or signing keys to unknown sites.

IMPORTANT LIMITATIONS
- This is a prototype with a generated road and stylized bus, not a geographically exact Kandy-Colombo map.
- Three.js is loaded from jsDelivr CDN, so the first launch needs internet. A truly offline native APK needs bundling the 3D library and Android packaging/build tooling.
- The game has no real traffic, passenger system, ticketing, missions, licensed bus models, or real-world map data yet.
