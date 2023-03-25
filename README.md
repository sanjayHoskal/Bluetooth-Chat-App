# BluetoothChatApplication

#### ABOUT PROJECT

Communication is very important between the people in all areas, why because through 
communication we can share knowledge, exchange ideas, chat with friends etc.,

This Bluetooth Chat Android system project can be installed into various Androids and other 
supported android devices and can be used to send files from node of the system to another 
node of the system. The files or data contained in the files can be sent in the form of bits and 
frames format. The user just needs to have Bluetooth support on their device and send to 
another device via the Bluetooth connection. Two devices can communicate with each other
using this project of Android Bluetooth Chat.

##### Messenger application to share files and text messages using RFCOMM/Socket channel

## DFD

<img src="images/DFD.png"/>


## Screenshots
<table height="650">
  <tr>
    <td valign="top">
      <img src="images/pairinglist.jpeg" width=30%/>
      <img src="images/realme.jpeg" width=30%/>
      <img src="images/passcode verify.jpeg" width=30%/>
    </td>
   </tr>
</table>
<table height="650">
  <tr>
    <td valign="top">
      <img src="images/chat demo 1.jpeg" width=30%/>
      <img src="images/chat demo 2.jpeg" width=30%/>
    </td>
   </tr>
</table>


# Modules

➢ Scanning for other Bluetooth devices

➢ Querying the local Bluetooth adapter for paired Bluetooth devices

➢ Establishing RFCOMM channels/sockets

➢ Connecting to a remote device

➢ Transferring data over Bluetoot

## MODULES DESCRIPTION:

## 2.4.1 Scanning for other Bluetooth devices
This application begins searching for devices as soon as it is opened. Options menu appear 
only after a successful or unsuccessful search is complete. Other options are new message 
alert - vibrate or sound, and refresh rate setting ranging from 30 seconds to three minutes. 
Users can manually refresh the list of users as well. Select a user from the list and use 
Options.

## 2.4.2 Querying the local Bluetooth adapter for paired Bluetooth devices
The Bluetooth Adapter is the entry-point for all Bluetooth interaction. Using this, you can 
discover other Bluetooth devices, query a list of bonded (paired) devices, instantiate a 
Bluetooth Device using a known MAC address, and create a Bluetooth Server Socket to 
listen for communications from other devices. Use this to request a connection with a remote 
device through a Bluetooth Socket or query information about the device such as its name, 
address, class, and bonding state. Represents the interface for a Bluetooth socket (similar to a 
TCP Socket). This is the connection point that allows an application to exchange data with 
another Bluetooth device via InputStream and OutputStream.

## 2.4.3 Establishing RFCOMM channels/sockets
In the socket programming model, a socket represents an endpoint of a communication 
channel. Sockets are not connected when they are first created, and are useless until a call to 
either connect (client application) or accept (server application) completes successfully. Once 
a socket is connected, it can be used to send and receive data until the connection fails due to 
link error or user termination. An RFCOMM Bluetooth Socket used to accept incoming 
connections must be attached to operating system resources with the bind method. bind takes 
in a tuple specifying the address of the local Bluetooth adapter to use and a port number to 
listen on. Usually, there is only one local Bluetooth adapter or it doesn't matter which one to 
use, so the empty string indicates that any local Bluetooth adapter is acceptable. Once a 
socket is bound, a call to listen puts the socket into listening mode and it is then ready to 
accept incoming connections

## 2.4.4 Connecting to a remote device
You must request the BLUETOOTH permission in order to perform any Bluetooth 
communication, such as requesting a connection, accepting a connection, and transferring 
data. Before your application can communicate over Bluetooth, you need to verify that 
Bluetooth is supported on the device, and if so, ensure that it is enabled. you need to ensure 
that Bluetooth is enabled. A dialog will appear requesting user permission to enable 
Bluetooth. Once a connection is made with a remote device for the first time, a pairing 
request is automatically presented to the user. When a device is paired, the basic information 
about that device (such as the device name, class, and MAC address) is saved and can be read 
using the Bluetooth APIs. Using the known MAC address for a remote device, a connection 
can be initiated with it at any time without performing discovery (assuming the device is 
within range).

## 2.4.5 Transferring data over Bluetooth
Check the manual that came with your cellular phone and read the section on Bluetooth 
capabilities to see if your phone has a Bluetooth password. Note down the password. Power 
on your cellular phone and access the "Settings" option in the main menu. Choose the 
"Bluetooth" option if it is immediately available, or choose "Connections" and then 
"Bluetooth." Press the option for "Activate Bluetooth." Enter in the Bluetooth code that you 
noted down before if your phone prompts you for one, or instead enter the standard code of 
"1111" if you don't have your manual and aren't sure what the password is. Repeat the 
process on the second phone. Navigate to the folder on your phone that holds the file you 
want to transfer. Choose the file and then choose the option to "Send." Press the option to 
"Send to Phone" and then press the button to send to a connected Bluetooth phone. Enter in 
the phone number of the other phone if your cell does not prompt you to send to an activated 
Bluetooth phone in range

# CONCLUSION

• There is always a room for improvements in any software package, however 
good and efficient it may be done.

• But the most important thing should be flexible to accept further modification.

• Right now we are just dealing with text communication

### REFERENCE

➢ Android Programming: The Big Nerd Ranch Guide 5th Edition

➢ Java Programming for Android Developers for Dummies

➢ GUI Design for Android Apps

➢ The Busy Coder's Guide to Advanced Android Development
