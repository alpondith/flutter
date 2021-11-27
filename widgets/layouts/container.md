# Container

|       Title       |                                Description                               |
| :---------------: | :----------------------------------------------------------------------: |
| Api Documentation |   [Link](https://api.flutter.dev/flutter/widgets/Container-class.html)   |
|   Official Video  | L[ink](https://www.youtube.com/watch?v=c1xLMaTUWCY\&ab\_channel=Flutter) |

{% embed url="https://www.youtube.com/watch?ab_channel=Flutter&v=c1xLMaTUWCY" %}

### Example 1

```
import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        appBar: AppBar(
          title: Center(
            child: Text(
              "App Bar",
              style: TextStyle(
                color: Colors.black,
              ),
            ),
          ),
          backgroundColor: Colors.amber,
        ),
        body: Container(
          width: double.infinity,
          height: double.infinity,
          color: Colors.amber,
          child: Center(
            child: Text("Hello World!"),
          ),
        ),
      ),
    );
  }
}
```

![](<../../.gitbook/assets/Screenshot from 2021-11-27 13-50-08.png>)
