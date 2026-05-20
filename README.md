I worked alone.

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

    1. Within a Github action that runs whenever code is pushed. This is the because automated tests should run every time new code is added to the project. This is so bugs can be caught early before the code is merged or shared with the rest of the team. It also makes sure that new changes do not break existing features.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

    No you would not use end to end test to check if a function is returning the correct output. This is because an end-to-end test primary use is to test how a user interacts with the application from start to finish, such as clicking buttons, filling out forms, or navigating pages. To check whether a single function returns the correct output, you would use a unit test, not an end-to-end test.