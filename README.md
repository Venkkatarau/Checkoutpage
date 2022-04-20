# WebView Containers

Fancy container package lets you add a beautiful gradient container to your Flutter app.

## Installation 

1. Add the latest version of package to your pubspec.yaml (and run`dart pub get`):
```yaml
dependencies:
  flutter_web_checkoutpage: ^1.0.0
```
2. Import the package and use it in your Flutter App.
```dart
import 'package:flutter_web_checkoutpage/flutter_web_checkoutpage.dart';
```

<hr>

<table>
<tr>
<td>

```dart

class _CheckoutPageState extends State<CheckoutPage> {
  @override
  Widget build(BuildContext context) {
    return SafeArea(
        child: Scaffold(
      body: WebView(
        initialUrl: widget.url,
        javascriptMode: JavascriptMode.unrestricted,
      ),
    ));
  }
}

```


## Next Goals

 - [x] Add onTap for functions.
 Now, you can specify the onTap and specify a function.
 
 - [x] Change font and color style for text.
 Change color by specifying `textcolor` and `subtitlecolor` properties.
 
 - [ ] Add more containers to the package.
