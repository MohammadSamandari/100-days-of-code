# 100 Days Of Code - Log

### Day 0: June 13, 2019

**Today's Progress**:
1. Android fundamentals 01.2 Part A: Your first interactive UI
2. Android fundamentals 01.2 Part B: The layout editor
3. Android fundamentals 01.3: Text and scrolling views
4. Android fundamentals 02.1: Activities and intents

**Thoughts:** I begin my first day of coding with codelab project from Android tutorials. i think it is the best way of learning android development.

**The Noticeable Thing I learned**
1. we can create a different layout for landscape and portrait devices. To create a variant of the layout strictly for the horizontal orientation, leaving the vertical orientation layout alone: click the Orientation in Editor button and select Create Landscape Variation.
2. Use a ScrollView to scroll a single child View (such as a TextView). A ScrollView can hold only one child View or ViewGroup.
3. Use the android:autoLink="web" attribute to make web links in the text clickable.
5. An Intent lets you request an action from another component in your app, for example, to start one Activityfrom another. An Intent can be explicit or implicit.
6. Defining Parent and Child Activity so that the Up Navigation appears in the child activity as a back button.
7. Getting data back from an Activity using StartActivityForResult()
8. Working with onActivityResult() override.


**Link to work:**
1. [Interactive Ui With Different Layout Variant](https://github.com/MohammadSamandari/AndroidFundamentals.git)
2. [Scrolling Text](https://github.com/MohammadSamandari/AndroidFundamental-ScrollingText.git)
3. [Two Activities](https://github.com/MohammadSamandari/Android-TwoActivities)

**Suggestion For Further Reading**
1. [Using ConstraintLayout to design your views](https://codelabs.developers.google.com/codelabs/constraint-layout/index.html)
2. [Working with the TextView](https://guides.codepath.com/android/Working-with-the-TextView)

### Day 1: June 14, 2019

**Today's Progress**:
1. Android fundamentals 02.2: Activity lifecycle and state

**Thoughts:**
I started my work with going through activity and explicit intents. then moved from that to lifecycles.
the intrensting thing was the saveInstanceState method. when changing orientation, some of the data was lost. we tried to preserve this data lose through saving them inside the
saveInstanceState.

**The Noticeable Things I learned:**
1. we learned about onstart and onresume and other lifecycles.
2. Activity instance state and how to save them.

**Link to work:**
1. [Two Activities](https://github.com/MohammadSamandari/Android-TwoActivities)
