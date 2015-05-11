# email_report
Automated Email Report

This email report allows you to automatically send a very simple storage report email to the email addresses of your choosing.  You'll need to replace the details within it to the details of your SMTP server etc and you'll also need something like Cron to automated it for the times and dates that you want.

The Path variable will need to also be inputted so that Cron can properly read it adn is not trying to run it from another default directory.  From here it will count all the file types you specify within all of the subdirectories of your initial Path.

