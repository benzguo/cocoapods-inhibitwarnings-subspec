**tl;dr:** this Podfile produces warnings:
```
source 'https://github.com/Cocoapods/Specs.git'

platform :ios, '8.0'

pod 'FormatterKit/TimeIntervalFormatter', '~> 1.5.0', :inhibit_warnings => true
```

this Podfile does not:
```
source 'https://github.com/Cocoapods/Specs.git'

platform :ios, '8.0'

pod 'FormatterKit', '~> 1.5.0', :inhibit_warnings => true
```
