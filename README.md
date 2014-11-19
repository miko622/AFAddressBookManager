AFAddressBookManager
====================
![Pod version](http://img.shields.io/cocoapods/v/AFAddressBookManager.svg?style=flat)
![Pod platform](http://img.shields.io/cocoapods/p/AFAddressBookManager.svg?style=flat)

Get contacts from iOS Address Book by their phone numbers. Works on iOS 6+.

## Installation

### [CocoaPods](http://cocoapods.org)

```ruby
pod 'AFAddressBookManager'
```

### Manually

Copy all files from AFAddressBookManager folder to your project and add the [Address Book framework](http://developer.apple.com/library/ios/#documentation/AddressBook/Reference/AddressBook_iPhoneOS_Framework/).

## Usage

Import `AFAddressBookManager.h` in the class where you want to use it.

### Available methods

Get name (First name and last name) of contact:
```objectivec
+ (NSString *)nameForContactWithPhoneNumber:(NSString *)phoneNumber;
```

Get photo of contact:
```objectivec 
+ (UIImage *)photoForContactWithPhoneNumber:(NSString *)phoneNumber;
```

---

<a href="http://Fogh.tip.me">
  <img
    alt="Tip Me With ChangeTip"
    src="https://cdn.changetip.com/img/logos/tipme_square.png?1"/>
</a>
