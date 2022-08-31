# Reliable-data-transfer-protocol-rdt-3.0-

This is an implementation of the reliable data transfer protocol (rdt 3.0). For the sake of simplicity I considered only uni- directional data transfer, but the control information will flow on both directions. You may use the finite state machine (FSM) of the rdt 3.0 to understand all the states, events and actions.  

IMPORTANT: You need to add your IP address in both server and client files(variable name: serverName) before running the scripts  Note: I have implemented stop and wait protocol where only a single packet is in-flight. Furthermore, the size and count of packets to be transferred are configurable(for now, this can only be done by modifying the code.  Will add console configuration option later). I have also assumed a fix timeout period.
