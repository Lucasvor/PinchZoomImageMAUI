# PinchZoomImageMAUI

Zoom in on the image using a pinch gesture with your fingers.

MAUI makes it easy to zoom in and out on your images.


 ###### This is the component, works on iOS, Android, Windows and MAC
 
 **NuGet**

|Name|Info|
| ------------------- | ------------------- | 
|PinchZoomImageMAUI|[![NuGet](https://buildstats.info/nuget/PinchZoomImageMAUI)](https://www.nuget.org/packages/PinchZoomImageMAUI/)|

 

PinchZoomImage is a MAUI library.

## Setup / Usage

Does not require additional configuration. Just install the package in the shared project and use.

You just need to add the reference in your xaml file.

```csharp
  xmlns:pinch="clr-namespace:PinchZoomImageMAUI;assembly=PinchZoomImageMAUI"  
```

Control

Use with the image control

```csharp
       <pinch:PinchZoom>
           <Image
               Aspect="AspectFit"
               HeightRequest="185"
               SemanticProperties.Description="dot net bot in a race car number eight"
               Source="dotnet_bot.png" />
       </pinch:PinchZoom> 
```

The complete example can be downloaded here: 

Base on package with some improvements: https://github.com/TBertuzzi/Bertuzzi.MAUI.PinchZoomImage