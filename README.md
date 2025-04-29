# cosc3333-assignment-1-part-2-solved
**TO GET THIS SOLUTION VISIT:** [COSC3333 Assignment 1 part 2 Solved](https://www.ankitcodinghub.com/product/cosc3333-download-the-code-provided-by-the-textbook-in-order-to-complete-this-program-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113656&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COSC3333 Assignment 1 part 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Download the code provided by the textbook in order to complete this program.

This is a two part assignment.

Part I:

Write a program that reads a word (series of ALL CAPITAL LETTERS) from the keyboard and builds a Binary Search Tree out of them. You can use the code in the book to build this tree, but you must incorporate the following additional rules for this assignment.

Although you must follow the BST rules to build a valid BST out of these uppercase letters, but you must make sure that:

1. No vowel parent can have a vowel as a child unless the parent’s sibling is also a vowel. This means that you can insert a vowel as a child of another vowel only if its uncle-to-be is also a vowel.

2. No consonant parent can have a duplicate value as a child i.e. the parent and a child cannot be the same consonant letters. This duplicate parent-child rule only applies to consonants and not vowels. For example letter A can be the child of parent-A as long as the child-A has a vowel uncle. Note: We agreed to insert the legal duplicates as the left child.

3. When you encounter a letter that could not be inserted based on the above rules, you will save them in a proper data structure to be re-inserted following the rules of part II of this assignment, and move on to the next letter. When you are done populating the BST with the letters that you could properly insert, you will re-insert the letters that were put on hold IN THE EXACT ORDER they were put on hold and in the tree based on the rules of Part II. This should give you a hint about what data structure you need to use for these letters for further processing.

4. BONUS: After the BST is properly populated, you must visit each node and compute its height. You need to modify the book’s code for class Node to incorporate this integer attribute and populate it as you visit each node. You MUST write a method to compute all nodes’ height and assign them to their height attribute.

Why do you need to wait until the tree is fully populated to start computing each node’s height and could not decide on the height as you were inserting the nodes?

I leave it up to you to decide whether to write this method recursively or iteratively.

The following is the list of what is expected to output after completing part I:

1. Display the BST (using the book’s method)

2. Display the contents of the data structure you used to store the letters that could not be inserted (if any).

3. BONUS: Display the information of every node in the BST: the letter followed by their height; one node per line. This part along with the method to compute each node’s height will possibly earn you 15 bonus points.

Part II:

By the time you get to this part, you have your string of uppercase letters configured as a BST following the rules for Part I and potentially have a data structure that contains the letters that could not be inserted in BST and now you get a chance to re-insert them based on a different set of rules.

In case you have letters left from Part I, follow the methodology we covered in class and reinsert them IN THE EXACT ORDER THEY WERE PUT ON HOLD, and in the first available spot you find in the BST, starting from the left side.

When done, display the tree using the textbook’s display method, to show the letters that were inserted based on Part II’s rules.

• The program must be written in Java.

• The submission that is missing required files/classes will be considered void.

• Programs that do not compile will be considered void.
