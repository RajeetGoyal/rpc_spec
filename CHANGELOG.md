# RPC Spec 4.5.0


### Breaking Changes


### Modifications
- [0031](https://github.com/smartdevicelink/sdl_evolution/issues/97): Added `PROJECTION` element to `AppHMIType` 
- [0049](https://github.com/smartdevicelink/sdl_evolution/issues/144) : Added `CANCEL` element to `TouchType`
- [0055] : Added `DATA_NOT_AVAILABLE` to `Result`
- [0058] : Added `videoStreaming ` to `HMICapabilities`
- [0060] , [0076] : Added `EN-IN`, `TH-TH`, `EN-SA`, `HE-IL`, `RO-RO`, `UK-UA`,`ID-ID`, `VI-VN`, `MS-MY`, and `HI-IN` to elements to `Language` 

### New RPCs, Structs, and Enums 

#### Functions
- [0055] , [0058] : `GetSystemCapability`

#### Structs
- [0055] , [0058] : `SystemCapability`
- [0055] : `NavigationCapability`
- [0055] : `PhoneCapability`
- [0058] : `VideoStreamingCapability`
- [0058] : `VideoStreamingFormat`

#### Enums
- [0055] , [0058] : `SystemCapabilityType`
- [0058] : `VideoStreamingCodec`
- [0058] : `VideoStreamingProtocol`


[0055]:https://github.com/smartdevicelink/sdl_evolution/issues/166
[0058]:https://github.com/smartdevicelink/sdl_evolution/issues/176
[0060]:https://github.com/smartdevicelink/sdl_evolution/issues/178

[0076]:https://github.com/smartdevicelink/sdl_evolution/issues/220