---
title: Week 09 | JavaScript Core 3
---

<hr class="mb-0">

<h1 id="{{ Week 09-JavaScript Core 3 | slugify }}">
  <span class="week-prefix">Week 09 |</span> JavaScript Core 3
</h1>

<div class="week-controls">

  {% assign week_num = 09 | to_integer %}

  <h2 class="week-controls__previous_week">

    <!-- ADD CHECK FOR WEEK open:true (remove if false) -->
    {% if week_num > 0 %}

      {% assign previous_week_num = 09 | to_integer | minus: 1 | prepend: '00' | slice: -2, 2 %}

      <a href="/WDX-180/curriculum/week{{ previous_week_num }}">Week {{ previous_week_num }} &#8678;</a>
    {% endif %}

  </h2>

  <span>Updated: 26/11/2023</span>

  <h2 class="week-controls__next_week">

    <!-- ADD CHECK FOR WEEK open:true (remove if false) -->
    {% if false and week_num <= 36 %}

      {% assign next_week_num = 09 | to_integer | plus: 1 | prepend: '00' | slice: -2, 2 %}

      <a href="/WDX-180/curriculum/week{{ next_week_num }}">&#8680; Week {{ next_week_num }}</a>
    {% endif %}

  </h2>

</div>

---

<!-- Week 09 - Day 1 | Functions Part 1 -->
<details markdown="1">
  <summary>
    <h2>
      <span class="summary-day">Week 09 - Day 1</span> | Functions Part 1</h2>
  </summary>

### Schedule

  - [Study](#study-plan-NN)
  - [Exercises](#exercises-NN)
  - [Extra Resources](#extra-resources-NN)

### Study Plan

  Another essential concept in coding is functions, which allow you to store a piece of code that does a single task inside a defined block, and then call that code whenever you need it using a single short command — rather than having to type out the same code multiple times. In this module we'll explore fundamental concepts behind functions such as basic syntax, how to invoke and define them, scope, and parameters.

  In JavaScript, you'll find functions everywhere. In fact, we've been using functions all the way through the course so far; we've just not been talking about them very much. Now is the time, however, for us to start talking about functions explicitly, and really exploring their syntax.

  Pretty much anytime you make use of a JavaScript structure that features a pair of parentheses — () — and you're not using a common built-in language structure like a for loop, while or do...while loop, or if...else statement, you are making use of a function.

  > The examples and exercises in this repository all use () => {} (arrow functions), while many resources online cover function functions. Why? Because arrow functions are simpler to study in the debugger. That's all you need to know for now!



  - [Watch: **JavaScript Functions In 90 Seconds**](https://www.youtube.com/watch?v=UY182o4J5_Y){:target="_blank"}
    - **Duration:** 2min
    - **Level:** Beginner

  <!-- TODO: INTEGRATE  -->


  - [Study: **Function Basics** @javascript.info](https://javascript.info/function-basics){:target="_blank"}
    - **Level:** Beginner

  Make sure to follow the guides on **Setting up Study Lenses (v2) on your System**. Once `lenses2` is properly installed on your system, you can go to your `WDX-180` folder and run `lenses2` with the material for this Module:

  - `cd WDX-180/`
  - `lenses2 curriculum/modules/javascript/denepo/_inside-js/3-functions/`

  or just:

  - `cd WDX-180/curriculum/modules/javascript/denepo/_inside-js/3-functions/`
  - `lenses2`

  You should focus and study the following modules (included within `3-functions/`):

  - **1-functions**
  - **2-documenting-functions**
  - **3-the-callstack**
  - **4-local-param-parent**

<!-- Summary -->

<!-- Exercises -->

### Extra Resources

  - [Function Basics @ The Coding Train](https://www.youtube.com/watch?v=wRHAitGzBrg){:target="_blank"}
  - [5.2: Function Parameters and Arguments @ The Coding Train](https://www.youtube.com/watch?v=zkc417YapfE){:target="_blank"}
  - [5.3: Functions and Return @ The Coding Train](https://www.youtube.com/watch?v=qRnUBiTJ66Y){:target="_blank"}

<!-- Sources and Attributions -->
  
</details>

<hr class="mt-1">

<!-- Week 09 - Day 2 | Functions Part 2 -->
<details markdown="1">
  <summary>
    <h2>
      <span class="summary-day">Week 09 - Day 2</span> | Functions Part 2</h2>
  </summary>

### Schedule

  - [Study](#study-plan-NN)
  - [Exercises](#exercises-NN)
  - [Extra Resources](#extra-resources-NN)

### Study Plan

  Make sure to follow the guides on **Setting up Study Lenses (v2) on your System**. Once `lenses2` is properly installed on your system, you can go to your `WDX-180` folder and run `lenses2` with the material for this Module:

  - `cd WDX-180/`
  - `lenses2 curriculum/modules/javascript/denepo/_inside-js/6-using-functions/`

  or just:

  - `cd WDX-180/curriculum/modules/javascript/denepo/_inside-js/6-using-functions/`
  - `lenses2`

  You should focus and study the following modules (included within `6-using-functions/`):

  - **1-calling-functions**
  - **2-writing-functions**
  - **3-refactoring-functions**
  - **4-reverse-engineering**
  - **5-dom-io**

<!-- Summary -->

<!-- Exercises -->

<!-- Extra Resources -->

<!-- Sources and Attributions -->
  
</details>

<hr class="mt-1">



<hr class="mt-1">

**Weekly feedback:** Hey, it's really important for us to know how your experience with the course has been so far, so don't forget to fill in and submit your [**mandatory** feedback form](https://forms.gle/S6Zg3bbS2uuwsSZF9){:target="_blank"} before the day ends. Thanks you!

## Week 09 - Weekend Suggestions

If you are in the mood of enjoying related content during the weekend, check out our weekly recommendations [here](WEEKEND.md).