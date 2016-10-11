# Roman Numerals Converter
#### Problem:
Write a program that reads an input file for Roman numerals and converts them to decimal numbers.

####Sample Input
I  
X  
IV  
DLV  
MCMXXVIII  
MMMCMXCIX  

####Expected Output
I is 1  
X is 10  
IV is 4  
DLV is 555  
MCMXXVIII is 1928  
MMMCMXCIX is 3999  

####Resources
[All about roman numerals](http://www.thecalculatorsite.com/articles/other/roman-numerals-deciphered.php)

#### How to run

#####Unix-like
- Method 1
    - cd into the root directory (tdd-roman-numerals)
    - run '_./gradlew run_'
- Method 2
    - cd into the root directory (tdd-roman-numerals)
    - run './gradlew'
    - run '_./gradlew jar_'
    - cd into the build/libs directory
    - run '_java -jar tdd-roman-numerals-1.0-SNAPSHOT.jar input\_file\_path_'

#####Windows 
- Same as Unix-like but change '_./gradlew_' to '_gradlew.bat_'