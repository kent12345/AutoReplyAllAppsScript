A simple Google Apps Script to auto ReplyAll in Gmail based on the email address that it is sent to. For example, if your email address 
is foo@example.com, you can have an auto ReplyAll sent if the the to: address is foo+junk@example.com. 

You need to set a trigger to run periodically to scan your inbox for new, unread messages. Once the ReplyAll is sent, the thread will be starred and marked
as read.
