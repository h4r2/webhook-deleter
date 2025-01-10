# webhook-deleter

A simple Vue-based web application that simplifies the process of deleting Discord webhooks.

## Purpose

- You can prevent unknown @everyone webhook spams
- Most scams on discord get your information by sending some form of malicious media to the victim, grabbing the information from the webpage, and finally sending the victim's data via a webhook. You can obtain that webhook URL by going on your Developer Tools (record the Network requests), copy the webhook URL and you can delete it from here.

To the admin looking at the audit logs of the server that the webhook belongs to, it will look like this:
![unknown-user-deleted-webhook](https://imgur.com/SDiMb7H)

## Built with

- Vue 3 + Vite
- Vanilla CSS
