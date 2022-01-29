# Wordle-Solver (Kotlin)
Wordle Solver is a useful script to help players gain an advantage at Wordle, the new online word game catching on so fast on Twitter. Use this Kotlin script to find the daily Wordle answer before your buddies and show off your skills on social media.

# How to use

![s](https://user-images.githubusercontent.com/98500513/151640054-3efcab10-f342-4d55-b146-5e8a0342dd92.png)

Example 1, at Tester.kt

Green letters are N A L

Yellow letters are A N L

Grey letters is U N I L O Y

```
    var green = listOf("", "", "n", "a", "l") //  is correct and in the correct position
    var yellow1 = listOf("a", "n", "", "", "") // answer but not in the right position
    var yellow2 = listOf("", "l", "", "", "")
    var yellow3 = listOf("", "", "", "", "")

    var grey = "unioyl"   //  it is not in the answer at all
```
Run it, You will get result 'banal'

