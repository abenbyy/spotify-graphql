# spotify-graphql
A Graphql Wrapper for Spotify Web API

## Deployed Example on:
https://spotify-graphql.up.railway.app

## Requirements:
- Go 1.15

## How to Create Your own:
- Clone this repository
- Go to [Spotify Developer's Dashboard](https://developer.spotify.com/dashboard/applications) and create a new app
- Create a new .env file using .env.example given
- Fill CLIENT_ID and CLIENT_SECRET with your app's Client ID and Client Secret
- Run ```go run ./server.go```
- Done!

## Available Queries

### Artist
- [x] Search Artist 
- [x] Search Artist Albums

### Album
- [x] Get Album Tracks

### Tracks
- [x] Get Track Content
