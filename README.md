<h5>
Note: This package was just updated on <a href="https://github.com/iamvivekkaushik/OTPTextField">OTPTextField</a> because the author does not accept pull requests.
</h5>

<a href="https://github.com/ahmad-einieh/OTPTextFieldV2">
<img align="left" src="https://raw.githubusercontent.com/iamvivekkaushik/OTPTextField/master/screenshot/logo.png" width="400" height="230" /></a>

<p><h2 align="left">OTP Text Field V2</h2></p>

<h4>A flutter package to create a OTP Text Field widget in your application.</h4>

___

</br>

[![Pub](https://img.shields.io/pub/v/otp_text_field_v2)](https://pub.dev/packages/otp_text_field_v2)


## 📱Screenshots
<p align="center">
<img src="https://raw.githubusercontent.com/iamvivekkaushik/OTPTextField/master/screenshot/screen.png" width="300"/>
</p>
<br>

## ⚙️ Installation

Import the following package in your dart file

```dart
import 'package:otp_text_field_v2/otp_text_field_v2.dart';
```
OR 

```dart
import 'package:otp_text_field_v2/otp_field_v2.dart';
```

## 👨‍💻 Usage

Add `otp_text_field_v2` to your Flutter application's dependencies (for example `flutter pub add otp_text_field_v2`). This package's SDK constraint is Dart `>=2.17.6 <4.0.0`; check the resolved release against your Flutter version. Local contributors can run `flutter pub get` and `flutter test`; these commands were not executed for this documentation refresh.

This is an input widget, not an OTP-generation, SMS-delivery, or server-verification service. Verify submitted codes securely in your backend. Upstream attribution, screenshots, and usage examples are retained.

Use the `OTP Text Field V2` Widget

```dart
OTPTextFieldV2(
            controller: otpController,
            length: 5,
            width: MediaQuery.of(context).size.width,
            textFieldAlignment: MainAxisAlignment.spaceAround,
            fieldWidth: 45,
            fieldStyle: FieldStyle.box,
            outlineBorderRadius: 15,
            style: TextStyle(fontSize: 17),
            onChanged: (pin) {
              print("Changed: " + pin);
            },
            onCompleted: (pin) {
              print("Completed: " + pin);
            },
),
```

For more detail on usage, check out the example provided.

## 🙍🏻‍♂️ Edited BY

* [Ahmad Einieh](https://github.com/ahmad-einieh)

