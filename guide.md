### Files and folders
I decided to keep track of the files and there locations here.

For now there are 2 jupyter files: 
- **create_db** creates the database yoga.db and all the tables 
- **app** is the main file which runs the app 

In **templates** folder there are 2 html files, here is why: 
- the **base.html** is the main template which stores the navigation bar code
- **register.html** is the child file of base.html, it takes the navbar from there and has the register form 

### Some ideas for the views and joins: 

- **View** //
For the view we can work around with `Members` and `Memberships` tables. In `Members` table we should have only membership id - so the name is not directly visible. We may create a view for this - for one Member display her Membership in `My profile` tab.

- **Join** //
To display bookings in `My profile` tab we need to merge `Members` and `Schedule` tables by there keys in `Reservations`. 