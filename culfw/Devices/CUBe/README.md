# Firmware f�r den MapleCUL/MapleCUN


## ben�tigte Tools

STM32 Flash loader demonstrator: http://www.st.com/en/development-tools/flasher-stm32.html
a-culfw: https://www.mediafire.com/folder/tf16radvztfd9/a-culfw
USB zu TTL Adapter. 


## a-culfw flashen

- RX1/TX1 am Maple Mini mit einem USB/TTL Adapter mit dem PC verbinden.
- USB Kabel am Maple Mini anschlie�en.
- Taste but=32 am Maple Mini dr�cken und gerd�ckt halten.
- Taste reset am Maple Mini dr�cken.
- Tasten loslassen.
- Flash loader demonstrator starten.
- Com Port des USB/TTL Wandler ausw�hle, Baud Rate 115200, Parity Even, Echo Disabled, Timeout 1.
- Auf Next dr�cken.
- Es sollte die Meldung erscheinen. Target is readable. Please click "Next" to proceed.
- Auf Next dr�cken.
- Auf Next dr�cken.
- Download to device ausw�hlen.
- Datei MapleCUL.bin bzw. MapleCUN.bin �ffnen.
- Erase necessary pages ausw�hlen.
- Auf Next dr�cken.
- Warten bis Flashvorgang abgeschlossen ist.
- USB Kabel am Maple Mini entfernen. 

