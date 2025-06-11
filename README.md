# cs2050-program-1-solved
**TO GET THIS SOLUTION VISIT:** [CS2050 Program 1 Solved](https://mantutor.com/product/cs2050-instructions-solved-10/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112856&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2050 Program 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
In this project your will implement a data structure that models a bag with items. Each item has a short description, a weight (in pounds), and a price (in US$). A bag weighs the total weight of the items it carries. A bag also has a weight limit. Therefore, it does not allow items to be added if the weight limit cannot be preserved. As you will see, our implementation of a bag is going to be very similar to the linked list data structure discussed in class.

The Item Class

Finish the two constructors of the Item class. The generic constructor takes 3 parameters: description, weight, and price. The weight of an item cannot be less than .05 lbs (value defined by the MIN_WEIGHT class variable). Also, the price of an item cannot be less than US$ 1 (value defined by the MIN_PRICE class variable). The other constructor only takes the item’s description, setting its weight and price to .05 and 1, respectively.

Two items are equal if they have the same description, disregarding their weights and prices. The comparison is done without taking case into consideration. Therefore, items with descriptions like “laptop” and “Laptop” are considered to be equal.

The provided compareTo method allows items to be compared by price. For example, to check if item referenced by variable “a” is cheaper than item referenced by variable “b” you would do:

if (a.compareTo(b) &lt; 0) System.out.println(a + ” is cheaper than ” + b);

The Bag Class

A bag can be created by setting its weight limit. If the weight limit is not informed, it is assumed to be 50 lbs (value defined by the

DEFAULT_WEIGHT_LIMIT class variable). As said in the introduction section, a bag is modeled as a linked list. Because you can only add Item objects to the bag, the head of this specialized linked list is a reference to a Node. To avoid the cost of having to traverse the whole list to compute the bag’s weight, a variable with the same name is maintained, and it should always reflect on the bag’s current weight. Therefore, whenever a new item is added to the bag, the new item’s weight must be added to the bag’s weight variable; also, whenever an item is removed from the bag, the removed item’s weight must be subtracted to the bag’s weight variable. Other than the constructors, you are expected to implement the following methods in the Bag class:

boolean isTrue() double weight() double weightLimit() boolean add(final Item item) int count()

int count(final Item item) int price()

Item mostPricey()

boolean contains(final Item item) boolean remove(final Item item) boolean removeAll(final Item item)

Each method is described by a TO-DO embedded in the provided code.

The BagDriver Class

This was a famous screensaver that was in 99% of the Windows computers in the 90s. Before YouTube, we spent hours just looking at this screensaver wondering what the character, named Johnny Castaway, would do next. Imagine that you, like Johnny, will have to spend an indefinite amount of time on a desert island. To survive on this inhospitable island, you are only allowed to carry a 30 lbs bag. Which items would you bring with you? Using your Bag class, create a bag with items that you would bring with you. Display your bag (with proud), show whether your bag contains a “firecracker” or “firework” items, and what is the most pricey item in your bag.

The BagTest Class

To help you check whether your Bag class implementation is correct, a few tests were provided.

Submission

To avoid having points deducted, you MUST submit your project using the right format, which is: a zip file named “prg_01.zip” with the following files ONLY:

Item.java

Bag.java

BagDriver.java

Those files should NOT be in a subfolder. This is the structure that I am expecting:

prg_01.zip |___Item.java |___Bag.java |___BagDriver.java

Make sure to write your name in all source files submitted. Use the provided comment sections.

Rubric

+10 Item class (+5 for each constructor) +65 Bag class +5 constructors +2 boolean isTrue() +2 double weight() +2 double weightLimit() +7 boolean add(final Item item) +5 int count() +5 int count(final Item item) +5 int price() +7 Item mostPricey() +5 boolean contains(final Item item) +12 boolean remove(final Item item) +13 boolean removeAll(final Item item) +25 BagDriver class +5 Bag instantiation +7 items addition +3 bag display +5 if statement checking if bag contains items +5 display of the most pricey item -5 file submitted does not follow the format asked -5 comment sections of the source files do not list the name(s) of the student(s)
