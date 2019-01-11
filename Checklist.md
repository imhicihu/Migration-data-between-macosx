## First stage

* Attach every involved device in the procedure to a [UPS](https://en.wikipedia.org/wiki/Uninterruptible_power_supply), to prevent power failure
* Verify (and fix) any erroneous computer's date & time
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
* Verify status of internal battery. A must condition: fully charged
* Verify if the computer is _under_ password. The same goes for _inner_ Windows session(s)
* Turn off the access to internet: 
     - turn `off` wifi connection 
     - detach LAN access 
* Verify the health of the disk drive, then defrag it. 
    - Open Disk Utility (`Applications` > `Utilities`)
    - Choose your startup disk.
    - Click `Verify Disk Permissions` to check permissions.
    - Click `Repair Disk Permissions` to repair any inconsistent permissions.
    - Defragmentation is not a serious issue in MacOSX operating systems. Even more, [no advisable](https://macpaw.com/how-to/how-to-defrag-mac) on macs with SSD hard drives.
    
* Verify the health of the external hard disk, then defrag it. Both actions can be done with [Defragler](https://www.ccleaner.com/defraggler)
* Verify the health of the pen drive, then defrag it. Both actions can be done with [Defragler](https://www.ccleaner.com/defraggler)
* Update to the latest definitions of the antivirus resident on the (primary) computer
* Do a full scan with the antivirus on the operating system, files, _etc_. The same goes for the hard disk or pen drive
    - If there are _virus_: notify it!
* File sharing: `off` during diagnostic, defrag or copy/move of files between devices
* Close all the software in memory or actually running during the procedure of copy/move files between devices
* Install backup software to migrate between operating systems or devices. 
* Create `.ISO` images for folders that is mandatory to maintain the framework of folders (ie. folders nested inside another folders). In a nutsell, create full _mirror_ images of folders and files (even with _hidden_ attributes)
* Backup to a "healthy" external disk drives, pendrives, dvd or blu-ray discs
* 


## Backup

#### Spotlight

* Enable Spotlight on operating system
* Go to `System Preferences` -> `Spotlight` -> `Search results` -> Enable only `Applications`

#### Operating system

* `~/Library/`
* `~/Library/Preferences`
* `~/Library/Application Support`

#### Software
* Keychain Access (via Spotligh)
* `Little Snitch` rules (exported from the original mac)

#### Online tools
* [AppleID](https://appleid.apple.com/): (`user` and `password` required) > to backup Keychain data
* [iCloud](https://www.icloud.com/): (`user` and `password` required) > to backup Keychain data
