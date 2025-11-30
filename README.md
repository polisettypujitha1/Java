# Java
Everything about java

Reading using Scanner class:

| Method                 | Description                          | Example                         |
| ---------------------- | ------------------------------------ | ------------------------------- |
| `next()`               | Reads a single word (stops at space) | `String w = sc.next();`         |
| `nextLine()`           | Reads a full line including spaces   | `String line = sc.nextLine();`  |
| `nextInt()`            | Reads an integer value               | `int n = sc.nextInt();`         |
| `nextDouble()`         | Reads a double value                 | `double d = sc.nextDouble();`   |
| `nextFloat()`          | Reads a float value                  | `float f = sc.nextFloat();`     |
| `nextLong()`           | Reads a long value                   | `long l = sc.nextLong();`       |
| `nextBoolean()`        | Reads true/false                     | `boolean b = sc.nextBoolean();` |
| `hasNextInt()`         | Checks if next input is an integer   | `if(sc.hasNextInt()) {}`        |
| next().charAt(0)`      | Reads a single character             | `char c = sc.next().charAt(0);` |

we should use nextLine() after 

| Previous Input Method | Should You Use `nextLine()` After It? | Why?                            |
| --------------------- | ------------------------------------- | ------------------------------- |
| `nextInt()`           | ✅ Yes                                 | Leaves newline                  |
| `nextDouble()`        | ✅ Yes                                 | Leaves newline                  |
| `nextFloat()`         | ✅ Yes                                 | Leaves newline                  |
| `nextLong()`          | ✅ Yes                                 | Leaves newline                  |
| `nextBoolean()`       | ✅ Yes                                 | Leaves newline                  |
| `next()`              | ❌ No                                  | Already ignores spaces/newlines |
| `nextLine()`          | ❌ No                                  | Already consumes newline        |
