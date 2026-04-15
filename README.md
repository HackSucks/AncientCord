# What is AncientCord?
A custom discord client created in an IDE called Sketchware Pro compatible with Android 2.3 (API level 9) and up.

# How?

Well, youll need your own Discord token. find it using one of many guides, and then head on over to https://pythoncord.pythonanywhere.com. (i recycled the users system from another ongoing project.) Then enter a username of your choice and the token, which don't worry! will be securely stored *and* encrypted.
Once done, go to the releases tab, download the latest .apk and open it. enter the username you used, wait a bit, and watch as it loads.

# How does it work?

Obviously i didnt embed discord. rather i made a Flask server eith API endpoints and JSON responses that the app communicates with.

# Things added in 2.0
1. DM support
2. image caching on device
3. overhauled and revamped UI
4. real bio's pulled from discord
3.5. UI looks more like discord
5. more functionality
6. and server now directly communicates with discord instead of using the discum python package.
