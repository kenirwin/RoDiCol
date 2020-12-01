# RoDiCol
Representations of Diversity in Collections

## Outline plan

* API driven -- all functions handled by API
  * how will keys be granted?
* CRUD database structure
  * readable by all
  * searchable by all
  * writeable by partners
* collections / user accounts
  * add to / remove from collection manually
  * batch upload collection for comparison
  * search for books and save them to your own "collection"
  * possibly support multiple collections per users
* connections with authorities
  * oclc / worldcat
  * goodreads
  * library thing
* analysis tools
  * per collection, report stats
* admin tools
  * review API key requests

## Proposed API endpoints
* GET /books - list all/some books
* GET /book  - provide an individual book's details
* PUT /book  - update book details
* POST /book - create new book
* DELETE /book - delete a book (admin only?) 
* POST /collection/add - add a book to a collection
* DELETE /collection/item - remove an item from collection


