# ACM Alexandria Student Chapter "TheXCourse: Android"
* An Android introductory level crash course (7 sessions - 3 hours each).
* This work was done during my short time working as an Android Instructor for ACM Alexandria Student Chapter. 
* I have open sourced the assignments (Java) we built, feel free to use it for learning purposes. 
* Assignments assets and Session slides can also be found in this repository such that anyone can re-create this crash course from his home at his own pace.

<p align=center> <img src ='https://www.diygenius.com/wp-content/uploads/2015/06/android-apps-for-learning.jpg'/></p>

## Assignments
### Assignment 1: GeoQuiz
Originally from "Android Programming- The Big Nerd Ranch Guide" Chapter 1.  
The application you are going to create is called GeoQuiz. GeoQuiz tests the user’s knowledge of
geography. The user presses True or False to answer the question on screen, and GeoQuiz provides
instant feedback.

**Why is this a good Android programming exercise? You will learn how to:**

* Displaying an Activity and Mainfest File usage.
* XML Layouts and UI. 
* How to make the UI responive using Java Activity Class.
---
### Assignment 2: The Cheating GeoQuiz
Originally from "Android Programming- The Big Nerd Ranch Guide" Chapter 5.   
You will add a second activity to GeoQuiz. An activity controls a screen of information,
and this activity will add a second screen that offers users a chance to see the answer to the current
question.

**Why is this a good Android programming exercise? You will learn how to:**

* Create a new activity and a new layout for it.
* Start an activity from another activity. Starting an activity means asking the OS to create an
activity instance and call its onCreate(Bundle) method.
* Pass data between the parent (starting) activity and the child (started) activity.
* Also, we add Lifecycle Callbacks and use Logcat to better understand the activity lifecycle.
---
### Assignment 3: The Cheat-Aware GeoQuiz
In this version of GeoQuiz, we do modifications in order to receive updates from the Cheating Screen in the Quiz Screen about whether the user has used his cheating opportunity or not. See ? A cheat-aware GeoQuiz indeed.

**Why is this a good Android programming exercise? You will learn how to:**

* Passing data from child activity to parent activity when we press the back button to navigate back to the parent. 
* We also introduce a bug during the process caused by "Configuration Changes" and undertsand them.
* We use an appropriate solution for it "InstanceState" and discuss other possible more complex solutions for similar problems.
---
### Assignment 4: The MVC GeoQuiz
In this version of GeoQuiz, You are going to upgrade GeoQuiz to present more than one question.
To make this happen, you are going to add a class named Question to the GeoQuiz project. An instance of this class will encapsulate a single true-false question.  
Then, you will create an array of Question objects for QuizActivity to manage.

**Why is this a good Android programming exercise? You will learn how to:**

* Learn about the MVC Architecture and how to imply it in code. 
* Learn more about Java and OOP principals.
---
### Assignment 5: The Question List GeoQuiz
In this version of GeoQuiz, we are interested of displaying the array of questions the MVC arhcitecture made possible to exist in the last assignment in a screen which will be the first screen for the user.  
The List will be implemented 2 times, the first time using ListView and the second time using the RecyclerView.    
You can change between which is working from the Mainfest file by including the Intent Filter with Action MAIN on the one you want to launch. While ListView is the simplest solution and most time effective but RecyclerView complexity comes with much much additional features as well. 

**Why is this a good Android programming exercise? You will learn how to:**
* Learn all about ListView and how to use it in code.
* Learn all about RecyclerView and how to use it in code.

## Resources
While this list has taught me much, you should not limit yousrself to one book, course or tutorial. I recommend you go the extra mile and explore whatever falls in your hand and always keep learning.

1. *Android Programming: The Big Nerd Ranch Guide by Bill Phillips, Chris Stewart and Kristin Marsicano*
2. *Programming Mobile Applications for Android Handheld Systems by University of Maryland, College Park*
3. *[The Android Hive](https://www.androidhive.info/)*
4. *[The Android Minworks Guide](https://mindorks.com/)*

---

<p align=center> Made with :heart: by <b>Amr Elzawawy</b>. Wish you a happy <b>learning journey</b> :book: </p>
