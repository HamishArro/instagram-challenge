# README

## Welcome to RetroGram

## Plan

MVP: users can log onto RetroGram and post a picture for other users to see.

### levels:
- Follows
- User
  - Pictures
    - Comments
    - Likes

### Tables
Users:

| ID | email | password | username |
| -- | ----- | -------- | -------- |
| 1 | Hamish@email.com | password | Hamish |
| 2 | Oscar@email.com | password | Oscar |

- No owner.

Follows:

| user_id | following_id (other user_id) |
| --- | -------- |
| 2 | 1 |

- No ID needed.
- No owner.

Pictures:

| ID | user_id | time_added |
| -- | ----------- | ---- |
| 1 | 1 | 26/02/2021 18:00 |

- will use the ID to save the image and find the image.
- Belongs to Users.

Likes:

| picture_id | user_id |
| --- | --- |
| 1 | 2 |

- No ID needed.
- Belongs to pictures.

Comments:

| picture_id | comment | user_id | time_added |
| --- | ---- | ----- | ---- |
| 1 | 'this is a very nice picture' | 2 | 26/02/2021 18:30 |

- Belongs to pictures.
