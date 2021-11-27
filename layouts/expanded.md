# Expanded

| Title | Description |
| :---: | :---------: |
|       |             |
|       |             |

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
        body: Column(
          children: [
            Expanded(
              flex: 1,
              child: Container(
                color: Colors.red,
              ),
            ),
            Expanded(
              flex: 1,
              child: Column(
                children: [
                  Expanded(
                    flex: 1,
                    child: Container(
                      color: Colors.amber.shade900,
                    ),
                  ),
                  Expanded(
                    flex: 1,
                    child: Container(
                      color: Colors.amber.shade500,
                    ),
                  ),
                  Expanded(
                    flex: 1,
                    child: Container(
                      color: Colors.amber.shade300,
                    ),
                  ),
                ],
              ),
            ),
            Expanded(
              flex: 1,
              child: Container(
                color: Colors.blue,
              ),
            ),
            Expanded(
              flex: 1,
              child: Row(
                children: [
                  Expanded(
                    flex: 1,
                    child: Container(
                      color: Colors.amber.shade900,
                    ),
                  ),
                  Expanded(
                    flex: 2,
                    child: Container(
                      color: Colors.amber.shade500,
                    ),
                  ),
                  Expanded(
                    flex: 1,
                    child: Container(
                      color: Colors.amber.shade300,
                    ),
                  ),
                ],
              ),
            ),
          ],
        ),
      ),
    );
  }
}
```

![](<../.gitbook/assets/Screenshot from 2021-11-27 17-09-39.png>)

