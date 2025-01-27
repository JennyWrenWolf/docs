---
title: FieldServiceLite
keywords: 

status: Complete
created: 20210915
updated: 20211004
createdby: JennyWrenWolf
updatedby: JennyWrenWolf

Note: New term - field service ticket and service board? 9/29 wording
---
[Home](../Index.md) > [Glossary](./Index.md)

# Field Service Lite
## Definition
NuvIoT provides a program called *Field Service Lite*.  It offers a basic implementation for core features of a typical Field Service Application and was designed to be integrated with more robust Field Service Applications. 

When a [Device](./Device.md) generates an [Error Code](./ErrorCode.md), *Field Service Lite* creates a [Service Ticket](./ServiceTicket.md) providing information about the error.  The [Service Ticket](./ServiceTicket) is then sent to a [Service Board](./ServiceBoard.md) to be managed.  

<br>
<br>
<br>

## Example
The bearing on a *Plymouth IoT Conveyor Belt* reached a temperature of 425°, creating an `overheat` [Error Code](./ErrorCode.md).  This generated a [Service Ticket](./ServiceTicket.md) in *Field Service Lite* and posted the ticket on the floor manager's [Service Board](./ServiceBoard.md).

<br>
<br>
<br>

# Related Terms
- [Device](./Device.md)
- [Error Code](./ErrorCode.md)
- [Service Board](./ServiceBoard.md)
- [Service Ticket](./ServiceTickets.md)