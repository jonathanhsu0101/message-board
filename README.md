# Full Stack Message Board

https://newby.now.sh/

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