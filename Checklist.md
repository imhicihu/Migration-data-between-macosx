## Procedures

#### Energy
* Verify there is no power failures
* Attach every involved device in the procedure to a [UPS](https://en.wikipedia.org/wiki/Uninterruptible_power_supply), to prevent power failure
* Verify status of internal battery. A must condition: _fully charged_

#### System
* In the ~~Mojave~~ High Sierra macbook, verify that the account name you set up not be the same name as any of the accounts you're migrating of (_critical issue_)
* Verify (and fix) any erroneous computer's date & time. Update or correct with the current `time zone`
* Verify the Trash is empty. If not, undelete all the files and copy to portable hard disk.

#### System Preferences
* Verify `Users & Groups` inside `System Preferences`
    - Go to `System Preferences` > `Users & Groups` > `Login items`
        - Remove any application to open automatically when you log in
* Verify `Security & Privacy` inside `System Preferences`
    - Go to `System Preferences` > `Security & Privacy` > `General`
        - Disable `Require password` option
    - Go to `System Preferences` > `Security & Privacy` > `FileVault`
        - Disable `FileVault`
    - Go to `System Preferences` > `Security & Privacy` > `Firewall`
        - Disable `Firewall`
    - Go to `System Preferences` > `Security & Privacy` > `Privacy` > `Analytics`
        - Disable `Share Mac Analytics` & `Share with App Developers`
* Verify `Energy Saver` inside `System Preferences`
    - Go to `System Preferences` > `Energy Saver` > `Battery`
        - Disable `Turn display off after`: `Never`
        - Disable `Put hard disks to slep when possible`
        - Disable `Enable Power nap while on battery power`
        - Enable `Show battery status in menu bar`
    - Go to `System Preferences` > `Energy Saver` > `Power Adapter`
        - Disable `Prevent computer from sleeping automatically when the display is off`
        - Disable `Turn display off after`: `Never`
        - Disable `Put hard disks to slep when possible`
        - Disable `Enable Power nap while on battery power`
* Enable `Keychain Access` backup on `System Preferences`
    - Go to `System Preferences` -> `iCloud` -> `Keychain` -> Enable it

* Verify if the computer is _under_ password. The same goes for _inner_ Windows session(s)
* Disable any File sharing option: during diagnostic, defrag or copy/move/backup of files between devices
* Turn off the access to internet: 
     - turn `off` wifi connection 
     - detach LAN access 

#### Drives (internal & external)
* Verify the health of the disk drive, then defrag it. 
    - Open Disk Utility (`Applications` > `Utilities`)
    - Choose your startup disk.
    - Click `Verify Disk Permissions` to check permissions.
    - Click `Repair Disk Permissions` to repair any inconsistent permissions.
    - Defragmentation is not a serious issue in MacOSX operating systems. Even more, [no advisable](https://macpaw.com/how-to/how-to-defrag-mac) on macs with SSD hard drives.  
* Verify the health of the external hard disk, then defrag it.
    - Open Disk Utility (`Applications` > `Utilities`)
    - Choose your startup disk.
    - Click `Verify Disk Permissions` to check permissions.
    - Click `Repair Disk Permissions` to repair any inconsistent permissions.
    - Defragmentation is not a serious issue in MacOSX operating systems. Even more, [no advisable](https://macpaw.com/how-to/how-to-defrag-mac) on macs with SSD hard drives.
* Verify the health of the pen drive, then defrag it. 
    - Open Disk Utility (`Applications` > `Utilities`)
    - Choose your startup disk.
    - Click `Verify Disk Permissions` to check permissions.
    - Click `Repair Disk Permissions` to repair any inconsistent permissions.
    - Defragmentation is not a serious issue in MacOSX operating systems. Even more, [no advisable](https://macpaw.com/how-to/how-to-defrag-mac) on macs with SSD hard drives.

#### Antivirus
* Update to the latest definitions of the antivirus resident on the (primary) computer
* Do a full scan with the antivirus on the operating system, files, _etc_. The same goes for the hard disk or pen drive
    - If there are _virus_: notify it!
* Close all the software in memory or actually running during the procedure of copy/move/backup of files between devices
* Enable Spotlight on both operating systems
    - Go to `System Preferences` -> `Spotlight` -> `Search results` -> Enable only `Applications`

#### Backup
* Install backup software to migrate between operating systems or devices.
    - Install Carbon Copy Cloner
    - Install SuperDuper
    - Choose the above software that fit most of your migration needs
* Create `.ISO` images of folders that is mandatory to maintain the framework of folders (ie. folders nested inside another folders). In a nutsell, create full _mirror_ images of folders and files (even with _hidden_ attributes)
    - `~/Library/`
    - `~/Library/Preferences`
    - `~/Library/Application Support`
* To prevent the worst scenario as possible: backup to a "healthy" external hard disk drive or dvd or blu-ray discs
* Verify that iCloud account got -at least 500 MB of free space- to give room to Keychain rules _et alia_ (the more space, the better).

#### Online tools
* [AppleID](https://appleid.apple.com/): (`user` and `password` required) > to backup Keychain data
* [iCloud](https://www.icloud.com/): (`user` and `password` required) > to backup Keychain data
