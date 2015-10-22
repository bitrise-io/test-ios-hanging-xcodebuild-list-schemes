# test-ios-hanging-xcodebuild-list-schemes

A test project which demonstrates a setup which make `xcodebuild -list -project ./HockeyDemoWithLib.xcodeproj` to hang, indefinitely


It's quite hard to reproduce, as it seem the hierarchy of folders, or the contents of the folders also matter.

You can find a project which demonstrates this issue at: https://github.com/bitrise-io/HockeyKit
