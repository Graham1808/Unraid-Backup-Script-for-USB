Hi All

Having tried multiple ways to make an easy backup of the USB I have, (ChatGPT) has created a script that you can run daily, which creates a file for the USB (Excluding the .git files as there are 1000s). It names the file in date order and deletes folders over 7 days.

I did it this way as multiple of the backups were a bit of a mare to read the USB, and this was easier for me than giving root to lots of containers... these containers can just pull the data from the backup file and store elsewhere.

You will need to create a share called "backups" for the script to work.

My cron setup is 01**** to run at 01:00 daily

Any enhancements or thoughts, let me know. This is not my forte
