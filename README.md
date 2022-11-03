# Bash-PortScanner
Created a bash script to easily connect to ports using TCP IP.

- This script can find open ports in a subnet saving files to different files with their IP's as filename.
- You can modify the script to target specific ports ie target systems which their RDP ports(3389) are open.
- Use the `BPscanner` script to find specific ports.
- **NB: set execute permissions on the scripts before running**


![Screenshot from 2022-11-03 15-30-03](https://user-images.githubusercontent.com/106890328/199722760-4a6a9910-db52-4cf9-9e09-3618f3ffe72b.png)

 - As you can see we have scanner ports range `1-5000` and found 2 ports 3000 and 80.
 - The script also saves file using its ip making it easier for analysing.
 
 
 - To target specific ports on a network ran the `areabpScanner`.
 
 
 [scanner.webm](https://user-images.githubusercontent.com/106890328/199724194-26b307f6-0c6a-4a47-a296-b165c535e348.webm)
   
   - This may take time as it goes through all ports in a network and different files of different hosts.
   
 **NB: Only for educational purposes.**
