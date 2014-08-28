# HTML email template #

A simple responsive HTML email template usable by most of the major email applications (Outlook, Gmail, Ymail, etc..)

![Alt text](https://raw.github.com/kqlambert/HTML_email/master/example.png "Theme View")


## php headers for html email ##

	$headers = "From: " . $email . "\r\nReply-To: ". $email . "\r\nMIME-Version: 1.0\r\nContent-Type: text/html; charset=ISO-8859-1\r\n";