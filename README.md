# Messaging_App
A messaging application that allows users to communicate over the Internet when signed in.

## Problem To Solve?
The main issue I encountered while coding this app, was that the app had to be fully mobile and independent, meaning that after downloading the app, the user should simply run the 'client.exe' file, and then sign in. Extra downloads and installations were not allowed.

### How I Solved It?
At first, I tried hosting the 'server.exe' file on my local computer, and then port forward my router to allow for my computer to be discovered on the Internet. This plan did not work as my ISP did not allow for my router to be port-forwarded. After hours of trial and error, I discovered online hosting services such as ngrok, where they can host your script online. I proceeded to host the 'server.exe' script on their website, and my problem was solved.