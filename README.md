# Cloudflare Worker M3U Playlist

A Cloudflare Worker to serve an M3U playlist dynamically.

## Description

This Cloudflare Worker fetches JSON data from a specified URL, converts it into an M3U playlist format, and serves it to the user. The playlist is updated every 12 hours.

## Features

- Dynamically generates an M3U playlist from JSON data.
- Updates the playlist every 12 hours.
- Serves the playlist with the correct MIME type.

