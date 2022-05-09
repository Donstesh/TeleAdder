# Pro Version Of Telegram Member Adder Tool

Contact me to get the Pro Version of this TeleAdder :


 Telegram : https://t.me/daredevilkinng
 
 
# Script to export members Telegram Groups and Channels to a CSV file and to add members to Telegram Groups or Channels.

> Exporting and adding members to channels requires the user from which the script is launched to be a Channel admin.

### Install dependencies

You'd need python3 and pip3 installed and available in your PATH.

Run `pip3 install telethon` from the projects root directory.

### Telegram Configuration

1. To run it you need to generate API credentials for your Telegram user, you can do it [here](https://my.telegram.org), and access your already created ones [here](https://my.telegram.org)
2. Replace your credentials in the script
    ```python
    api_id = 000000        # YOUR API_ID
    api_hash = 'XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX'        # YOUR API_HASH
    phone = '+34000000000'        # YOUR PHONE NUMBER, INCLUDING COUNTRY CODE
    ```

### Export users
Just follow the instructions in the script after running it from your the shell.

### Add users to groups

Users can be added using:
- **Username**: Gets temporarily banned with less requests.
- **User ID**: Gets temporarily banned with more requests.

> Temporarily bans last for up to a day in my experience.

Adding users by Username expects a CSV file with one username per line.
Adding users by User ID expects a CSV file such as: `username,user_id,user_access_hash`

> No headers are expected in the CSV files

Once you have your CSV prepared, just follow the instructions in the script.


<p align="center">
  Follow Me On
</p>
<p align="center">
  <a href="https://youtu.be/DiXvVSzFo0g">
    <img src="https://www.iconsdb.com/icons/preview/black/youtube-4-xxl.png" width="40" height="40">
  </a>
</p>


# Telegram-Scraper-Adder-Complete
this version of python script will help you to scrap members fron any Group/Channel/Supergroups or Superchannels as well as add members to your telegram group and also you can send concesutive message (TeleGram SMS) without having any trouble at all. All instructions are given below please perform them step by step 100% working procedure Coded by DareDevilKinng.

This method is only created for educational purposes only.

-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*
                                             STEP BY STEP PROCEDURE 
*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-


# Telegram-Scraper & Adder


NOTE : these commands are for android devices. All Android devices are supported. On linux OS all you have to just install telethon and rest is same.



PROCEDURE:-


$ apt update && upgrade


$ pkg install python


$ pkg install python -y


$ pkg install git -y


$ pkg install -y git python


$ git clone https://github.com/daredevilkinng/TeleAdder.git


$ cd TeleAdder


$ ls



Install requierments

$ python3 setup.py -i



To setup configration file ( API ID, API HASH )

$ python3 setup.py -c

$ python3 smsbot.py members.csv



To Genrate User Data

$ python3 scraper.py

( members.csv is default if you changed name use it )



Send Bulk sms To Scrpped data

$ python3 smsbot.py members.csv



Add users to your group

$ python3 groupadd.py members.csv



Update Tool

$ python3 setup.py -u

