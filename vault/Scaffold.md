---
id: Ug01cG2E73bxtH5TpWxHo
title: Scaffold
desc: ''
updated: 1634045638877
created: 1634045296499
---

## scaffold

```dart
import 'package:flutter/material.dart';

void main() => runApp(const MyApp());

class MyApp extends StatelessWidget {
  const MyApp({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Welcome to Flutter',
      home: Scaffold(
        appBar: AppBar(
          title: const Text('helllo'),
          backgroundColor: const Color(0x00000000),
        ),
        body: const Center(
          child: Text('Hello World'),
        ),
      ),
    );
  }
}
```

![](/assets/images/2021-10-12-21-33-52.png)