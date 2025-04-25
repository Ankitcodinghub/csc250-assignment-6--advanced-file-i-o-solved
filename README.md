# csc250-assignment-6--advanced-file-i-o-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/csc250-computer-science-2-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127809&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC250 Assignment 6- Advanced File I\/O Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
&nbsp;

Plant File

Write a program that the Plant Shack (Prog 5) can use to create and maintain a file with information for their spring plants. Name the data file plants.dat Employees will use this program to store the plant information. Program 5 can then be updated to read from a file instead of using an initialized array, but you do not need to update program 5, just write this program.

Use a structure with the following fields to hold the information for each structure.

Field Name Description

name string

type Kind

cost float/double

qty_avail int

Use an enumerated type for Kind that contains the following enumerators: FLOWER, VEGETABLE, GRASS, SHRUB

This program will NOT use an array of structures. Instead, your program will use the plants.dat file to store the plant records and a single structure variable to read/write a record as needed.

In main, use the code discussed in the notes to create a new file, only if one does not already exist. If one already exists, it should be used. Open the file for binary input and output. You can open it once in main and pass it into your functions, or you can have each function that needs the file open it in the mode that it needs and close it when finished.

Your program must include a menu with the operations shown below:

1. Add a record. (Read the info for one plant from the user into a single struct variable, and use the write command to add it to the end of the data file.)

2. Print All (print the info for all activities in a table with column headings. Display the Kind as a word.)

3. Edit All Quantities. (move through all of the records in the file, printing the current information and asking the user if they want to change the quantity, if so read the new quantity, updated the data in the structure variable, then back up and write the updated record out over the old record. Do not try to read or write only the quantity field, just read and write the entire record. Hint: Use seekp to move back one record.

4. Exit the program.

Your program should allow the user to make selections until they choose “Exit” which will end the program.

Use a second enumerated type for the operations {ADD, PRINT, EDIT, EXIT}. Use the enumerators in a switch/case statement that calls a function to process each choice.

Your program should be modular. Use a separate function for each option stated above. Your output should be well-organized, neat, and easy to read.

Design your program by completing the CSC 250 Program Design Document. Be sure to include a structure chart for the program, the prototype for each function, a brief description of what each function does and time estimates for program design, coding each function, program testing, and total time.

Write your program and save it in a file named plant_file_xxx.cpp where xxx are your initials. Compile, run and test your program.
