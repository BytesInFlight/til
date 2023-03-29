# Windows API Interfaces & Operations

The following table of Windows interfaces and operations are recognized by ExtraHop protocol parsers

| Interface             | Operation               | Description |
| ---------             | ---------               | ----------- |
| drsuapi               |                         |             |
|                       | DRSBind                 |             |
|                       | DRSUnBind               |             |
|                       | DRSCrackNames           |             |
|                       | DRSReplicaSync          |             |
|                       | DRSGetReplInfo          |             |
|                       | DRSDomainControllerInfo |             |
|                       | DRSWriteSPN             |             |
| IRemoteSCMActivator   |                         |             |
|                       | RemoteCreateInstance    | https://learn.microsoft.com/en-us/openspecs/windows_protocols/ms-dcom/fd0682f8-8f5a-4082-830f-861c34db6251 |
| FrsTransport          |                         |             |
|                       | Establish Session       |             |
|                       | Establish Connection    |             |
| IRemUnknown2          |                         |             |
|                       | RemQueryInterface       |             |