# Software Updater

## 1. Software Updater - Admin

> This is the admin side of the software, where the user has the ability to upload new updates and patches to google drive.

---

Instructions

1. Create a google cloud console project.
1. Setup 0Auth.
1. Create Credentials (Choose Desktop Application While Setting Credentials).
1. Download the .json file, rename it to 'credentials.json' and place it inside the application directory.
1. Build or Run the project (First, choose option 2 and authenticate with drive).

## 2. Software Updater - Client

> This is the client side of the software, where the user can only download new updates and patches from google drive.

---

Instructions

1. Instructions for creating the credential file is as before mentioned in the admin side.
1. Download the .json file AGAIN!, rename it to 'credentials.json' and place it inside the application directory (Remember to use a new credentials file because, permissions are different in the client side - only read permission is given to the client).
1. Build or Run the project (First, choose option 2 and authenticate with drive).

---

`Note:- When Authorizing, please copy and paste the authorization token from the URL if it says 'localhost refused to connect'.`