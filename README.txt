# FinalProjectDS
 Final Data Science Project

The FinalProjectDS-workingcopy.ipynb file is our notebook as it was last run to show the matrices and the printout results.


The notebook consists of 7 parts:

Getting packages
- Here we define the packages we use for the whole notebook.

Getting CSV's
- Here we get the csv files. Note that the extracting of the big corpus csv-file is commented out, because we only needed it to get the cleaned version, and then we saved the cleaned version to file, so we would not have to clean again, because this takes a while.

The functions
- Here we define the function we use multiple times, such as clean and the vectorizing functions.

Processing the big dataset and visualizing
- Here we call the clean function on chunks of the big corpus, and gets some barplots about unique words and total words and the number of articles for each category. Not that the cleaning of the big dataset is inside a function that is commented out seeing as we only needed to do it once and then save the cleaned df. Examples of values saved to files are y_test_bin.pkl and X_val_liar.npz.

Processing the Liar dataset
- Here we process the liar dataset, we dont save any of this data because it is quick to do.
-Note that below this section there is a code-box with the text #Run everything above this. Running everything above this will prepare everything for the models.

The models with confusion matrices for evaluation.
- Here we train, save and load the all the models. As such only loading and evauating was neccesary. simple_nb_model_150 is an example of a naive bayes gaussian model run on 150 chunks of the big corpus dataset.

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


Package                      Version
---------------------------- ----------
absl-py                      1.4.0
anyio                        3.6.2
appnope                      0.1.3
argon2-cffi                  21.3.0
argon2-cffi-bindings         21.2.0
arrow                        1.2.3
asttokens                    2.2.1
astunparse                   1.6.3
attrs                        22.2.0
backcall                     0.2.0
beautifulsoup4               4.12.0
bleach                       6.0.0
cachetools                   5.3.0
certifi                      2022.12.7
cffi                         1.15.1
charset-normalizer           3.1.0
clean-text                   0.6.0
cleantext                    1.1.4
click                        8.1.3
cloudpickle                  2.2.1
comm                         0.1.2
contourpy                    1.0.7
cycler                       0.11.0
dask                         2023.3.1
debugpy                      1.6.6
decorator                    5.1.1
defusedxml                   0.7.1
emoji                        1.7.0
executing                    1.2.0
fastjsonschema               2.16.3
flatbuffers                  23.3.3
fonttools                    4.39.2
fqdn                         1.5.1
fsspec                       2023.3.0
ftfy                         6.1.1
gast                         0.4.0
google-auth                  2.16.2
google-auth-oauthlib         0.4.6
google-pasta                 0.2.0
grpcio                       1.51.3
h5py                         3.8.0
idna                         3.4
imbalanced-learn             0.10.1
imblearn                     0.0
ipykernel                    6.22.0
ipython                      8.11.0
ipython-genutils             0.2.0
ipywidgets                   8.0.4
isoduration                  20.11.0
jax                          0.4.6
jedi                         0.18.2
Jinja2                       3.1.2
joblib                       1.2.0
jsonpointer                  2.3
jsonschema                   4.17.3
jupyter                      1.0.0
jupyter_client               8.1.0
jupyter-console              6.6.3
jupyter_core                 5.3.0
jupyter-events               0.6.3
jupyter_server               2.5.0
jupyter_server_terminals     0.4.4
jupyterlab-pygments          0.2.2
jupyterlab-widgets           3.0.5
kiwisolver                   1.4.4
libclang                     16.0.0
locket                       1.0.0
Markdown                     3.4.3
MarkupSafe                   2.1.2
matplotlib                   3.7.1
matplotlib-inline            0.1.6
mistune                      2.0.5
mkl-fft                      1.3.1
mkl-random                   1.2.2
mkl-service                  2.4.0
nbclassic                    0.5.3
nbclient                     0.7.2
nbconvert                    7.2.10
nbformat                     5.8.0
nest-asyncio                 1.5.6
nltk                         3.8.1
notebook                     6.5.3
notebook_shim                0.2.2
numpy                        1.23.5
oauthlib                     3.2.2
opt-einsum                   3.3.0
packaging                    23.0
pandas                       1.5.3
pandocfilters                1.5.0
parso                        0.8.3
partd                        1.3.0
pexpect                      4.8.0
pickleshare                  0.7.5
Pillow                       9.4.0
pip                          23.0.1
platformdirs                 3.1.1
prometheus-client            0.16.0
prompt-toolkit               3.0.38
protobuf                     4.22.1
psutil                       5.9.4
ptyprocess                   0.7.0
pure-eval                    0.2.2
pyasn1                       0.4.8
pyasn1-modules               0.2.8
pycparser                    2.21
Pygments                     2.14.0
pyparsing                    3.0.9
pyrsistent                   0.19.3
python-dateutil              2.8.2
python-json-logger           2.0.7
pytz                         2022.7.1
PyYAML                       6.0
pyzmq                        25.0.2
qtconsole                    5.4.1
QtPy                         2.3.0
regex                        2022.10.31
requests                     2.28.2
requests-oauthlib            1.3.1
rfc3339-validator            0.1.4
rfc3986-validator            0.1.1
rsa                          4.9
scikit-learn                 1.2.2
scipy                        1.10.1
seaborn                      0.12.2
Send2Trash                   1.8.0
setuptools                   65.6.3
six                          1.16.0
sniffio                      1.3.0
soupsieve                    2.4
stack-data                   0.6.2
tensorboard                  2.12.0
tensorboard-data-server      0.7.0
tensorboard-plugin-wit       1.8.1
tensorflow-estimator         2.12.0
tensorflow-io-gcs-filesystem 0.31.0
termcolor                    2.2.0
terminado                    0.17.1
threadpoolctl                3.1.0
tinycss2                     1.2.1
toolz                        0.12.0
tornado                      6.2
tqdm                         4.65.0
traitlets                    5.9.0
typing_extensions            4.5.0
Unidecode                    1.3.6
uri-template                 1.2.0
urllib3                      1.26.15
wcwidth                      0.2.6
webcolors                    1.12
webencodings                 0.5.1
websocket-client             1.5.1
Werkzeug                     2.2.3
wheel                        0.38.4
widgetsnbextension           4.0.5
wrapt                        1.14.1
zipfile38                    0.0.3