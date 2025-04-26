# comp9021---assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [COMP9021 – Assignment 1 Solved](https://www.ankitcodinghub.com/product/comp9021-assignment-1-solved-6/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;108572&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP9021 - Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
1. General matters

1.1. Aims. The purpose of the assignment is to:

• let you design solutions to simple problems;

• let you implement these solutions in the form of short python programs;

• practice the use of arithmetic computations, string manipulation, tests, repetitions, lists, tuples, dictionaries, reading from files.

1.3. Assessment. The first two exercises are worth 4 marks each, the third one, 5 marks. For all exercises, the automarking script will let each of your programs run for 30 seconds.

The outputs of your programs should be exactly as indicated.

1

2

2. Pivoting die (4 marks)

Consider the board below, which can be imagined as being infinite, so only a small part is represented. A die is placed on cell number 1 of the board in the position indicated: 3 at the top, 2 at the front (towards cell number 4 of the board), and 1 on the right (towards cell number 2 of the board). Recall that 4 is opposite to 3, 5 is opposite to 2, and 6 is opposite to 1. The die can be moved from cell 1 to cell 2, then to cell 3, then to cell 4…, each time pivoting by 90 degrees in the appropriate direction (to the right, forwards, to the left, or backwards). For instance, after it has been moved from cell 1 to cell 2, 2 is still at the front but 6 is at the top and 3 is on the right.

43

42

41

40

39

38

37 44 45 46 47 48 49 50

21

20

19

18

17 22 23 24 25 26

27

28

29

30

31

7

6

5 8 9 10

11

12

13

1 2

3

4

16 15 14

36 35 34 33 32

Write a program, stored in a file named pivoting_die.py, that prompts the user for a natural number N at least equal to 1, and outputs the numbers at the top, the front and the right after the die has been moved to cell N.

Here is a possible interaction.

$ python3 pivoting_die.py

Enter the desired goal cell number: A

Incorrect value, try again

Enter the desired goal cell number:

Incorrect value, try again

Enter the desired goal cell number: -1

Incorrect value, try again

Enter the desired goal cell number: 0

Incorrect value, try again

Enter the desired goal cell number: 1

On cell 1, 3 is at the top, 2 at the front, and 1 on the right.

$ python3 pivoting_die.py

Enter the desired goal cell number: 29

On cell 29, 3 is at the top, 2 at the front, and 1 on the right.

$ python3 pivoting_die.py

Enter the desired goal cell number: 2006

On cell 2006, 4 is at the top, 1 at the front, and 2 on the right.

3

3. A word game (4 marks)

Write a program, stored in a file named highest_scoring_words.py, that performs the following task.

• Prompts the user to input between 3 and 10 lowercase letters (with possibly whitespace inserted anywhere); if the input contains too few or too many lowercase letters or any character which is neither a lowercase letter nor whitespace, then the program outputs an error message and exits.

• Finds in the file wordsEn.txt, assumed to be stored in the working directory, the words built from the letters input by the user (with the exclusion of any other character) with highest score, if any; the score of a word is defined as the sum of the values of the letters that make up that word, the value of each letter being defined as follows:

a 2 b 5 c 4 d 4 e 1 f 6

g 5 h 5 i 1 j 7 k 6 l 3

m 5 n 2 o 3 p 5 q 7 r 2

s 1 t 2 u 4 v 6 w 6 x 7

y 5 z 7

• Outputs a specific message if there is no such word; otherwise, outputs the highest score and all words with that score, one word per line, with a different introductory message depending on whether there is a unique such word (in which case the introductory message is on the same line as the word) or at least two such words (in which case the introductory message is on a line of its own and all words are preceded with 4 spaces).

Here is a possible interaction.

$ python3 highest_scoring_words.py

Enter between 3 and 10 lowercase letters: abc2ef Incorrect input, giving up…

$ python3 highest_scoring_words.py Enter between 3 and 10 lowercase letters: ab Incorrect input, giving up…

$ python3 highest_scoring_words.py

Enter between 3 and 10 lowercase letters: abcdefghijk Incorrect input, giving up…

$ python3 highest_scoring_words.py

Enter between 3 and 10 lowercase letters: zz zz zz No word is built from some of those letters.

$ python3 highest_scoring_words.py

Enter between 3 and 10 lowercase letters: a a a The highest score is 2.

The highest scoring word is a

$ python3 highest_scoring_words.py

Enter between 3 and 10 lowercase letters: a e i o u The highest score is 8.

The highest scoring words are, in alphabetical order:

iou oui

$ python3 highest_scoring_words.py

Enter between 3 and 10 lowercase letters: prmgroa The highest score is 24.

The highest scoring word is program

4

$ python3 highest_scoring_words.py

Enter between 3 and 10 lowercase letters: a b e o r a t

The highest score is 16.

The highest scoring word is abator $ python3 highest_scoring_words.py

Enter between 3 and 10 lowercase letters: r a m m o x y The highest score is 17.

The highest scoring words are, in alphabetical order:

mayor moray moxa oryx

$ python3 highest_scoring_words.py

Enter between 3 and 10 lowercase letters: eaeo rtsmn The highest score is 17.

The highest scoring words are, in alphabetical order:

matrons transom

5

4. Overlapping photographs (5 marks)

Write a program, stored in a file named perimeter.py, that performs the following task.

• Prompts the user to input the name of text file assumed to be stored in the working directory. We assume that if the name is valid then the file consists of lines all containing 4 integers separated by whitespace, of the form x1 y1 x2 y2 where (x1,y1) and (x2,y2) are meant to represent the coordinates of two opposite corners of a rectangle. With the provided file frames_1.txt, the rectangles can be represented as follows, using from top bottom the colours green, yellow, red, blue, purple, olive, and magenta.

We assume that all rectangles are distinct and either properly overlap or are disjoint (they do not touch each other by some of their sides or some of their corners).

• Computes and outputs the perimeter of the boundary, so with the sample file frames_1.txt, the sum of the lengths of the (external or internal) sides of the following picture.

Here is a possible interaction with the two provided sample files.

$ python3 perimeter.py

Which data file do you want to use? frames_1.txt

The perimeter is: 228

$ python3 perimeter.py

Which data file do you want to use? frames_2.txt

The perimeter is: 9090
