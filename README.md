# email-with-nodejs
This repo demonstrates how to use various packages to send emails via nodejs

## Usage

Install dependancies

```
git clone git@github.com:ar-to/email-with-nodejs.git
cd email-with-nodejs.git
npm install
```

Create a .env file on root with the follow format

```
MY_GMAIL=mygmail
GMAIL_USER=username
GMAIL_PASS=password
TEMP_EMAIL=from10minutemail.com
```
This file is build using [dotenv module](https://www.npmjs.com/package/dotenv)

Create a .env file on root with the follow format and open a browser tab and got to this [temporary email website](https://10minutemail.com/) and add the email to TEMP_EMAIL

```
MY_GMAIL=mygmail
GMAIL_USER=username
GMAIL_PASS=password
TEMP_EMAIL=from10minutemail.com
```

Run test email and check [temporary email website](https://10minutemail.com/)

```
node nodemailerTest.js
```

Check terminal for url to check email

### Test via Gmail

Go to you gmail, under [account settings](https://support.google.com/mail/answer/7126229?visit_id=1-636452446836907712-1778859109&rd=2#cantsignin) and security turn on "Less secure apps" to allow this test email to run.

Run test email and check [temporary email website](https://10minutemail.com/)

```
node nodemailerGmail.js
```