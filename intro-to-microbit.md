> # Getting started
 
## Introduction @unplugged
Welcome! This tutorial will teach you how to use the micro:bit and this website, Makecode.
 
 
## Step 2 @unplugged
Take a look at the three columns on this screen. There's a simulator on the left, code blocks in the middle, and a workspace to do your coding on the right.
( add .gif showing the three columns)
 
## Step 3 @unplugged
We will start by using the "basic" blocks to program the LED lights on the front of your micro:bit. Together, these lights act kind of like a screen that you can display information and images on.
(add image of micro:bit screen)
 
## Step 4
You have two blocks on your screen already, an "on start" block and a "forever" block.
Let's explore how the "on start" block works.
 
## Step 5
Grab a ``||basic:show string||`` block and place it inside of the ``||basic:on start||`` block.
Change the text to something else, like "Your name".
Notice how the blocks fit together, kind of like puzzle pieces.
 
```blocks
basic.showString("Hi!")
```
## Step 6
Now let's try out the ``||basic:forever||`` block. Select 2 or 3 icons from the "Basic" category and place them in the ``||basic:forever||`` block.
```blocks
 
basic.forever(function () {
   basic.showIcon(IconNames.Heart)
   basic.showIcon(IconNames.Happy)
   basic.showIcon(IconNames.Ghost)
})
```

## Step 7
You can also make your own icon by adding the ``||basic:showLeds||`` block to your code. Give it a try!
 
```blocks
basic.forever(function () {
   basic.showIcon(IconNames.Heart)
   basic.showIcon(IconNames.Happy)
   basic.showIcon(IconNames.Ghost)
   basic.showLeds(`
       # . # . #
       . # # # .
       # # # # #
       . # # # .
       # . # . #
       `)
})
```
 
## Step 8
These images are changing pretty fast. You can slow them down by adding a ``||basic.pause||`` block to your program in between each image block.
 
```blocks
basic.forever(function () {
   basic.showIcon(IconNames.Heart)
   basic.pause(100)
   basic.showIcon(IconNames.Happy)
   basic.pause(100)
   basic.showIcon(IconNames.Ghost)
   basic.pause(100)
   basic.showLeds(`
       # . # . #
       . # # # .
       # # # # #
       . # # # .
       # . # . #
       `)
})
```
 
## Step 9
Now you're ready to download your code! Press the ``|Download|`` button to save the code to your computer.
Watch this youtube video, starting at 6:45, to learn how to move the code from your computer to your micro:bit ( https://www.youtube.com/watch?v=ELGkro0fuf4&list=PLqJUzqgu4WDwo1BbyXDE-pZKiCQCi34b_&index=2&t=0s)


