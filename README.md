# cse220-lab-3-solved
**TO GET THIS SOLUTION VISIT:** [CSE220 Lab 3 Solved](https://www.ankitcodinghub.com/product/cse220-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119726&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE220 Lab 3  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Instructions for students:

1. Complete the following methods on Linked lists.

4. The submission format MUST be maintained. You need to copy paste all your codes in ONE SINGLE .txt file and upload that. If format is not maintained, whole lab submission will be canceled.

5. If you are using JAVA, you must include the Tester class containing the main method which should test your other methods in DoublyList class and print the outputs according to the tasks.

7. Usage of built in methods/libraries are NOT ALLOWED

8. The google form link for this lab is provided in BUX under LAB 3 Doubly Linked Lists subsection under the SUMMER21 CSE220 lab tab.

Dummy Headed Doubly Circular Linked List

Task 1:

i) Create a Node class which will hold three fields i.e an integer element and a reference to the next Node along with a reference to the previous Node.

ii) Create a Dummy Headed Doubly Circular Linked list Abstract Data Type (ADT)named DoublyList.The elements in the list are Nodes consisting of an integer type key (all keys are unique) and a reference to the next node and a reference to the previous Node.

[You are not allowed to use any global variable other than head.]

1. Constructors: (3)

a. DoublyList (int [] a) or def __intit__(self,a)

Pre-condition: Array cannot be empty.

Post-condition:This is the default constructor of MyList class. This constructor creates a Dummy Headed Doubly Circular Linked list list from an array.

2. void showList ( ) or def showList(self) (1)

Precondition: None.

Postcondition: Outputs the keys of the elements of the order list. If the list is empty, outputs “Empty list”.

3. void insert (Node newElement, ) or def insert(self, newElement) (4) Pre-condition: None.

Post-condition: This method inserts newElement at the tail of the list. If an element with the same key as newElement already exists in the list, then it concludes the key already exists and does not insert the key.

4. void insert (int newElement, int index) or def insert(self, newElement, index) (4)

Pre-condition: The list is not empty.

Post-condition: This method inserts newElement at the given index of the list. If an element with the same key as newElement value already exists in the list, then it concludes the key already exists and does not insert the key. [You must also check the validity of the index].

5. void remove (int index) or def insert(self, index) (4)

Pre-condition: The list is not empty.

Post-condition: This method removes the Node at the given index of the list.[You must also check the validity of the index].

6. int removeKey(int deleteKey) or def remove(self, deletekey) (4)

Pre-condition: List is not empty.

Post-condition: Removes the element from a list that contains the deleteKey and returns the deleted key value.
