# Flutter

## Getting Started

### Prerequisites
  - You should have at least one of the supported IDE listed below:
    * [Android Studio](https://developer.android.com/studio/)
    * [IntelliJ](https://www.jetbrains.com/idea/)
    * [Visual Studio Code](https://code.visualstudio.com/)

### Installing
  1. **Download** Flutter SDK from [here](https://flutter.io/docs/get-started/install/linux).

  2. **Extract** the Flutter SDK:
    * Linux terminal:
  ```
  cd ~/[destination_Directory]
  tar xf ~/[source_Directory]/flutter_linux_v1.0.0-stable.tar.xz
  ```


  3. **Create** the "<span style="color:orange"> *.bash_profile* </span>" file:
      * Navigate to your *Home* directory:
        * Linux terminal:
        ```
        cd $Home
        ```
      * Create new file:
        * Linux terminal:
        ```
        touch .bash_profile
        ```

  4. Add Flutter path to you current path:
    * Linux:

      Add this line to the <span style="color:orange"> *.bash_profile* </span> file using nano or any text editor.
    ```
    export PATH=~/Downloads/flutter/bin:$PATH
    ```
  5. Update current path:
    * Linux terminal:
    ```
    source $HOME/.bash_profile
    ```

### Verification
  * To verify and check dependencies:
    * Linux terminal:
    ```
    flutter doctor
    ```

### IDE extension
  * Once you verfied that flutter is accessable and installed. Start your prefered IDE and install the **flutter** extension.
  * If you do not install the extension, the ***flutter doctor*** command will detect that your IDE does not support **Flutter**.
  * If you install the **flutter** extension, the ***flutter doctor*** will detect that too.
### Note

  - The **.bash_profile** file <span style="color:red"> *does not* </span> have an extension.
  - If you restart your device, you might lose access to the ***flutter*** directory. Just apply **Step #4** again and you should be good to go.
