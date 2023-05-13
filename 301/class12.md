# Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:
100’s = Informational - says the sever has the request and is countinuing the processing
200’s = Server received, understood, and accepted the users request
300’s = Request moved/redirected to a new location 
400’s = User error - maybe a bad request or something 
500’s = Server error - maybe it crashed or some other kind of internal error
2. What is a status code 202?
  - Server recieved and accepted request but hasn't finished processing it 
3. What is a status code 308?
  - Permanent redirect - requested resouce permanently moved to a new URL 
4. What code would you use if an update didn’t return data to a client?
  - 204 No Content
5. What code would you use if a resource used to exist but no longer does?
  - 410 Gone
6. What is the ‘Forbidden’ status code?
  - 403 Forbidden