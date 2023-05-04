Download Link: https://assignmentchef.com/product/solved-csc-115-fundamentals-of-programming-ii-assignment-2-collections
<br>
Objectives: Upon completion of this assignment you need to be able to:

<ul>

 <li>Practice creating a class that <em>implements</em> an interface in Java.</li>

 <li>Use the Node class to create a reference-based list.</li>

 <li>Use Exception Handling techniques.</li>

 <li>Read and understand specifications.</li>

 <li>Implement testing of code during development.</li>

</ul>

______________________________________________________________________________

<strong>Resources:</strong>

<ul>

 <li>CSC 115 Java Coding Conventions.pdf (found on conneX, under Resources)</li>

 <li>Textbook Chapters 4 and 5.</li>

 <li>java</li>

 <li>java</li>

 <li>java</li>

 <li>java</li>

 <li>java</li>

</ul>

Introduction:

A local pharmacy would like to keep a small database of its clients and a list of the medications that each patient is currently taking.  For now, it  is confined to local residents, but the pharmacy is hoping to tap into the larger region and include communication with the hospitals.  We are tasked with supporting a basic system that will monitor medication lists to later attach to patient files.  Since most people are not on huge numbers of mediation, we decide to use the basic List ADT to manage each patient’s medication information.  We haven’t decided whether to use an array based list or a reference based list, so we will implement both.  That way we can plug in whichever one suits the client’s needs, without having to alter the client’s handling of the lists. The array-based medication list has already been completed and tested.  We need to complete the reference-based list.

In this assignment you will:

<ul>

 <li>Develop the MedListRefBased class that implements the standard List interface approved by the client.</li>

 <li>Use the doubly-linked list as the primary data field in this class; it is described in the textbook’s Chapter 5 beginning on page 280.</li>

</ul>

Quick Start:

<ul>

 <li>If you haven’t done so already, download all the necessary documents for this assignment from conneX into a specific folder for CSC115 assignment two, assn2 is a recommended name.</li>

 <li>Double-click on the html to see the specifications for a standard List interface. It is similar to the ADT description on the Text page 204. The List.java file contains all the method headers required of any class that <em>implements </em>a list.  Note that none of the methods contain a body; the implementation is never part of an ADT.  Note also that the description uses Java generics, described on page 291.  This allows the <em>developer</em> of a List to make the decision of the type of elements E that will be stored in the list.</li>

 <li>Examine the completed source code for the MedListArrayBased Note that it implements List&lt;Medication&gt;,  allowing for any object of the MedicationArrayBased  to also call itself a List  object. Note also that MedListArrayBased implements every method of the List interface. Similarly to the file in Assignment one, there is a main method where internal testing of each method is carried out.  Internal testing allows a programmer to test all methods, including the private methods during the development phase.</li>

 <li>Examine the file called java. This is an example of an <em>external </em>tester. It is the tester that is used once the completed class is ready for its final assessment before submitting it to the client.  Note that it can only test the methods that are listed in the List ADT.  It tests the list for functionality from the perspective of a <em>user,</em> the pharmacy in this case.</li>

 <li>Compile all the given java files. You can run MedListArrayBased to examine the internal tester result.  You can also run the MedListTester to examine the external test results.</li>

 <li>Your job is to create a class called MedListRefBased that implements List&lt;Medication&gt;. It must contain all the required public methods and implement the list using a doubly linked list instead of an array. See Chapter 5 for information on the doubly linked list.</li>

 <li>Once the code for MedListRefBased is completed and internal testing is done, you can use the external tester after changing a portion of a single statement in the tester.</li>

</ul>

Detailed Instructions

There are several files supplied in this assignment.  Examine them many times; their purpose makes sense as you work on the implementation of the linked list version of the medication list. You only need to create one class.  Once that is done, you will need to alter the external tester

class so that it calls the MedListRefBased constructor instead of the MedListArrayBased constructor.

You are to create, implement and test the MedListRefBased class.  Make sure of the following:

<ol>

 <li>The main data structure you use to store the medications is a doubly linked list, that you create yourself (no util classes are to be used in your source code).</li>

 <li>The class implements List&lt;Medication&gt;.</li>

 <li>Any private methods are properly commented (follow the MedListArrayBased source code as a guide.) Note that comments are not required for any method that implements a method required by the List  Those methods are already commented and the methods you implement will follow those specifications.  During the labs, you will be introduced to <em>javadoc</em>, a tool to create proper documentation.</li>

 <li>The main method inside your source code tests each of your methods. Use this extensively to check the progress, including the private helper methods. You do not need to comment out the main method or delete it.  The marker will be looking for evidence of internal testing.</li>

 <li>Once you have thoroughly tested all the methods internally, then you can move onto the external tester. If the external tester fails, then you must go back to the internal tester and take the necessary steps to debug and fix your code.  The external tester will test your program when you alter the one line in java that declares the List list variable and initialize it with a call to  the MedListRefBased constructor. Then re-compile and run MedListTester.  You should see <strong>exactly</strong> the same output as when it tested the MedListArrayBased class.</li>

</ol>

Submission

Submit the following completed file to the Assignment folder on conneX:

<ul>

 <li>java</li>

</ul>

Please make sure that conneX has sent you a confirmation email.  Do not send [.class] (the byte code) file, or any another file for this assignment.  Also make sure you <em>submit</em> your assignment, not just save a draft.  All draft copies are not available to the instructors, so we cannot mark them.

<strong>Note about Academic Integrity</strong>:  It is OK to talk about your assignment with your classmates, and you are encouraged to design solutions together, but each student must implement (code) their own solution.

We will be using plagiarism detection software on your assignment submissions.

<ul>

 <li></li>

</ul>