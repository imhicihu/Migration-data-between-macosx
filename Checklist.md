(this comes from this file: [checklist.md](https://bitbucket.org/imhicihu/migration-data-checklist/src/83368208d724a49b6b23d71f90fb65f5070d78b3/Checklist.md?at=master) from another internal [repo](https://bitbucket.org/imhicihu/migration-data-checklist)).

## First stage
* Attach every involved device in the procedure to a [UPS](https://en.wikipedia.org/wiki/Uninterruptible_power_supply), to prevent power failure
* Verify (and fix) any erroneous computer's date & time
* Verify status of internal battery
* Verify if the computer is _under_ password. The same goes for _inner_ Windows session(s)
* Turn off the access to internet: 
     - turn off wifi connection 
     - detach LAN access 
* Verify the health of the disk drive, then defrag it. Both actions can be done with [Defragler](https://www.ccleaner.com/defraggler)
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