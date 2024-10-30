## <a id="features"></a>📋・Information
```
The Keyauth Server can simulate nearly all aspects of Keyauth, including:

Full simulation of the initialization process, including the login system.
Features such as logs, bans, and blacklists are disabled

We hereby declare that we do not possess any ownership rights or proprietary claims to the provided software
The author and owner of the provided software is Keyauth LLC. 
Forceful removal (DMCA takedown) of the provided content will result in further retaliation.
```

<details>
  <summary>Click me for the Usage Tutorial</summary>
  
## <a id="Changelog"></a>🔥・Usage Tutorial
```
Step 1: Setup everything
Add the generated root CA certificate to trusted root certificates

Double-click on rootCA.crt
Click "Install certificate"
Select "Local Machine," then click "Next"
Select "Place all certificates in the following store," click "Browse" and select "Trusted Root Certification"
Click "Finish" ( only needed to do 1 time )
Same thing for keyauth.win.crt Certificate but Just pressing next works fine ( also 1 time also )

Both of them are in the Folder x64/Release/certs

Now please install the OpenSSL 3.3.2 Windows Installer. 
https://kb.firedaemon.com/support/solutions/articles/4000121705#Download-OpenSSL

Once everything is done run Emulator.exe and paste your secret key of your keyauth loader

REMINDER ONLY MEANT FOR ALLOWED USE OF LOADERS AND MEANT FOR EDUCATION

```
</details>

<details>
  <summary>Click me for the Compiling Tutorial</summary>

## <a id="Changelog"></a>👷・Compiling
```
1. install the OpenSSL 3.3.2 Windows Installer. 
https://kb.firedaemon.com/support/solutions/articles/4000121705#Download-OpenSSL
2. Make sure you have VS2022 with C++ build tools and MFC installed
3. Open `EmuAuth.sln` and compile the project
4. Generate required certificates using the script in `Certificates/` and place them in `certs/`

**Tipp** They are already generated but if they expire you would need to regenerate them!
```
</details>


