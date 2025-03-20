## RESUTL TESTING DHT11 

**1. main.c**

![1](result/1.png)


**2. dht11.c**

How to Add the **`dht11.c`** File:

* **Locate the Library:**
  * In your project structure, navigate to **`DHT11/main`** to find the **`dht11.c`** file.

* **Include the Library in Your Code:**
  * Open the source file (e.g., main.c) where you want to use the DHT11 functionalities.
  * At the top of your source file, add the following line:

```c
#include "dht11.h"  
```

* **Rebuild the Project:**

  * After including the library, save your changes.
  * Rebuild the entire project to ensure that the new library is linked correctly. This can usually be done by clicking on the **"Build"** or **"Run"** option in your IDE.

![2](result/2.png)

Following these steps will enable you to utilize the DHT11 sensor functions provided by the **`dht11.c`** library in your code.


**3. dht11.h**

How to Add the **`dht11.h`** File:

* **Locate the Library:**
  * Find the **`dht11.h`** file in the project explorer under the **`DHT11/main/dht11`** directory.

* **Include the Library in Your Code:**
  * Open the main source file (e.g., **`main.c`** or another relevant file).
  * At the top of your file, add the following line to include the DHT11 header:

```c
#include "dht11.h"  
```

* **Rebuild the Project:**

  * Save your changes after including the header.
  * Rebuild your project by selecting the **`"Build"`** option in your IDE to ensure the new library is linked properly.

![3](result/3.png)

By following these steps, you will enable the use of the DHT11 sensor functions provided in the **`dht11.h`** library within your project.

**4. CMakeLists.txt**

Adding **`dht11.c`** Library to the **`CMakeLists.txt`** for Project Configuration

* Steps to Add the **`dht11.c`** File:
 * **Locate the `CMakeLists.txt`:**
   * In the project explorer, navigate to **`DHT11/main`** and click on the **`CMakeLists.txt`** file.
  

  

