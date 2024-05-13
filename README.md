## Minimal reproduction of runtime crash 


### To reproduce
- open ios/jumioexpo51.xcworkspace in Xcode
- build & run

App compiles successfully but crashes at runtime with following error:
```
dyld[43248]: Symbol not found: _$s10DatadogRUM0B0V13ConfigurationV15VitalsFrequencyO7averageyA2GmFWC
  Referenced from: <A2B3C359-8F37-377F-B2BE-7D4E13368761> /Users/nk/Library/Developer/CoreSimulator/Devices/5A7780B1-EB10-4018-9DDC-D26560217DD3/data/Containers/Bundle/Application/5753F9ED-C3A6-4785-8FD6-48807B0722CF/jumioexpo51.app/Frameworks/JumioDatadog.framework/JumioDatadog
  Expected in:     <076A1CF9-E027-3FB8-B0BA-E49AA3B59721> /Users/nk/Library/Developer/CoreSimulator/Devices/5A7780B1-EB10-4018-9DDC-D26560217DD3/data/Containers/Bundle/Application/5753F9ED-C3A6-4785-8FD6-48807B0722CF/jumioexpo51.app/Frameworks/DatadogRUM.framework/DatadogRUM

```
