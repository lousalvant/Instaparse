# Lab 2 - *Instaparse*

Submitted by: **Lou Salvant - Z23637852**

**Instaparse** is an app that lets users sign up, log in, and create posts by selecting photos, adding captions, and uploading them to a Parse backend. Users can view their posts in a feed, persist their login across sessions, and log out when needed, with all data managed through the Parse Swift SDK.

Time spent: **4** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] Users can sign up to create a new account.
- [x] Users can log in after creating an account.
- [x] Users are able to log out
- [x] Users are able to persist their login credentials on multiple app launches
- [x] Users can create a Post by choosing an existing photo from their photos library and uploading it with a caption to the server.
- [x] Users can view posts they've created in their feed.

## Video Walkthrough

**Added name and Z# afterwards**


![GIF](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZGUwNTF5eHg3N2RxZWJmeWI0OGRleXdlZDlnYzJkNXFwY25sajhsdiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/YaUhs2Zq3AzUE9IBIN/giphy.gif)

**Login Demonstration**


![GIF](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWk4cGFrY3J2NTgzdjU0b2JvdGE5cjhwOTRlNmphMXZpMjI4N2ZhcyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/iUptvGqu7JKtHjOAjP/giphy.gif)

**Signup Demonstration**


![GIF](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExbm9scWZja2s2Z3V1OTRxdmp6YXIwYTl0cmY5bmJnYnl6YWhhdWR3NCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/LSVy2xLNuKaBXstapt/giphy.gif)

**Create Post and Logout Demonstration**


![GIF](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMHd2d2M4dm84cjJra3Fnam42ZDFncDNhZjV2OHR2MGlqaGN0cmw2cyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/vzeqe5uc6YCM5vbTFA/giphy.gif)

**Persisting Login Credentials Demonstration**


![GIF](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWJudGh5NDUzbXpnZjlxNnF1MGFzZ2xjaXc4ODhqczMwcW52NHQ4OSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/s6Swg6FoIQzRud6bLe/giphy.gif)

## Notes

I was encountering a ParseError code=-1 error=Invalid struct: No value associated with key CodingKeys(stringValue: "name", intValue: nil) ("name"). After some research and referring to the slack channel, I used a workaround suggested by Dr. J to change the Parse Version to a previous version. After doing this, the app seems to work as expected.
## License

    Copyright [2024] [Lou Salvant]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
