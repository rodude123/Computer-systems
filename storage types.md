# Storage types
 
## Primary storage
  * Primary storage holds the least out of all memory types and usally only holds information for a short period of time         while the PC is running.
  * Has much lower access time and faster perfomance but more costly than secondary storage 
  * Can also be refered to as internal memory, main memory, main storage, and primary memory. 
  * used to load the OS

### Types of primary storage 
  * ROM - Read Only memory keeps information if no power, used to help with startup as in it tells the CPU what to do on         startup
  * RAM - Random Access Memory - located close to the cpu, fast memory, very expensive and so computers don't have much.         Once a computer shuts down the data gets lost
  * Cache - Very very fast and very expensive which is why it is very close to the CPU and only very important information       gets stored.
  * ROM is non-volatile
  * Most RAM is volatile 
  * ROM used for firmware updates
  * RAM used to store running programs
  
## Secodary storage
  * Can also be refered to as external memory, secondary memory, and auxiliary storage
  * Is non-volatile
  * Holds data until its deleted or overwritten 
  * Cheaper than primary storage 

### Types of secondary storage 
  * Hard drive - slower and stored further from the CPU which is why it is slower. It is also lot bigger than primary           storage. Only used for safe keeping e.g, OS's
  * SSD  - slower than primary but faster than hard drives because there is no mechanical parts. It is a costlier than hard     drive
  
#### Why we need it 
  * Without secondary storage we wouldnt be able to save any information from the computer after is powered off, however         with secondary storage we are able to save files and recover the last saved version of a document 
  
## Tertiary storage
   * The main aim of tertiary storage is to store large amounts of data for a cheap cost.  
   * It is primarily used for archiving rarely accessed information
   * It is much slower than secondary storage
   * When a computer needs to read information from tertiary storage, it checks the catalog database to                          determine which tape or disc contains the information.    
### Types of tertiary storage 
  * Magnetic tape - it is very old technology and is used primarly for backups due to having a very high capacity and its       low cost.
  * Optical disks -  
  
  
|![Computer storage](https://www.computerhope.com/jargon/s/storage.jpg)|
|:--------------------------------------------------------------------:|
|               ***The diagam about storage types***                   |
 

## RAID storage 
  * RAID storage stands for redundant array of independant disks 
  * RAID is a number of connected hard drives that are set up to in a way so as to help the speed and perfomance of a computer

### RAID techniques:
  1. Striping (RAID 0)
     - Splitting information and writing it across multiple disk drives. 
    
  2. Mirroring 
     - Duplication of data between disks 
 
  3. Duplexing
     - Duplicates disk drive and disk controller 
    
  4. Deferred
     - Data is stored in cache but moves to the hard drive when the disk drive is avaiable 
    
  5. Hot swapping
     - Data is replaced and moved from a failed disk drive onto a new one while the system is still operational
    
  6. Hot sparing
    - a disk drive is automatically initialised into the array when another fails
    
  7. Spindle sychronisation 
      - The synchronisation of disk drives allowing the array to similtaneously write information  
 
### Types of RAID 
 1. RAID 0
 2. RAID 1
 3. RAID 2
 4. RAID 3
 5. RAID 4
 6. RAID 5
 7. RAID 7
 8. RAID 10
 9. RAID 53

 * RAIDs can also be combined to create types such as RAID 0/1 which would combine the mirroring of RAID 1 and the striping 
    of RAID 0. 
    
## Virtual memory 
* Virtual memory is a memory management technique that allows the computer to compensate for an overworking RAM. A system using virtual memory has a section of its hardrive allocated to emulate RAM when is atcual RAM becomes overloaed. It only stores data that might be required soon. 
* Pros: Allows the user to use more RAM than they actually have and reduces risk of external fragmentation.
* Cons: can be slower since the access speed of the harddrive is slower than the RAM, thrashing, incorrect size allocation 

## Cloud computing 
* utility storage 
* Allows users to view, upload, download and store data from a collection of remote servers. 
* an abstract 'cloud' of computers that provides distributed storage and processing power. 
* pros: can be accessed anywhere, same data can be viewed across multiple deivces without having to be sent, cheap, can be used to back up data 
* cons: slower than physical storage, vunerability, cannot be accessed without internet, servers can go down making data unaccessible.


