
# Feel free to check my THM profile. https://tryhackme.com/p/pycasian


It's only appropriate to start this room by mentioning the man who invented the concept of emails and made the @ symbol famous. The person responsible for the contribution to the way we communicate was Ray Tomlinson. 

The invention of the email dates back to the 1970s for ARPANET. Yep, probably before you were born. Definitely, before I was born. :)

So, what makes up an email address?

User Mailbox (or Username)
@
Domain
Let's look at the following email address, billy@johndoe.com.

The user mailbox is billy
@ (thanks Ray)
The domain is johndoe.com
To simplify this even further, think about the street on which you live on.

You can think of your street as the domain. 
The recipient's first/last name, along with the house number in this scenario, represents the user mailbox. 
With this information, the postal worker delivering the mail knows into which mailbox to put the letter(s). 

Next, let's look at the network protocols used to send an email from the sender to the recipient.

# Answer the questions below
# Email dates back to what time frame?
1970s

# What port is classified as Secure Transport for SMTP?

465

# What port is classified as Secure Transport for IMAP?

993

# What port is classified as Secure Transport for POP3?

995

# What email header is the same as “Reply-to”?

Return-Path

# Once you find the email sender’s IP address, where can you retrieve more information about the IP?

http://arin.net

# In the above screenshots, what is the URI of the blocked image? 

https://i.imgur.com/LSWOtDI.png

# In the above screenshots, what is the name of the PDF attachment?

Payment-updateid.pdf

# In the attached virtual machine, view the information in email2.txt and reconstruct the PDF using the base64 data. What is the text within the PDF?

We're gonna open the txt file and remove everything that is'nt base64

We're gonna copy all the base64 to clipboard and paste it in https://base64.guru/converter/decode/pdf then convert to get the flag


# Types of phishing

# What trusted entity is this email masquerading as?

Home Depot


We will decode the above text after removing the ?UTF-8?B? and ?= from beginning and end


# What is the sender’s email?

support@teckbe.com

# What is the subject line?

Order Placed : Your Order ID OD2321657089291 Placed Successfully

# Decrypt the Highlighted text as before

# What is the URL link for — CLICK HERE? (Enter the defanged URL)

hxxp[://]t[.]teckbe[.]com/p/?j3=EOowFcEwFHl6EOAyFcoUFV=TVEchwFHlUFOo6lVTTDcATE7oUE7AUET==

# What is BEC

Business Email Compromise

