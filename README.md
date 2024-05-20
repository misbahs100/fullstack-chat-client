# Live Site
[Click](https://my-fullstack-chat.netlify.app) here to see the live site. You must have to Sign Up if you want to use it.

# Connect React to Chat Engine!

This simple repo shows how to easily add chat functionality into a React project with [Chat Engine](https://chatengine.io).

To understand the code, please watch [this video]()!

## Setup Steps

Setup this chat client in 3 steps below.

These steps assume you have already setup one of the server projects in `../server-*` (for example, `server-express`).

### 1 - Setup a Chat Engine server

Go to [Chat Engine](https://chatengine.io) to setup your own chat server.

- Click "New Project" and follow the steps
- Your `Project ID` and `Private Key` will be required for step 2

### 2 - Connect `.env` to Chat Engine

We will connect to your Chat Engine server with environment varibles.

This allows you to connect to different chat-servers in local vs staging vs production.

Replace the UUID below with your own. In `.env` write:

```
REACT_APP_CHAT_ENGINE_PROJECT_ID=your_project_id
```


