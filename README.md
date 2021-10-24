# Kotlin-Build_System-SublimeText
Build System for sublime text Linux user

******///NOTE ENVIRONMENTAL VARIBLE SHOULD BE SAME AS BELOW MENTIONED ///******

//environmental varible

* download kotlin zip in offical site
* extract folder and open folder which names like "kotlinc" (rename) ->kotlin
* move the folder to /usr/local/bin/(paste here)
* set environmental variable in three format
    //open terminal
    1)export KOTLIN_HOME=/usr/local/bin/kotlin &&export PATH=$PATH:$KOTLIN_HOME/bin 
    2)nano ~/.bashrc file  
    //-->go to end of the file and paste
    export KOTLIN_HOME=/usr/local/bin/kotlin
    export PATH=$PATH:$KOTLIN_HOME/bin 
    //give ctrl o & ctrl x to save and close
    3)sudo nano /etc/profile.d/kotlin.sh
    //paste this varible
    export KOTLIN_HOME=/usr/local/bin/kotlin 
    export PATH=$PATH:$KOTLIN_HOME/bin 
    //give ctrl o & ctrl x to save and close
  
*sudo reboot

//Sublime text Build System
* Open files -> .config/sublime-text/Packages/User
* And paste the below two file in the user folder
* Create a input.txt and output.txt file in kotlin programing folder(workspace)

