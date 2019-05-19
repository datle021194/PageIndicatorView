# PageIndicatorView
IOS Swift Page Indicator View

![Alt text](https://github.com/datle021194/PageIndicatorView/blob/master/PageIndicatorView.png?raw=true "PageIndicatorView")

# Installation
Add PageIndicatorView.swift and HexStringToColor.swift to your project

# Usage Example
```swift
self.parentView.layoutIfNeeded()
self.pageIndicator = PageIndicatorView(frame: self.parentView.bounds, numberOfIndicator: 5)
self.parentViewView.addSubview(self.pageIndicator)
```
# Custom color
```swift
self.pageIndicator.setIndicatorColor(UIColor.red)
self.pageIndicator.setCurrentIndicatorColor(UIColor.black)
```

# License and Authorship
Released under the MIT License. Copyright 2017 Dat. Please open issues on GitHub.
