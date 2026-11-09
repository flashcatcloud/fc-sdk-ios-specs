# fc-sdk-ios-specs

CocoaPods specs repository for the [Flashcat iOS SDK](https://github.com/flashcatcloud/fc-sdk-ios).

Add both sources to your `Podfile`. Flashcat pods are published here; their third-party dependencies (such as KSCrash) come from the CocoaPods CDN:

```ruby
source 'https://github.com/flashcatcloud/fc-sdk-ios-specs.git'
source 'https://cdn.cocoapods.org/'

pod 'FlashcatCore'
pod 'FlashcatRUM'
```

When upgrading, run `pod install --repo-update` so that your local copy of this repository includes the new version.

Specs are added by the SDK's release workflow. Do not edit them by hand.
