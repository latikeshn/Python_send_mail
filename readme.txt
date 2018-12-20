In python_mail directory there are four files
1.mycontacts.txt
2.message.txt
3.mail.py
4.pdf file


1.mycontacts.txt:
	This text file contains the list of the gmail username along with their names.This would help to send bulk messages to the users.

2.message.txt
	This text file include the message to be send as a message-body in mail.
In this file, you'll notice the word “ ${PERSON_NAME} ”. That is a template string in Python. Template strings can easily be replaced with other strings; in this example, ${PERSON_NAME} is going to be replaced with the actual name of the person 
    
3.mail.py
	Our main python executable file.
	Add your username and password to send the mails and also add the attachment file name along with its path to send attachment to a user.

4. It's an attachent file. It could be any file(.doc, .pdf, .txt, .jpeg, etc)