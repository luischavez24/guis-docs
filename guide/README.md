# Markdown for any language

## Java coding example
``` java
package com.guis.examples;
import java.util.List;
import java.util.ArrayList;

@Controller
@RequestMapping('/example')
public class ExampleController {
  public List<String> getExamples(){
    List<String> examples = new ArrayList<String>();
    examples.add("Hi");
    examples.add("welcome");
    return examples;
  }
}

```

## C# coding example
``` csharp
using System.Threading.Task;
namespace Guis.Testing {
  public class AsyncMethods {
    ...
    public async Task<int> GetIntsFromDatabase() {
      return await service.GetInts();
    }
  }
}
```
## Javascript coding example

``` javascript
import axios from 'axios';

async function getItems() {
  return await axios.get('https:/example.com/api/items');
}
export default {
  getItems
}
```

## Python coding example

``` python
# Generating number

numbers = [i for i in range(100)]

for num in numbers:
  print(f"Number {num}!")
```

## Dart coding example

``` dart
class Example {
  Future makeAsyncRequest() async {
    return await apiRequest();
  }
}
```

## Lisp coding example

``` lisp
(defun someFunction ()
  "Docs String"
  body
)
```
## Languages support 

| Languages  | Support |
| ---------- | ------- |
| Java       | true    |
| Dart       | true    |
| CSharp     | true    |
| Lisp       | true    |
| Javascript | true    |
| Python     | true    |