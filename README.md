# Index
- [DNS Example for W6100-EVB](#DNS-Example-for-W6100-EVB)
- [Hardware Environment](#Hardware-Environment)
- [Software Environments](#Software-Environment)
- [Run](#Run)
- [Code review](#Code-review)
  - [Test packet capture file](#Test-packet-capture-file)


------
# DNS Example for W6100-EVB
Common to Any MCU, Easy to Add-on. Internet Offload co-Processor, HW TCP/IP chip,
best fits for low-end Non-OS devices connecting to Ethernet for the Internet of Things. These will be updated continuously.

## Hardware Environment
* W6100EVB
  - connecting Micro usb.
  - connecting Ethernet cable. <br>
<p align="center">
  <img width="60%" src="https://wizwiki.net/wiki/lib/exe/fetch.php?w=600&tok=eabde4&media=products:w6100:w6100_evb:w6100-evb_callout.png" />
</p>

## Software Environment
In case of used to TrueSTUDIO,it is the same as HTTP Server example.
 - Link : [Software Environment of W6100EVB-HTTP_Server](https://github.com/WIZnet-ioLibrary/W6100EVB-HTTP_Server#Software-Environment)


## Run
* Demo Environment & Program <br>

  - Windows 10 <br>
  - Hercules <br>

* Demo Result <br>
  - Power On and push Reset button to start Program<br>
  - Program Run Serial display <br>
  <p align="center">
    <img width="60%" src="https://user-images.githubusercontent.com/9648281/55851813-4e189780-5b95-11e9-9b26-95b5240da34c.JPG" />
    <img width="60%" src="https://user-images.githubusercontent.com/9648281/55851814-4eb12e00-5b95-11e9-9588-5e61cf770855.JPG" />
  </p>
  - If you push the user0 or user1 on the W6100EVB, you can get the IPv4 or IPv6 of DNS server.
  
  <p align="center">
    <img width="60%" src="https://user-images.githubusercontent.com/9648281/55851812-4e189780-5b95-11e9-91fe-21fb8330ae9e.JPG" />
  </p>

  ## Code review
  * main.c code flow <br>
  <p align="center">
    <img width="50%" src="https://user-images.githubusercontent.com/9648281/55852110-92f0fe00-5b96-11e9-87b7-f99511bc1521.jpg" />
  </p>

   ## Test packet capture file
   <p align="center">
   <img width="100%" src="https://user-images.githubusercontent.com/9648281/55851980-0b0af400-5b96-11e9-8b38-45d2e5a5546b.JPG" />
    </p>

    
    -Test packet capture file : [DNS_Packet Capture file.zip](https://github.com/WIZnet-ioLibrary/W6100EVB-DNS/files/3062008/DNS.Result.Packet.Capture.zip)

