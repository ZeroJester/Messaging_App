# Production
A messaging application that allows users to communicate over the Internet when signed in.

## The Challenge I Faced:

One of the main issues I encountered while developing this app was ensuring that it could be fully mobile and independent. The goal was for users to simply download the app, run the client.exe file, and sign in without needing any additional downloads or installations.

## How I Solved It:

Initially, I attempted to host the server.exe file on my local computer and set up port forwarding on my router to make my computer accessible on the internet. Unfortunately, this approach failed because my ISP did not allow for port forwarding.

After hours of trial and error, I found a solution in online hosting services like ngrok. These services allow you to host scripts remotely, bypassing the limitations of my local network. I hosted the server.exe file on ngrok's platform, and this successfully solved my problem.
