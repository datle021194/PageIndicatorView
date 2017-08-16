# PageIndicatorView
IOS Swift Page Indicator View

![Alt text](https://github.com/datle021194/PageIndicatorView/blob/master/PageIndicatorView.png?raw=true "PageIndicatorView")

# Installation
Add PageIndicatorView.swift and HexStringToColor.swift to your project

# Usage
```swift
self.indicatorView.layoutIfNeeded()
self.pageIndicator = PageIndicatorView(frame: self.indicatorView.bounds, numberOfIndicator: self.maximumPage)
self.indicatorView.addSubview(self.pageIndicator)
```
# Custom color
```swift
self.pageIndicator.setColor(hexString: "#000000FF")
self.pageIndicator.setCurrentColor(hexString: "#8CC63EFF")
```

# License and Authorship
Released under the MIT License. Copyright 2017 Dat. Please open issues on GitHub.
