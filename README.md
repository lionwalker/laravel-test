# Requirements

### Create database structure to hold Post and Comment data

- Post has a property: description
- Comment has a property: message
- One post can contains multiple comments
- Comment is belong to a one Post

### Seed data to the database

- Create 5 posts: descriptions [ First Post, Second Post, Third Post, Fourth Post, Fifth Post ]
- First Post contains no comments
- Second Post contains 3 comments: message can be random texts
- Third Post contains 2 comments: messages [ First Comment, Second Comment ]
- Fourth Post contains no comments
- Fifth Post contains one comment: message can be random text

### Show Post and Comment in the UI

- List all Posts in the UI
- Comments should appear under each post
- Posts should be ordered based on its Comments count on descending order (most commented post comes
  first)

### Search Posts

- Can be search posts by its description and comment message ( case insensitive )
    - List all the Posts which contains the search text in the description or in any of the comment messages
    - Should keep the order

### UI Sketch

<img width="708" alt="UI Sketch" src="https://user-images.githubusercontent.com/24663408/121665011-b5a83580-cac5-11eb-898f-8688785c7554.png">
