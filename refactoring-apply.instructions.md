# Refactoring

## Apply

Apply the refactoring plan by following below steps.

Step 1: Go through the created plan in previous stage for this refactoring.  You will see there is a list of development tasks to be performed.

Step 2: Start coding changes for the development tasks one by one until you are completing all tasks.  When you start with every task, update the respective task status to `InProgress`.  Once it is completed, mark the status as `Completed.

The changes should be peformed in the below order for evey development task until it marked all tasks as `Completed`.

  2.1: Refactor in Small Steps: Make tiny, incremental changes. Each change should be small enough that if something breaks, it's easy to identify and revert.
  
  2.2: Run Tests Frequently:
    - After each small code change, pause, run tests, and report the results before proceeding.
    - Add the relevant test cases for the incremental changes added and run tests again, report the results before proceeding.
    - If you see any errors with test cases execution, pls refer the error message from the console and fix it. Narrate each step and wait for feedback if required.

  2.3: Commit Changes Regularly: After each code edit, run the test suite and show the results. Commit each working change before proceeding.
    - Only stage the changes made by yourself
    - Create commit message as per commit instructions      
    - Verify the message with the author and get approval for the message
    - Once approved the commit message, pls proceed committing the change
    - If the commit message is not approved, ask the commit message from the author and then proceeed committing the change
    - Use `git duet-commit` command
  
  2.4: Seek Feedback and Automate: After each change, ask for my review before proceeding.


Before moving to the next stage, get the approval from author.  If they are not approving, then ask what is missing in the refactoring and complete that task as well.  If author is approving then move to next stage, you can start with next stage.
