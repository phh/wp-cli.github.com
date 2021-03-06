---
layout: default
title: 'wp user import-csv'
---

`wp user import-csv` - Import users from a CSV file.

### OPTIONS

&lt;file&gt;
: The local or remote CSV file of users to import.

[\--send-email]
: Send an email to new users with their account details.

[\--skip-update]
: Don't update users that already exist.

### EXAMPLES

    wp user import-csv /path/to/users.csv
    wp user import-csv http://example.com/users.csv

    Sample users.csv file:

    user_login,user_email,display_name,role
    bobjones,bobjones@domain.com,Bob Jones,contributor
    newuser1,newuser1@domain.com,New User,author
    existinguser,existinguser@domain.com,Existing User,administrator

