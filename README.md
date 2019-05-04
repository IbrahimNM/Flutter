# Flutter

## Getting Started

### Prerequisites :clipboard:
  - You should have at least one of the supported IDE listed below:
    * [Android Studio](https://developer.android.com/studio/)
    * [IntelliJ](https://www.jetbrains.com/idea/)
    * [Visual Studio Code](https://code.visualstudio.com/)

### Installing :wrench:
  1. **Download** Flutter SDK from [here](https://flutter.io/docs/get-started/install/linux).

  2. **Extract** the Flutter SDK:
      * Linux terminal:
          ```console 
          cd ~/[destination_Directory]
          tar xf ~/[source_Directory]/flutter_linux_v1.0.0-stable.tar.xz
          ```


  3. **Create** the "<span style="color:orange"> *.bash_profile* </span>" file:
      * Navigate to your *Home* directory:
        * Linux terminal:
        ```console
        cd $Home
        ```
      * Create new file:
        * Linux terminal:
        ```console
        touch .bash_profile
        ```

  4. Add Flutter path to you current path:
    
      * Linux:
          
          Add this line to the <span style="color:orange"> *.bash_profile* </span> file using nano or any text editor.
           
          ```console
          export PATH=~/Downloads/flutter/bin:$PATH
          ```
  5. Update current path:
      
      * Linux terminal:
          ```console 
          source $HOME/.bash_profile
          ```

### Verification :white_check_mark:
  * To verify and check dependencies, run the following command:
    
    * Linux terminal:
      ```console
      flutter doctor
      ```

### IDE extension
  * Once you verfied that flutter is accessable and installed. Start your prefered IDE and install the **flutter** extension.
  * If you do not install the extension, the ***flutter doctor*** command will detect that your IDE does not support **Flutter**.
  * If you install the **flutter** extension, the ***flutter doctor*** will detect that too.
### Notes :warning:

  - The **.bash_profile** file <span style="color:red"> *does not* </span> have an extension.
  - If you restart your device, you might lose access to the ***flutter*** directory. Just apply **Step #4** again and you should be good to go.
