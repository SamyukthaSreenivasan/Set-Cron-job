
### EX NO 5

### AIM:

The aim is to set up a cron job for the user 'harry' to run /bin/echo "hello" at 12:30 PM daily.

### PROCEDURE:

1. Edit User's Cron Table.

2. Add Cron Job Entry.

3. The entry specifies that the command /bin/echo "hello" will run at 12:30 PM every day.

4. Save the changes and exit.

### PROGRAM / COMMANDS:

```
Developed by: Samyuktha S
Register Number: 212222240089
```
```
crontab -u harry -e

30 12 * * * /bin/echo "hello"

```
The cron job for user 'harry' is set to run /bin/echo "hello" at 12:30 PM daily and the job will execute the command and print "hello" to the standard output at the specified time.

### OUTPUT:

![image](https://github.com/SamyukthaSreenivasan/Set-Cron-job/assets/119475703/15f4cdc9-014e-4bcd-9fcc-2677f01f6c20)

### RESULT:

Thus the program to set up the cron job for the user is successfully implemented.
