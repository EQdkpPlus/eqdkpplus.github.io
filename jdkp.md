## JDKP
JDKP is a Java based Application, to download point data from your EQdkp Plus installation and transform it into a game-specific format.

It uses the Plus Exchange API from EQdkp Plus to export the point data from your local EQdkp Plus.

| JDKP  | Required Java-Version  | Supported EQdkp Plus Version  | 
|---|---|---|
| [JDKP 2.0.2 (Jar-File)](packages/jdkp/jdkp_v2.0.2_2.jar)  |  Java JRE 8 |  EQdkp Plus 0.7 - 2.3 |
| [JDKP 2.1.0 (Jar-File)](packages/jdkp/jdkp_v2.1.0_2.jar) | Java SE 9 - 13  | EQdkp Plus 0.7 - 2.3  |
| [JDKP 2.2.0 (Jar-File)](packages/jdkp/jdkp_v2.2.0_2.jar)  | Java SE 13  | EQdkp Plus 2.3  |

### Usage
EQdkp
* Remote - select your used protocol and insert the path of your EQdkp Plus installation
* User - Username, if the access to the point page is restricted (EQdkp Plus < 2.3)
* Pass - Password of the user, if the access to the point page is restricted (EQdkp Plus < 2.3)
* API-Token - Insert the API-Token from the Export-Data Adminpage, if access to the point page is restricted (EQdkp Plus > 2.2)
* Connection Timeout - Insert here an integer, if you have problems with the connection timeout. Default is 10 seconds.

Game
* Format - Select the desired format of the output file
* Local - Insert output file
* Execute (optional) - Insert a path to an executable that should be called after transforming the data

### Help
See [JDKP article at Wiki Dump](https://eqdkpplus.github.io/wiki/wiki/JDKP)

### Source Code
See [https://github.com/EQdkpPlus/tool-jdkp]
