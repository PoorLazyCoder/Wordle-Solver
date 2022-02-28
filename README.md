# Wordle-Solver (Kotlin)
A Simple Kotlin Script solve difficult Wordle problems

##
 
Wordle Solver is a useful script to help players gain an advantage at Wordle, the new online word game catching on so fast on Twitter and Facebook. Use this Kotlin script to find the daily Wordle answer before your friends and show off your skills on social media.

##
# How to use


Yellow letters are O S, Green letters are O S E, Grey letter are W R D C L, Then you filter out one words only

![D1](https://user-images.githubusercontent.com/98500513/152036230-0b9ace99-2b62-4c5c-81de-cdbd9afc5736.png)

 
```
    var green =   listOf("", "", "o", "s", "e") //  is correct and in the correct position
    var yellow1 = listOf("", "o", "", "", "s") // answer but not in the right position
    var yellow2 = listOf("", "", "", "", "")
    var yellow3 = listOf("", "", "", "", "")

    var grey = "wrdcl"   //  it is not in the answer at all
``` 
##


Yellow letters are LOLL, Green letters are O D, Grey letter are GVEHTSI, Then you filter out 8 words only

![A1](https://user-images.githubusercontent.com/98500513/151674338-ce06de27-6a69-4498-9ff6-c2dc8024294c.png)

```
    var green =   listOf("", "o", "", "", "d") //  is correct and in the correct position
    var yellow1 = listOf("", "l", "o", "", "l") // answer but not in the right position
    var yellow2 = listOf("", "l", "", "", "")
    var yellow3 = listOf("", "", "", "", "")

    var grey = "gvehtsi"   //  it is not in the answer at all
``` 
##

Yellow letters are ANL, Green letters are NAL, Grey letter are UNIOLY, Then you filter out 7 words only

![B1](https://user-images.githubusercontent.com/98500513/151674487-c5308e05-8e97-492e-8190-0101ad6bb105.png)

```
    var green =   listOf("",  "",  "n", "a", "l") //  is correct and in the correct position
    var yellow1 = listOf("a", "n", "", "", "") // answer but not in the right position
    var yellow2 = listOf("",  "l", "", "", "")
    var yellow3 = listOf("", "", "", "", "")

    var grey = "unioyl"   //  it is not in the answer at all
``` 
##

Yellow letters are AU, Green letters are AUE, Grey letter are VMGS, Then you filter out 6 words only

![C1](https://user-images.githubusercontent.com/98500513/151674574-f4c2800a-8087-434f-b0ca-072ba7812840.png)

```
    var green = listOf("a", "", "u", "", "e") //  is correct and in the correct position
    var yellow1 = listOf("", "a", "", "u", "") // answer but not in the right position
    var yellow2 = listOf("", "", "", "", "")
    var yellow3 = listOf("", "", "", "", "")

    var grey = "vmgs"   //  it is not in the answer at all
``` 
Webpage version is also available https://github.com/PoorLazyCoder/Wordle-Helper-Kotlin-JS


Desktop version is also available https://github.com/PoorLazyCoder/Wordle-Cheat-App

Android version is also available https://github.com/PoorLazyCoder/Wordle-Solver-for-Android


