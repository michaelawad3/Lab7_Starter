# Name 
- Michael Awad (I worked alone)


# *Check Your Understanding*
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

    1. Within a Github action that runs whenever code is pushed. This is the because automated tests should run every time new code is added to the project. This is so bugs can be caught early before the code is merged or shared with the rest of the team. It also makes sure that new changes do not break existing features.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

    No you would not use end to end test to check if a function is returning the correct output. This is because an end-to-end test primary use is to test how a user interacts with the application from start to finish, such as clicking buttons, filling out forms, or navigating pages. To check whether a single function returns the correct output, you would use a unit test, not an end-to-end test.

3) What is the difference between navigation and snapshot mode?
   
   Navigation mode analyzes a page during its initial load. It measures thing such as First Contentful Paint, Largest Contentful Paint, Total Blocking time, Cumulative Layout Shift, and Speed index to provide a full picture of how the page laods from scratch.

   Snapshot mode analyzes the page in its current state without reloading it, so it can't measure load performance or Javascript behavior. Therefore, it's mainly used for catching accessibility and structural issues at a specific moment. This is most useful for auditing pages after user interactions

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

   1. Add a `lang` attribute to the `<html>` element
   2. Add a meta description tag (such as `<meta name="description" content="...">` in the `<head>` of the HTML)
   3. Use efficient cache lifetimes to speed up repeat visits