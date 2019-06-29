# AAAS API Functions

This respository contains the functions implemented in order to provide and API to interact with the system
It includes several functions that implement a simple GET on the main entities and an special fucntions that allows to obtain the devices and modules installed and send commands to the modules deployed on the edge devices.

**alertFunction**, implementing REST GET service for alerts.

**plantFunction**, implementing REST GET service for telemetry.

**weatherFunction**, implementing REST GET service for telemetry.

**commandFunction**, implementing a GET that provides information about the devices connected to the IoTHub and a post method allowing to invoke the remote methods published by the modules included in the edge.

**statusFunction**, implementing REST GET service for alerts for every device.


