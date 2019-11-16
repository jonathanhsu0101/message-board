# Message Board

https://newby.now.sh/

# Screenshot

https://github.com/jonathanhsu0101/message-board/blob/master/message%20board%20screenshot.PNG

# What is it:

It is a message board. You can leave a message with picture to share with other people.

The App is deployed on Heroku.

It is based on Vue, with both front end interface and back end database. Front end uses Bootstrap framework and Bootswatch themes. Back end uses MongoDB Atlas.

# Index

* [x] Create Server Folder
  * [x] Init npm
  * [x] Add express morgan cors body-parser
  * [x] Create Hello World Route
* [x] Create Client Folder
  * [x] vue create client
  * [x] Add bootswatch CSS
  * [x] Homepage Layout
* [x] Add DB to server
  * [x] Add monk joi
  * [x] Create message model
  * [x] Create rout to add message to DB
    * [x] validate message with joi
      * username - default to anonymous
      * subject
      * message
      * imageURL
      * created_at
    * [x] insert message into DB
    * [x] respond with inserted message
* [x] When page loads show all messages on page
  * [x] Server route to GET all messages
* [x] Create new message form on client
  * [x] Submit form - fetch POST to server
  * [x] Show any errors
  * [x] Show new message on page
* [x] Deploy!
