# Ticket Model

Name         | Type         | Description
------------ | ------------ | -------------------------------------------------
ID           | int          | PK, AI, Unique
title        | varchar(250) | Ticket title
body         | text         | Ticket body
category     | varchar      | `::` delineated list of categories/sub-categories
resolution   | varchar      | Resolution text
submitter    |              |
owner        | int          | FK - User id
contributors | varchar      | Comma separated list of user IDs
followers    | varchar      | Comma separated list of email addresses
created      | date         | Created date
due          | date         | Due date
modified     | date         | Last modified date
queue        | int          | FK - Queue id that ticket belongs in
status       | varchar      | Ticket status
importance   | varchar      | Ticket importance
priority     | varchar      | Ticket priority
impact       | varchar      | Ticket impact
waiting_on   | int          | FK - Ticket id
related      | varchar      | Comma separated list of ticket IDs
external_ref | varchar      | Reference to an ID on another system
attachments  | varchar      | Comma separated list of file attachments
