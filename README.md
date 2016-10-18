# Description
Native Android Titanium module to detect Soft Navigation keys in device.

## Referencing the module in your Titanium Mobile application ##

Simply add the following lines to your `tiapp.xml` file:
    
    <modules>
        <module platform="android">com.arjun.navigationkey</module>
    </modules>
    
## Accessing the module from JavaScript code

### Loading the module

In order to access the module from JavaScript, you should do the following:
```
if (require('com.arjun.navigationkey').isNavigationKeyAvailable) {
  Ti.API.debug("Has a Software button");
} else {
  Ti.API.debug("Has a Hardware button");
}
```
