# Python3-SendEmail-with-Attachments
A Python 3 script to send email via your gmail with multiple file attachments

# How to Run
```
python run.py
```

# How to Use
```
from sendEmail import sendEmail

if __name__ == "__main__":
	gmail_username = 'example@gmail.com'
	gmail_password = 'yourpassword'
	emailfrom = gmail_username
	emailto = ['myfriend1@gmail.com','myfriend2@gmail.com']
	filesToSend = ['testFile1.txt', 'testFile2.txt']
	subject = 'Test Files'
	body = 'Here are our test files.\nThank you very much.'
	
	sendEmail(emailfrom, 
			emailto, 
			subject, 
			body, 
			filesToSend, 
			gmail_username, 
			gmail_password)
```
