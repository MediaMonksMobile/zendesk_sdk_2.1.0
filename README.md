# Patched Zendesk SDK 2.1.0 for iOS

The original repo: https://github.com/zendesk/zendesk_sdk_ios

This is Zendesk SDK 2.1.0 for iOS patched to work with modular headers (i.e. when `use_modular_headers!` is used in a Podfile). This issue seems to be fixed in 2.1.1, however we cannot use it yet because of Swift 4.2 requirement. It's a new repo instead of a fork, so `pod install` can be more or less fast. 

To use in your Podfile:

	pod 'ZendeskSDK', :git => 'https://github.com/MediaMonksMobile/zendesk_sdk_ios_2.1.0'

---
