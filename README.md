# PROJECT WORKING 🟢

# Cloudflare Worker M3U Playlist

A Cloudflare Worker to serve an M3U playlist dynamically.

## Description

This Cloudflare Worker fetches JSON data from a specified URL, converts it into an M3U playlist format, and serves it to the user. The playlist is updated every 12 hours.

## Features

- Dynamically generates an M3U playlist from JSON data.
- Updates the playlist every 12 hours.
- Serves the playlist with the correct MIME type.
- user can use both .m3u file and link
- https://your-worker-name.your-subdomain.workers.dev/Playlist/(filename).m3u
- file name by default " yutv "
- link working in ns player

# Deployment

## STEP 1
![jcfjfg](https://github.com/user-attachments/assets/1acd8602-60af-404d-8b60-b2389a14951b)


## STEP 2
create worker > give name > direct deploy
![gdsg](https://github.com/user-attachments/assets/7cb5aa4f-ac74-4c93-a236-446bffbc954f)


## STEP 3
![ddd](https://github.com/user-attachments/assets/fca37b9b-323b-42f3-ac4e-fb345da2c9b8)


## STEP 4
replace the defaualt code and change the file name in code (simple alphabet) > deploy 
![yutyu](https://github.com/user-attachments/assets/a24a1c9e-3239-4059-b845-dd2cac1491a3)






