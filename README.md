# FinalProjectDS
 Final Data Science Project


The notebook consists of 7 parts:

Getting packages
- Here we define the packages we use for the whole notebook.

Getting CSV's
- Here we get the csv files. Note that the extracting of the big corpus csv-file is commented out, because we only needed it to get the cleaned version, and then we saved the cleaned version to file, so we would not have to clean again, because this takes a while.

The functions
- Here we define the function we use multiple times, such as clean and the vectorizing functions.

Processing the big dataset and visualizing
- Here we call the clean function on chunks of the big corpus, and gets some barplots about unique words and total words and the number of articles for each category. Not that the cleaning of the big dataset is inside a function that is commented out seeing as we only needed to do it once and then save the cleaned df.

Processing the Liar dataset
- Here we process the liar dataset, we dont save any of this data because it is quick to do.
-Note that below this section there is a code-box with the text #Run everything above this. Running everything above this will prepare everything for the models.

The models with confusion matrices for evaluation.
- Here we train, save and load the all the models. As such only loading and evauating was neccesary

The final tests for the models using test datasets.
- Confusion matrices for all the models using test datasets.



Til kørsel af modeller blev nedstående computer med spesificationer brugt. Yderst vigtigt er det at der er 16GB ram på maskinen for at kunne reproducere modellerne.

OS-navn	Microsoft Windows 11 Home
Version	10.0.22621 Build 22621
Anden OS-beskrivelse	Ikke tilgængelig
OS-producent	Microsoft Corporation
Systemnavn	DESKTOP-54FL9S3
Systemproducent	HP
Systemmodel	HP ENVY x360 Convertible 15-ee0xxx
Systemtype	x64-based PC
System-SKU	158P3EA#UUW
Processor	AMD Ryzen 7 4700U with Radeon Graphics, 2000 Mhz, 8 Kerne(r), 8 Logisk(e) processor(er)
BIOS-version/dato	Insyde F.22, 03/11/2022
SMBIOS-version	3.2
Version af integreret controller	13.47
BIOS-tilstand	UEFI
BaseBoard-producent	HP
BaseBoard-produkt	876F
BaseBoard-version	13.47
Platformrolle	Mobiltelefon
Sikker bootstarttilstand	Slået til
PCR7-konfiguration	Der kræves elevation for at se
Windows-mappe	C:\WINDOWS
System-mappe	C:\WINDOWS\system32
Startenhed	\Device\HarddiskVolume1
Landestandard	Storbritannien
Abstraktionslag for hardware	Version = "10.0.22621.1413"
Brugernavn	DESKTOP-54FL9S3\Baxe
Tidszone	Rom, sommertid
Installeret fysisk hukommelse (RAM)	16,0 GB
Fysisk hukommelse i alt	15,4 GB
Tilgængelig fysisk hukommelse	8,25 GB
Virtuel hukommelse i alt	28,4 GB
Tilgængelig virtuel hukommelse	18,8 GB
Plads til sidefil	13,0 GB
Sidefil	C:\pagefile.sys
Kerne-DMA-beskyttelse	Slået fra
Virtualiseringsbaseret sikkerhed	Kører
Påkrævede sikkerhedsegenskaber for virtualiseringsbaseret sikkerhed	
Tilgængelige sikkerhedsegenskaber for virtualiseringsbaseret sikkerhed	Understøttelse af grundlæggende virtualisering, Sikker bootstart, DMA-beskyttelse, UEFI-kode skrivebeskyttet, SMM Security Mitigations 1.0, Tilstandsbaseret udførelseskontrol
Konfigurerede tjenester for virtualiseringsbaseret sikkerhed	
Tjenester til virtualiseringsbaseret sikkerhed kører	
Politik for Windows Defender Application Control	Gennemtvunget
Politik for brugertilstand i Windows Defender Application Control	Slået fra
Understøttelse af enhedskryptering	Der kræves elevation for at se
Der er fundet en hypervisor. Funktioner, der kræves til Hyper-V, vises ikke.	
