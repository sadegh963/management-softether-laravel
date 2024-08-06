# management-softether-laravel
management softether vpn for laravel

## Installation

To install the package, you can use Composer:

```sh
composer require sadegh963/management-softether-laravel
```
### list errors

```c#
ERR_UNKNOWN				An unknown error occurred.
ERR_0					No error.
ERR_1					Connection to the server failed. Check network connection and make sure that address and port number of destination server are correct.
ERR_2					Protocol error occurred. Error was returned from the destination server.
ERR_3					Connection has been disconnected.
ERR_4					Protocol error occurred.
ERR_5					A client which is non-SoftEther VPN software has connected to the port.
ERR_6					The command has been canceled by user.
ERR_7					The server denied the specified auth type.
ERR_8					The specified Virtual Hub does not exist on the server.
ERR_9					User authentication failed.
ERR_10					The specified Virtual Hub is currently stopped. Wait for a while and then reconnect.
ERR_11					The VPN session has been deleted. It is possible that either the administrator disconnected the session or the connection from the client to the VPN Server has been disconnected.
ERR_12					Access has been denied.
ERR_13					Time-out occurred during VPN session communication. It is possible the connection from the client to the VPN Server has been disconnected.
ERR_14					Protocol number is invalid.
ERR_15					There are too many TCP/IP connections.
ERR_16					There are too many sessions connected to either the destination server or Virtual Hub.
ERR_17					Connection to proxy server failed.
ERR_18					An error occurred on the proxy server.
ERR_19					User authentication failed on the proxy server.
ERR_20					There are too many sessions by the same user. Other person might be connected to the Virtual Hub as the same user.
ERR_21					A license error occurred on the VPN Server. Contact the VPN Server's administrator.
ERR_22					Cannot access the Virtual Network Adapter device driver. Check the Virtual Network Adapter is installed and make sure that it has not been disabled.
ERR_23					An internal error occurred.
ERR_24					Access to either the smart card or USB hardware token device failed.
ERR_25					The PIN code is incorrect.
ERR_26					The specified certificate is not stored on either the smart card or the USB hardware token device.
ERR_27					The specified private key is not stored on either the smart card or the USB hardware token device.
ERR_28					Write operation to the smart card or USB hardware token device failed.
ERR_29					Object not found.
ERR_30					A Virtual Network Adapter with the specified name already exists. Specify a different name.
ERR_31					Installation of the Virtual Network Adapter device driver failed.
ERR_32					You cannot use the specified name for a Virtual Network Adapter device.
ERR_33					Unsupported.
ERR_34					VPN Connection Setting with the specified name already exists.
ERR_35					The specified VPN Connection Setting is currently connected.
ERR_36					The specified VPN Connection Setting does not exist.
ERR_37					The specified VPN Connection Setting is not connected.
ERR_38					Invalid parameter.
ERR_39					Error occurred on smart card or USB hardware token.
ERR_40					Although authentication of smart card or USB hardware token was selected, but the device to be used has not been selected. Select from the Smart Card menu of Connection Manager.
ERR_41					The specified Virtual Network Adapter is being used by at least one VPN Connection Setting. \r\nEither delete the VPN Connection Setting that is using this Virtual Network Adapter or change Virtual Network Adapter that this VPN Connection Setting is using.
ERR_42					Cannot find the Virtual Network Adapter that the specified VPN Connection Setting is using. \r\nMake sure this Virtual Network Adapter exists. Also make sure the Virtual Network Adapter device has not been disabled. \r\n\r\nIf you cannot resolve the problem, either change the Virtual Network Adapter being used by this VPN Connection Setting or create a new Virtual Network Adapter with the same name.
ERR_43					The Virtual Network Adapter used by the specified VPN Connection Setting is already being used by another VPN Connection Setting. \r\nIf there is another VPN Connection Setting that is using the same Virtual Network Adapter, disconnect that VPN Connection Setting.
ERR_44					The Virtual Network Adapter being used by the specified VPN Connection Setting has been disabled. \r\nBefore using this VPN Connection Setting, enable the Virtual Network Adapter.
ERR_45					The specified value is invalid.
ERR_46					The connection destination is not a cluster controller.
ERR_47					Trying to connect.
ERR_48					Connection to the cluster controller failed.
ERR_49					The cluster controller was unable to assign a new session on a cluster.
ERR_50					Unable to manage the Virtual Hub of the cluster member server.
ERR_51					The user's password used to connect was blank so the connection from remote is prohibited. Blank password can be allowed only to connections from the VPN Server's localhost (127.0.0.1).
ERR_52					Not enough privileges.
ERR_53					Specified listener not found.
ERR_54					The listener of the specified port number already exists.
ERR_55					This is not a cluster member server.
ERR_56					The specified encryption algorithm name is not supported.
ERR_57					The Virtual Hub with the specified name already exists on the server.
ERR_58					There are too many registered Virtual Hubs. No more can be created. Delete the old Virtual Hubs.
ERR_59					The Cascade Connection with the specified name already exists.
ERR_60					A Cascade Connection cannot be created on a server on a cluster.
ERR_61					The specified Cascade Connection is offline. 
ERR_62					There are too many access lists.
ERR_63					There are too many users.
ERR_64					There are too many groups.
ERR_65					The specified group does not exist.
ERR_66					The user with the specified name already exists on the Virtual Hub.
ERR_67					The group with the specified name already exists on the Virtual Hub.
ERR_68					A user with the specified name exists on the server but the type of authentication is not password authentication. Unable to change the password.
ERR_69					The user name or old password you entered is incorrect. Note that the password is case-sensitive.
ERR_70					Saitama.
ERR_71					SoftEther has temporarily stopped the current distribution by order of the Japan Ministry of Economy Trade and Industry.
ERR_72					SoftEther has temporarily stopped the current distribution by order of the IPA.
ERR_73					Unable to disconnect the Cascade Connection's session. To delete the session, stop the Cascade Connection.
ERR_74					The VPN Connection Setting for connection with the VPN Server is incomplete. At first you have to complete the VPN Connection Setting for connection with the VPN Server.
ERR_75					VPN Connection to the VPN Server has already started.
ERR_76					Not connected to the VPN Server.
ERR_77					The specified X509 certificate file does not contain a RSA 1024 bit or 2048 bit public key. SoftEther VPN software supports only RSA 1024 bit or 2048 bit certificates.
ERR_78					Unable to disconnect the SecureNAT session. To delete the session, stop the SecureNAT function.
ERR_79					Cannot enable the SecureNAT in a clustering environment.
ERR_80					The SecureNAT is not operating.
ERR_81					This VPN Connection session to the VPN Server has been disconnected by the firewall device installed by the network administrator. Contact the network administrator.
ERR_82					Unable to disconnect the Local Bridge session. To delete the session, stop the Local Bridge.
ERR_83					The Local Bridge is not operating.
ERR_84					Local Bridge cannot be used by the destination VPN Server. Refer to online help or other documentation for the setting method when using Local Bridge on the VPN Server you are using.
ERR_85					Unable to trust the certificate provided by the destination server. The setting to always verify the server certificate is enabled in the VPN Connection Settings. Either register a root certificate that can be trusted or register a individual certificate.
ERR_86					The product code of the destination server is incorrect. It is not possible to connect from this client.
ERR_87					The client and server version is different. Update the software.
ERR_88					Failed to add a capture device. A same capture device might be already registered.
ERR_89					Unable to connect to the destination server from this client. A special client software is required.
ERR_90					The specified capture device is not registered.
ERR_91					Unable to disconnect the Virtual Layer 3 Switch session. To delete the session, stop the Virtual Layer 3 Switch.
ERR_92					A Virtual Layer 3 Switch with the specified name already exists. Specify a different name.
ERR_93					Specified Virtual Layer 3 Switch not found.
ERR_94					The specified name is invalid. Check if the name contains characters that cannot be used.
ERR_95					Failed to add the Virtual Layer 3 interface. Please check that the parameters are valid. Also please make sure that the Virtual Layer 3 switch is stopped. Adding or deleting interfaces are unable when the Virtual Layer 3 switch is running.
ERR_96					Failed to delete the Virtual Layer 3 interface. Please check that the parameters are valid. Also please make sure that the Virtual Layer 3 switch is stopped. Adding or deleting interfaces are unable when the Virtual Layer 3 switch is running.
ERR_97					The Virtual Layer 3 interface that is connecting to the destination Virtual Hub of the specified Virtual Layer 3 interface already exists in the Virtual Layer 3 Switch. No more than one Virtual Layer 3 interface that connects to the same Virtual Hub can be defined in a Virtual Layer 3 Switch.
ERR_98					Failed to add routing table entry. Please check that the parameters are valid. Also please make sure that the Virtual Layer 3 switch is stopped. Adding or deleting routing table entries are unable when the Virtual Layer 3 switch is running.
ERR_99					Failed to delete routing table entry. Please check that the parameters are valid. Also please make sure that the Virtual Layer 3 switch is stopped. Adding or deleting routing table entries are unable when the Virtual Layer 3 switch is running.
ERR_100					The specified routing table entry already exists.
ERR_101					The client clock and the server clock are not synchronized with each other. Check the time settings.
ERR_102					Unable to start this Virtual Layer 3 Switch. \r\n\r\nTo start the Virtual Layer 3 Switch, at least 1 virtual interface must be defined in the Virtual Layer 3 Switch.
ERR_103					Not enough Client Connection Licenses on the destination VPN Server. Contact the server administrator.
ERR_104					Not enough Bridge Connection Licenses on the destination VPN Server. Contact the server administrator.
ERR_105					Due to current technical difficulties, the destination VPN Server is not receiving the connection. Either wait a while, or contact the VPN Server administrator requesting that the server log file be checked.
ERR_106					The destination VPN Server's certificate has expired. Contact the VPN Server's administrator.
ERR_107					A connection has been requested in Monitoring Mode. But the security policy for the connecting user does not permit Monitoring Mode.
ERR_108					A connection has been requested in Bridge / Router Mode. But the security policy for the connecting user forbids both bridge mode and router mode.
ERR_109					A connection from a client IP address has been denied by the Source IP Restriction List of the Virtual Hub.
ERR_110					There are too many items.
ERR_111					Out of memory.
ERR_112					The specified object already exists.
ERR_113					A fatal error occurred. It is possible that the program operation is unable to continue.
ERR_114					The destination VPN Server has detected a software license violation. Connection is refused. Contact the VPN Server's administrator.
ERR_115					The destination VPN Server has connected via the Internet to an important server provided by SoftEther VPN Project and cannot validate a license. Either wait a while, or contact the VPN Server administrator requesting that the server log file and the Internet connection status of the server itself be checked.
ERR_116					A software license violation has been detected on the client side. Connection is refused.
ERR_117					The command or file name is incorrect.
ERR_118					The license key is incorrect.
ERR_119					No valid product license is registered on the VPN Server. Contact the VPN Server's administrator.
ERR_120					The product license required for the VPN Server to operate as a cluster is not registered. Contact the VPN Server's administrator.
ERR_121					This VPN Connection Setting has been installed using the "Web Installer Creation Kit" or "Simple Installer Creation Kit". The destination server is not an edition that supports the SoftEther VPN 2.0 Administration Pack. Contact the system administrator or person who created the installer.
ERR_122					With the VPN Server SDK for .NET, it is only possible to connect to the SoftEther VPN Server edition that supports the SoftEther VPN 2.0 Administration Pack. The destination VPN Server is not an edition that supports the SoftEther VPN 2.0 Administration Pack. Contact the system administrator.
ERR_123					Beta Version Software on the destination server is expired. Contact to system administrator of the server to download a new beta version or full version from http://selinks.org/.
ERR_124					The VPN connection to VPN Server is refused at server side.
```
