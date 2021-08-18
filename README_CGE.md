This is a fork of Effekseer with minimal modifications to build CGE wrapper
library from https://github.com/Kagamma/cge-effekseer .

Linux compilation instructions:

- Install dependencies following https://github.com/effekseer/Effekseer/blob/master/docs/Development/HowToBuild.md#linux .

- Build by `cmake --build .`

- The library you want is in `wrapper/libeffekseer.so` . Copy it to your project like

    ```
    cp -f wrapper/libeffekseer.so ../cge-effekseer/demos/TestEffekseer/
    ```
