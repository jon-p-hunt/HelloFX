java program called HelloFX (uses JavaFX). 
Usage: . 
C:\> set PATH_TO_FX=C:\Users\account\Downloads\javafx-sdk-25.0.2\lib .
C:\> javac --module-path %PATH_TO_FX% --add-modules javafx.controls HelloFX.java .
C:\> java --module-path %PATH_TO_FX% --add-modules javafx.controls HelloFX .
or .
$ export PATH_TO_FX=/home/account/download/javafx-sdk-25.0.2/lib .
$ javac --module-path $PATH_TO_FX --add-modules javafx.controls HelloFX.java .
$ java --module-path $PATH_TO_FX --add-modules javafx.controls HelloFX .
(><) .
