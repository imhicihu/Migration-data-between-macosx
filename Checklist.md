## Procedures

#### Energy
* Verify there is no power failures
* Attach every involved device in the procedure to a [UPS](https://en.wikipedia.org/wiki/Uninterruptible_power_supply), to prevent power failure
* Verify status of internal battery. A must condition: _fully charged_

#### System
* In the ~~Mojave~~ High Sierra macbook, verify that the account name you set up not be the same name as any of the accounts you're migrating of (_critical issue_)
* Verify (and fix) any erroneous computer's date & time. Update or correct with the current `time zone`
* Verify the Trash is empty. If not, undelete all the files and copy to portable hard disk.
* Verify iCloud space availability. _The more, the better._
* Verify if exist a [software protection](https://en.wikipedia.org/wiki/Software_protection_dongle) (_aka_ dongle). Take in count if it is USB or port based. _Hint_: take a photo of actual position to replicate the same environment in the future. 
* Launch `iTunes`: Go to `Account` > `Authorizations` > `Deauthorize This Computer` 

#### System Preferences
* Enable `Spotlight` on both operating systems
    - Go to `System Preferences` -> `Spotlight` -> `Search results` -> Enable only `Applications`
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
* Verify `User & Groups` inside `System Preferences`
    - Go to `System Preferences` > `User & Groups`
        - On `Current User` click on `Password`
                - Verify password for the current user
                - Disable any parental control
        - On `Current User` click on `Login Items`
                - Disable any login item
* Verify (and enable) this settings in `iCloud` inside `System Preferences`. *Do this for every user of the primitive machine*.
    - Go to `System Preferences` -> `iCloud` 
        - Enable `iCloud Drive`
            * Click on `Options`: 
                - Enable `System Preferences`
                - Enable `Contacts`
                - Enable `Calendars`
                - Enable `Notes`
                - Enable `Reminders`
                - Enable `Safari` (it will backup bookmarks and any historical record session from the current user)
                - Enable `Keychain Access` (*a must condition*)
                - Enable `Find my Mac` (for security issues)
* Verify if the computer is _under_ password. The same goes for ~~_inner_~~ user session(s)
* Disable any File sharing option: during diagnostic, ~~defrag~~ or ~~copy/move/~~backup of files between devices
* Then, turn _off_ (disable) access to internet: 
     - turn `off` wifi connection 
     - detach any LAN access through wired connection

#### Drives (internal & external)
* Verify the health of the disk drive, ~~then defrag it.~~
    - Open Disk Utility (`Applications` > `Utilities`)
    - Choose your startup disk.
    - Click `Verify Disk Permissions` to check permissions.
    - Click `Repair Disk Permissions` to repair any inconsistent permissions.
    - Defragmentation is not a serious issue in MacOSX operating systems. Even more, [no advisable](https://macpaw.com/how-to/how-to-defrag-mac) on macs with SSD hard drives.  
* Verify the health of the external hard disk, ~~then defrag it.~~
    - Open Disk Utility (`Applications` > `Utilities`)
    - Choose your external hard disk.
    - Click `Verify Disk Permissions` to check permissions.
    - Click `Repair Disk Permissions` to repair any inconsistent permissions.
    - Defragmentation is not a serious issue in MacOSX operating systems. Even more, [no advisable](https://macpaw.com/how-to/how-to-defrag-mac) on macs with SSD hard drives.
    - _Advice:_ Obliterate your external hard disk.
* Verify the health of the pen drive, ~~then defrag it.~~
    - Open Disk Utility (`Applications` > `Utilities`)
    - Choose your pen disk drive.
    - Click `Verify Disk Permissions` to check permissions.
    - Click `Repair Disk Permissions` to repair any inconsistent permissions.
    - _Advice:_ Obliterate your pen drive.

#### Online accounts 
* [AppleID](https://appleid.apple.com/): (Know your `user` and `password`) > login to set `user` and `password` settings in the Keychain Access app.
* [iCloud](https://www.icloud.com/): (Know your `user` and `password`) > login to set `user` and `password` settings in the Keychain Access app.

#### Antivirus
* Update to the latest definitions of the antivirus resident on the (source) computer
* Do a full scan with the antivirus on the operating system, files, _etc_. The same goes for the hard disk or pen drive. 
    - If there are _virus_: notify it!
* Close all the software in memory or actually running during the procedure of ~~copy/move/~~backup of files between devices

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

#### Mail accounts
* Create `.ISO` images of folder `Mail` from here: include nested folders (if apply)
    - `Macintosh HD` > `Users` > `_number of user_` > `Library` > `Mail`
* Locate and backup this file `com.apple.mail.plist` & `MessageRules.plist` from here:
    - `Macintosh HD` > `Users` > `_number of user_` > `Library` > `Preferences`
