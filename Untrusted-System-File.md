
This error usually appears on game launch and may give you some information about what file is not trusted. This is likely _EasyAntiCheat_ flagging a file as untrusted, not _Realm Royale_. There are a few possible solutions:

**1. Look at the error message given and read the file path that it says is untrusted. Another program may be the issue. One specific user had software installed to communicate with his bank account on his desktop that EAC thought was untrusted. Once he deleted the software he was able to play!**

**2. Use a system file checker tool - You could have corrupted files**

_2.1. Quick Version that might work: At the windows command prompt, type the following command, and then press ENTER: sfc /scannow_

_2.2. In-depth instructions [here](https://support.microsoft.com/en-us/help/929833/use-the-system-file-checker-tool-to-repair-missing-or-corrupted-system)_

**3. Find all places that EasyAntiCheat is installed. Delete the “Certificate” folder. Launch your game.**

**4. Add EAC and Realm Royale to your firewall and anti virus white list.**

**5. In rare cases this can be due to an infection. Run a full system scan, you can use [Malwarebytes](https://www.malwarebytes.com) if you don’t have a virus scanner.**
