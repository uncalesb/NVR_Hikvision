# NVR Structure and Message Request
this repo is contain 4 type structures for request and response to NVR Hikvision
1. GetListFile
2. DeviceInfo
3. CameraInfo
4. Download

### GetListFile
is a keyword to get files listed on nvr with start-time and end-time as search parameter.
#### Request Structure
  Source -> REST_Request_FileList.xsd\
  Destination -> NVR_Request_FileList.xsd
### Request Mapping
![alt text](https://github.com/UncalESB/NVR_Hikvision/blob/main/reqmap.JPG)
#### Response Structure
Source -> NVR_Response_FileList.xsd\
Destination -> REST_Response_FileList.xsd
### Response Mapping
![alt text](https://github.com/UncalESB/NVR_Hikvision/blob/main/resmap.JPG)
## you can check the structure for other purposes
