# jsonpath_parse
A implement of json path by dart, its functions is similar to [JsonPath](https://github.com/json-path/JsonPath)

## dependencies
```
dependencies:
  jsonpath_parse:
    git: https://github.com/Celeter/jsonpath_parse.git
```

## usage

```dart
import 'package:jsonpath_parse/jsonpath_parse.dart';

JPath jPath = JPath.compile("$..book[1:].price");
print(jPath.search(testMap));

```
