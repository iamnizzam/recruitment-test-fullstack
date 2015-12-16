# recruitment-test-fullstack
Test taken by candidates applying for the post of Fullstack Developer

# The Task
The task is to create a cross platform web-based single-page textual chat client application. It is a simple chat application that utilizes two transports instead of only one. The authentication is not a concern for you right now. Just let the user pick a username that has not already been picked. Registration/Passwords are not needed. You can do them if you fancy but seriously, why? :)

The first trasport is websocket. I suggest you use the `WebSocket` native APIs on client side.

Use the "ws" module (https://github.com/websockets/ws) on server side. This part is extremely straightforward.

The second trasport is the challenging part. It allows for offline communication using the brand new "Service Worker" standards. The idea is that the application should be usable without actually being online. The user can just type in the url for the application and type in their messages as if they were online. (The behaviour is similar to how google docs can be worked on offline.) Read up on service worker here - http://www.html5rocks.com/en/tutorials/service-worker/introduction/

As a bonus, if you can, implement this "Push Notification" option on the reciver. So that the receiver will be notified even if they are not presently browsing the demo website. This feature currently only works on chrome (which is not a problem). Read up here - https://developers.google.com/web/updates/2015/03/push-notifications-on-the-open-web

You will need to write unit tests for your code. Write unit tests using `mocha` and `chai`. The server code should be pure Object Oriented CoffeeScript. On the client, use CoffeeScript for all your scripting. The rest is mostly upto you.

Note that UI is not your concern in this project. But UX (User Experience) is. As long as it is usable and not confusing, you won't be judged by your user interface.

I hope you will find this task challenging and educative at the same time.

### Technologies required
* CoffeeScript (the code you write should be written entirely in CoffeeScript)
* NodeJS (use 4.2.3 LTS)
* mocha
* chai
* neDB (https://github.com/louischatriot/nedb) OR mongoDB

### Technologies NOT allowed
* jQuery
* bootstrap
* any client side framework other than Polymer.

# How to do it?
* Fork this repository to your personal github account.
* Complete the task
* Notify us by email.

# Timelimit
You should ideally complete the task in less than 24 work hours. In no circumstances it should take you more than 48 work hours.

Your individualized deadline will depend on the date you apply on. Usually it's within 7 days from your application.

# Notes
* Make sure to commit around every 5 to 15 minutes while you work. It is extremely important. Make sure your commits messages make sense.
* Sync your commits work every hour.
* Read up references as much as you need. Reading is appreciated.
* You may showcase your work on your portfolio regardless you work with us or not.
* Your enthusiasm and creativity is evaluated on par with your professionalism.
* Contact us if you have any trouble understanding the task.
