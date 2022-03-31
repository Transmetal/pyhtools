# PyHTools

<!-- Image Dim: 940x788 -->

- Python Hacking Tools (PyHTools) (pht) is a collection of python written hacking tools consisting of network scanner, arp spoofer and detector, dns spoofer, code injector, packet sniffer, network jammer, email sender, downloader, wireless password harvester credential harvester, keylogger, download&execute, and reverse_backdoor along with website login bruteforce, scraper, web spider etc. PHT also includes malwares which are undetectable by the antiviruses.


- The tools provided are for educational purposes only. The developers are no way responsible for misuse of information and tools provided. All the information and tools are meant to help newbies to learn new concepts. 

- These tools are written in python3, refer installation to install/download tools and its dependencies.

- PyHTools comes with UI, but you can also use command line to use tools individually.

**`NOTE` : The UI hasn't been updated yet with new tools, and evil files so using cli is preferred.**

### Installation

1. Open terminal

2. Install git package
   ```
   sudo apt install git python3 -y
   ```
   
3. clone the repository to your machine
   ```
   git clone https://github.com/Transmetal/pyhtools
   ```
4. Change directory
   ```
   cd pyhtools
   ```
  
5. install requirements
   ```
   python3 -m pip install -r requirements.txt
   ```

### Start PHTools

1. change to pyhtools directory 
   ```
   cd pyhtools
   ```
2. run pyhtools.py
   ```
   python3 pyhtools.py
   ```
3. to get all the commands use `help`
   ```
   pyhtools >> help
   ```

> There may be chances that pyfiglet or kamene will not be installed through requirements.txt, you can install manually using `pip3 install pyfiglet kamene`.
> If you're using Termux or windows, then use `pip` instead of `pip3`. 

### Tools and Features 
   #### Attackers
   - `For Networks`
      - Network Scanner
      - Mac changer
      - ARP Spoofing 
      - DNS spoofing 
      - Downloads Replacer
      - Network Jammer
      - Pkt Sniffer
      - Code Injector
   - `For Websites`
      -  Login Guesser (Login Bruteforcer)
      -  Web Spider
      -  Web crawler (detects dirs | subdomains)
      -  Web Vulnerablity Scanner

   #### Detectors
   - ARP Spoof Detector
   
   #### Malwares/Trojans/Payloads/Ransomwares/Worms
   - Email Sender (reporter)
   - Downloader
   - Wireless Password Harvester
   - Credential Harvester
   - Keylogger (dlogs)
   - Reverse Backdoors
      - [TCP](https://github.com/dmdhrumilmistry/pyhtools/tree/main/malwares/reverse_backdoor/TCP)
      - [HTTP](https://github.com/dmdhrumilmistry/pyhtools/tree/main/malwares/reverse_backdoor/HTTP)
   - Download and Execute
   - [Telegram Data Harvester](https://github.com/dmdhrumilmistry/pyhtools/blob/main/malwares/telegram_data_harvester/HowToUse.md)
   - [DMSecRansomware](https://github.com/dmdhrumilmistry/pyhtools/blob/main/ransomwares/dmsec/HowToUse.md)
   - [Telegram Remote Code Executor](https://github.com/dmdhrumilmistry/pyhtools/tree/main/malwares/TelegramRemoteCodeExecutor)
   - DirCloner
  > Do not upload/send/report malwares to anti virus services such as `VirusTotal`. This will make program detectable
     

### Dependencies

   **`PHT`** requires following programs/scripts to run properly -
   - `Python`
      - `subprocess`
      - `scapy`
      - `kamene`
      - `pyfiglet`
      - `argparse`
      - `re`
      - `sys`
      - `os`
      - `shutil`
      - `pyinstaller`
   
   > **NOTE:** most of the modules are pre-installed, still to ensure the proper working of scripts, user should install the required modules using pip
