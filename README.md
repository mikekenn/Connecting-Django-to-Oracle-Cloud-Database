# Connecting-Django-to-Oracle-Cloud-Database
## Creating an Oracle Cloud Free Tier Account and Provisioning a Database

1. Start by either singing in, or creating a new account at [OCI Cloud Free Tier](https://www.oracle.com/ca-en/cloud/free/)
2. Under the hamburger menu in the top left, select `Oracle Database`, then select `Autonomous Database`.
![Screenshot1](../assets/img1.png?raw=true)
3. Click on `Create Autonomous Database`.
![Screenshot1](../assets/img1.png?raw=true)
4. Change your `Display Name` and `Database Name` (The name must contain only letters and numbers, starting with a letter. Maximum of 30 characters.) to whatever you like.
5. For _Workload type_ i generally select `Transaction Processing` as alot of these little tutorials are not processing huge queries over massive datasets.
6. `Configure the database` - Select _Always Free_.
7. `Create administrator credentials` - I generally always leave this as ADMIN and give it a good password you wont forget.
8. `Choose network access` - I always select _Secure access from everywhere_ and ensure that _Require mutual TLS (mTLS) authentication_ is selected.
9. Then click `Create Autonomous Database` at the bottom of the page. It will take about a minute or so for the Cloud DB to provision.
10. Once the databse has provisioned, click on your database name and then select `Database Connection`.
11. `Download client credentials (Wallet)` - for Wallet Type_ select `Instant Wallet`, then download the Wallet. It will ask you to input a password to create it. Do so, and remember the password.

## Creating Django Project & Configuration.
TODO

## Downloading Oracle Client Libraries and Configuration.
TODO

## Setting up .env file.
TODO