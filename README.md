# Log4Py
a simple logging library

# Usage
Here is a basic file which includes all functions:
```
from log4py import * # import the library

LOG_FILE_ENABLED(True, "test") # the word True means that everything will be logged to a file. The word test is the name of the log file, you can name it to anything

INFO("test") #Log [INFO]

WARNING("test 2") #Log [WARNING]

ERROR("test 3") #Log [ERROR]

DEBUG("test 4") #Log [DEBUG]

SUCCESS("test 5") #Log [SUCCESS]

```
