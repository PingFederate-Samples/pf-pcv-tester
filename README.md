#pf-pcv-tester

### Overview

PingFederate password credential validator that may be useful for testing purposes, returns a success for any username/password except for a configurable username. Can be used to authentication success and failures in a development environment.


### System Requirements / Dependencies

Requires:
 - PingFederate 7.2.x or higher

 
### Installation
 
1. Compile the plugin in (refer to the [PingFederate server SDK documentation] for details on compiling PingFederate plug-ins)
2. Copy the resulting .jar file to the <pf_home>/server/default/deploy folder (on all nodes and admin instances).
3. Restart PingFederate
 
[PingFederate server SDK documentation]: http://documentation.pingidentity.com/display/PF/SDK+Developer%27s+Guide


### Configuration

Once the plug-in has been deployed and the PingFederate instance restarted, launch the PingFederate admin console:

1. Create a new password credential validator instance under: Authentication > Password Credential Validators
2. Name the instance and select the appropriate validator from the "type" list
3. Refer to the inline documentation to configure the validator


### Disclaimer

This software is open sourced by Ping Identity but not supported commercially as such. Any questions/issues should go to the Github issues tracker or discuss on the [Ping Identity developer communities] . See also the DISCLAIMER file in this directory.

[Ping Identity developer communities]: https://community.pingidentity.com/collaborate