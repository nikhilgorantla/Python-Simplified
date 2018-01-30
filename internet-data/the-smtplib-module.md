# The smtplib Module

The smtplib module defines an SMTP client session object that can be used to send mail to any Internet machine with an SMTP or ESMTP listener daemon.

```
import smtplib
 
server = "smtp.gmail.com"
port = 587
username = "username"
password = "password"

sender = "me@domain"
recipient = "you@domain"
subject = "Python Email Test"
message = "Hello from Python!"

try:
    smtp = smtplib.SMTP(server, port)
    smtp.starttls()
    smtp.login(username, password)
    smtp.sendmail(sender, recipient, 
        "From: %s\nTo: %s\nSubject: %s\n%s" % (sender, recipient, subject, message))
    smtp.quit()

    print("Sent message.")
except Exception as exception:
    print(exception)
```

Output:

```
Sent message.
```



