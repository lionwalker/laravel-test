# Requirements

### Create database structure to hold Todo Work and User data

- Todo work has properties: description
- User has a property: name
- One user can have multiple todo Works
- Todo Work is belong to a one User

### Seed data to the database

- Create 3 users: set name [ User 1, User 2, User 3 ]
- First user have no pending Works to do
- Second user have 3 Works to do: description can be random texts
- Third user have 2 Works to do: set description [ First work, Second work ]

### Show User and Todo Works in the UI

- List all Users in the UI
- Work should appear under each user
- User should be ordered based on its work count on descending order (most Work pending User comes
  first)

### Search User

- Can be search user by its name and work description ( case insensitive )
    - List all the Users which contains the search text in the work description or in user name
    - Should keep the order
