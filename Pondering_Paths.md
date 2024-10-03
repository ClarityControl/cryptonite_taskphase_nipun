# Pondering_Paths
This module mainly focuses on teaching the basics of file paths.
### 1. The Root
This challenge teaches the very basics of a path, with the path simply being /pwn.
>Flag: pwn.college{gSes3NBRwtAnKxlsDB1G52Ox_8W.dhzN5QDL3ADM1czW}
### 2. Program and absolute paths
This challenge teaches accessing files within a directory, in this case the path is /challenge/run.
>Flag: pwn.college{UzLL2aJBKuZDqySNOS0etfXnlbu.dVDN1QDL3ADM1czW}
### 3. Position thyself
This challenge teaches changing directories with the cd command. In this case, /challenge/run needs to be invoked from the /var directory.
>Flag: pwn.college{smMrtSlvgnI5KcoJ9yofE4VyKEr.dZDN1QDL3ADM1czW}
### 4. Position elsewhere
This challenge teaches changing directories with the cd command. In this case, /challenge/run needs to be invoked from the /etc/apt/sources.list.d directory.
>Flag: pwn.college{4BFgDAQRwIIEsEV0KarB5THjQOw.ddDN1QDL3ADM1czW}
### 5. Position yet elsewhere
This challenge also teaches changing directories with the cd command.
>Flag: pwn.college{MATWUTKCptQuQAf6fX1XjchNQsl.dhDN1QDL3ADM1czW}
### 6. Implicit Relative Paths, from /
This challenge teaches relative paths. In this case, /challenge/run needs to be invoked from the / directory.
>Flag: pwn.college{YSNPPDJdh1HmRxK8BnffVqF6Cjc.dlDN1QDL3ADM1czW}
### 7. Explicit Relative Paths, from /
This challenge teaches explicit relative paths. In this challenge, the key is given by ./challenge/run, a relative path.
>Flag: pwn.college{kKLRcO7BRnY_sPDkndYyzLn-ppB.dBTN1QDL3ADM1czW}
### 8. Implicit relative path
In this challenge, ./run needs to be called explicitly, to execute it in the current directory.
>Flag: pwn.college{MfLpsLerpCR7TZD56L3mAL2iVwe.dFTN1QDL3ADM1czW}
### 9. Home sweet home
This challenge provides information about the home directory, as well as the *~* symbol, which is a shorthand for the home directory. It introduces file creation in the home directory using ~, where the flag is written.
>Flag: pwn.college{wrNWDEByQ-uktqOSeogLq0ojxkT.dNzM4QDL3ADM1czW}
