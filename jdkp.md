## JDKP
JDKP is a Java based Application, to download point data from your EQdkp Plus installation and transform it into a game-specific format.

It uses the Plus Exchange API from EQdkp Plus to export the point data from your local EQdkp Plus.

Currently, the following Game-Addons are supported:
* WoW GetDKP (Classic Lua)

### Download
| Syntax | Description |
| --- | ----------- |
| Header | Title |
| Paragraph | Text |

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
