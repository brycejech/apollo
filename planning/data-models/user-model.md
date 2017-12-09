# User Model

Name          | Type    | Description
------------- | ------- | -------------------------
ID            | int     | PK, AI, Unique
name          | varchar | Display name of user
email         | varchar | Used for login
password      | varchar | Hashed user password
cell_phone    | varchar | User cell number
work_phone    | varcahr | User work number
rolls         | varchar | Users rolls
default_queue | int     | FK - Queue ID
enabled       | int     | Flag for enabled/disabled
created       | date    | Created date
modified      | date    | Last modified date
