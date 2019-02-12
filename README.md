# Unk9S_BoT
Robot for downloading file types and uploading it to the telegram servers and vice versa and downloading files uploaded to the telegram and making their download link from the mega.nz servers.

# icon...

![alt text][logo]

[logo]: https://raw.githubusercontent.com/unk9vvn/Unk9S_BoT/master/icon.jpg "Logo Title Text 2"





This robot will not store transaction information and will function as a dummy, in which case you no longer need to buy money services to cover the size of the robot, and information security will be maintained,

The next striking thing is that the robot chooses the names of the transacted files as a chance, so it does not interfere with the file management, and it can be very quick, and the very last of its operations is the files made on the mega.nz server. Clears the desired server.

This robot communicates directly with the mega.nz cloud network API and automatically installs and uses Megacmd on Windows platforms, all of which will be done automatically.

Note To use the robot, you must register on https://mega.nz/register and enter your username and password in the Unk9S_BoT.py script in the

    subprocess.Popen(
        'start cmd.exe /c "MEGAcmdServer"',
        shell=True)
    time.sleep(5)
    subprocess.Popen(
        'mega-login unk9vvn@gmail.com 00980098"',
        shell=True)

    updater = Updater('Token')
        
In the Email and Password fields, enter your information. Also, in Token, insert Token and start the script.


# How to Run
```
git clone https://github.com/unk9vvn/Unk9S_BoT.git & cd Unk9_BoT && chmod 755 *
pip install telegram python-telegram-bot requests wget;python -m pip install --upgrade pip
python Unk9S_BoT.py
```
