# Main Feature Tables

## `users`
Column Name | Data Type | Details
------|-------|---------------------
`id` | int | primary key, not null
username | string | not null, unique
email | string | not null, unique
password | string | not null
created_at | datetime | not null
updated_at | datetime | not null

## `cocktailQs`
Column Name | Data Type | Details
------|-------|---------------------
`id` | int | primary key, not null
question | text | not null
votes | int | 
userId | int | not null, foreign key 
*tagId | int | foreign key
created_at | datetime | not null
updated_at | datetime | not null

* `userId` references `users` table
* *`tagId` references `tags` table

## `cocktailAs`
Column Name | Data Type | Details
------|-------|---------------------
id | int | primary key, not null
answer | text | not null
votes | int | 
userId | int | not null, foreign key
cocktailQId | int | not null, foreign key
created_at | datetime | not null
updated_at | datetime | not null 

* `userId` references `users` table
* cocktailQId references `cocktailQs` table

*`tagsId` references a bonus table

***

# Bonus Feature Tables

## `tags`
Column Name | Data Type | Details
------|-------|---------------------
`id` | int | primary key, not null
type | string | not null, unique

## `comments`
Column Name | Data Type | Details
------|-------|---------------------
id | int | primary key, not null
comment | text | not null
votes | int | 
userId | int | not null, foreign key
cocktailQId | int | not null, foreign key
cocktailAId | int | not null, foreign key
created_at | datetime | not null
updated_at | datetime | not null 

* `userId` references `users` table
* `cocktailQId` references `cocktailQs` table
* `cocktailAId` references `cocktailAs` table




 