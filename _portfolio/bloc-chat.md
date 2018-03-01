---
layout: post
title: BlocChat
thumbnail-path:
short-description: BlocChat is an application that sends and receives messages in real time.
---

{:.center}
![]({{ site.base_url }}/img/blocflix.png )


## Explanation

BlocChat is an application that was created to act as chat room. The end result of this application is to have it send and receive messages in real time.

## Problem

The goal of this project was to have a chat room work in real time.

## Solution

This project injected Firebase, which is an application development platform, as a module into this Angular based application. With BlocChat I learned how to also use cookies to store information in a web browser. With Firebase I was even taught new methods such as `orderByChild` . This generates a new Query object ordered by the child key that is specified. Two controllers were created for this application `HomeCtrl` and `ModalCtrl`. Within these controllers I injected three separate services `Room`, `Message` and `BlocChatCookies` which created new chat rooms and sent messages in real time associated with a specified username. 


## Results

Create new chatrooms and different usernames
Switch between chatrooms
Send messages in real time with a timestamp within the chatroom


## Conclusion

This project involved both Angular and Firebase to create a chatroom which worked in real time. I learned how to use cookies within my applications to store information within a web browser for later use.
