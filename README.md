# Weather-App-IOS
Support All devices Iphon


FRAMEWORK 
1) Cocoapods


User Scenarios

1) As a user, i can get current location weather data, if location services and internet connection available
2) As a user, i can pull to refresh current location weather data, if location services and internet connection available
3) As a user, if location services not available and internet connection available, pull to refresh user alert inform me location services not available
4) As a user, if location services not available but internet connection available, i can get last location weather data
5) As a user, if location services not available and no last location weather data but internet connection available, i can search location with Google Autocomplete Place
6) As a user, if location services and internet connection not available and no last location weather data, user alert inform me to allow location services or enable internet connection


## Getting Started

These instructions will get you a copy of the project up and running on your Xcode for development and testing purposes.

### Prerequisites

Cocoapods (Dependency Manager for Xcode Project)

Check Cocoapods already installed in your system.

```
~ gem which cocoapods
```

If it's not installed.

```
~ sudo gem install cocoapods
~ pod setup —verbose
```

Check the pod version

```
~ pod --version
1.3.1
```

#### Pods

* [Alamofire](https://github.com/Alamofire/Alamofire) (Elegant HTTP Networking in Swift)
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) (The better way to deal with JSON data in Swift)
* [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) (A clean and lightweight progress HUD for your iOS and tvOS app)

### Installing

Listed pods already uploaded the github project. You don't need to install them.

```
platform :ios, '9.0'

target 'Clima' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Clima

pod 'SwiftyJSON'
pod 'Alamofire'
pod 'SVProgressHUD'

end


```

If something goes wrong! Updating pod files maybe fix the problem.

In project folder where Podfile is

```
~ cd Developer/iOS/Clima
```


Update  the pods
```
~ pod update
```

## License
Saleh Majidov (https://github.com/salehvm/Weather-App-IOS/blob/master/LICENSE)

## Special Thanks to

Angela Yu . 
