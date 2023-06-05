Find Selected Image
===================

In this activity, you will learn to find the filter selected by the user on the camera feed.

<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10495566/readingvideo.gif" width = "480" height = "320">


Follow the given steps to complete this activity:

1. Flag a variable for item selected from the filters menu

* Open the main.py file.

* Declare a variable `menuChoice` and set it value as `-1`  .

    `menuChoice = -1`


* Write an `if` condition to check if the `indexFingerTop[1]` is less than `xIncrement`, then declare `i` and set it to 0.

    `if (indexFingerTop[1] < xIncrement):`

        `i = 0`

* While the `xIncrement*i` is less than or equal to `wWidth` check if `indexFingerTop[0]` is less `wWidth` 
        
    `while (xIncrement*i <= wWidth):`

        `if (indexFingerTop[0] < xIncrement*i):`

            `menuChoice = i-1`

* Set `isImageSelected` flag variable to `true` to show that image can be dragged now.

    `isImageSelected = True` 

    `break`
    
    `i = i+1`

* Save and run the code to check the output.






