# Duckymotion

<p align="left">
    <a href="https://discord.gg/rxekqVJ" target="_blank">
        <img src="https://discordapp.com/api/guilds/408718485913468928/widget.png?style=banner3">
    </a>
</p>

## Duckymotion replacement for https://nothing.portal and https://nothing.ctr

# What is this?
This is a recreation of Miiverse but for DuckNetwork.

# Usage

First step, install [NodeJS](https://nodejs.org). Download/clone this repo and run `npm i` to install all dependencies. Edit `example.config.json` to your liking and rename it `config.json`. Run the server via `npm run start`.

## What works
- [ ] Made the Duckymotion UI.
- [ ] Made the API for send messages.
- [ ] Made the API for send image or drawer.
- [ ] Finish the User Menu.
- [ ] Made API for follows communities/users.
- [ ] Made API for views communities.

## Currently implemented endpoints
 * [GET]  /titles/show
 * [GET]  /communities
 * [GET]  /communities/[title ID]/new
 * [POST] /communities/follow
 * [GET]  /users/show?pid=[user ID]
 * [GET]  /users/me
 * [POST] /users/follow
 * [POST] /post/empathy
