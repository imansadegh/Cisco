# Cisco ISE (v4.0)
## CCNP_Security(300-715 SISE)
### How Can I install it?
you can install on EVE-ENG

### ISE is an AAA server
 A: Authentication (user and password)
 A: Authorization (level of permittion)
 A: Accounting (capture your doing)

 AAA servers work with 2 protocol
 - TACACS+<br>
   -for Device Administration<br>
   -TCP<br>
   -all packets encrypted between ACS server and router<br>
   -powerfull in Authorization<br>
   -ideal for Network admins(because can manage commands in routers and switchs)<br>
 - RADIUS<br>
   -for Network Access<br>
   -UDP<br>
   -only the password is encrypted<br>
   -powerful in accounting<br>
   -ideal for endpoints users or NAC(Network access control)<br>
