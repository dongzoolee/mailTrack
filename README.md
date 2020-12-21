# MailTrack
How Can We Track Mail With Gmail?

# 0. Before We Start
Gmail has no mail-tracking function.

Let's make it with our hands.

# 1. How Does Other Trackers Work?
### 1 - insert <img src=> tag into mail with style=
```
width:0;
height:0;
```
### 2 - SET src to a link that checks if someone has accessed to that link.
### 3 - Receiver opens mail and the browser send request to that link.
### 3 - Server concludes that the mail has been opened.
### 4 - Send 'OPENED' alert to the sender.
