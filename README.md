# cs114-assignment-4-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs114-read-these-instructions-repeatedly-until-you-understand-then-begin-your-project-if-something-is-not-clear-ask-a-before-you-begin-a-solved-3/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128312&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS114 Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
1. Log in to GitHub.

2. Fork this repo(sitory). See this video on how to carry out this step and step 3.

3. Clone your fork, using either the web site or the GitHub Desktop client.

4. Checkout your personalized branch, the one with your name and GitHub handle.

â– Introduction â–

Using basic Java graphics via the Processing programming language, create a tic tac toe game in which the user plays against the computer. A short movie of how this assignment should look and behave in its resolved state is available here.

&nbsp;

â– Rules â–

1. The size of the canvas must be 500Ã—500.

2. The computer always plays an â€œXâ€.

3. The user always renders a circle.

4. The computer always starts.

5. Any content that should be reported to the user must be done via Processingâ€™s println() method.

6. Use only the numeric keys 0â€“8 to choose a square. The number 0 must map to the top left corner square, then assign the subsequent numbers across the top and down until you reach the bottom right corner square, which must map to the number 8.

7. When the user presses any key between 0â€“8 that corresponds to a blank square, your program should fill that square with a circle. This is akin to the user taking a turn at the game.

8. Immediately after the user plays, the computer takes its turn.

9. When the user presses any key other than 0â€“8, your program should report a message to the user that they pressed an incorrect key.

10. After the user takes their turn, and if neither the user nor the computer has won, report to the user that the game is still in play.

11. If all squares are played and neither the computer nor the user has won, report to the user that no one has won.

12. When either the user or the computer has won, report this to the user.

13. Subsequent key presses after a game has ended should report to the user that the game has ended.

â– File List â–

This repo contains the following files, all required to carry out this assignment. Before you start working, ensure you understand the role of each file below.

1. tic_tac_toe/tic_tac_toe.pde â€” This is the springboard from where your Processing app will run using setup() and draw().

2. tic_tac_toe/constants.pde â€” All global constants must go in this file.

3. tic_tac_toe/shapes.pde â€” All methods you author to draw shapes, such as â€œOâ€, â€œXâ€, and the tic tac toe board must go in this file.

4. tic_tac_toe/board.pde â€” The logic of your program goes in this file. That is, all methods that will process the logic of your tic tac toe game.

5. .editorconfig â€” The settings in this version of .editorconfig by default indents code by 2 spaces. If you use VS Code instead of Processing to write code for this project, ensure EditorConfig is working before beginning this assignment. (The Processing IDE by default also indents by 2 spaces.)

6. .gitignore â€” Do not modify any .gitignore files.

â– Grading â–

| Item | Points | |—————————————————————————–|:——-:| | Program works according to instructions | 20 | | Code avoids being clever in favor of readability | 20 | | Code is neat and professional | 20 | | Variable naming is logical | 20 | | Comments are used thoughtfully in places where code is not self documenting | 20 |

â– Submission â–

You will need to issue a pull request back into the original repo, the one from which your fork was created for this project. See the Issuing Pull Requests section of this site for help on how to submit your assignment.
