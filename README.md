# V2Ray-VPN-StatusCheck
A simple VPN monitoring program for the V2RayN application. Tracks errors and the current status of the active connection.

The program runs in autostart mode by default.
(You can disable this in the settings.)

1- Monitors the successful creation of a VPN (Virtual Network Card), because sometimes when you enable VPN, the virtual network card is created with errors or not created at all.

2 - Notifies you of connection interruptions.

3- Notifies you of the current VPN status (enabled or disabled).

4- Checks system routes (0.0.0.0 to VPN).

Does not track traffic, does not track physical network cards, does not track the local network.
Does not participate in the operation of V2RayN.
