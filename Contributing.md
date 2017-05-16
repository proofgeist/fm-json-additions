# Contributing Guide

We welcome feedback, bug reports, and bug fixes. Please help us incorporate your contributions by following this guide.

We know that github is a new thing for many of you FileMaker users, but don't worry. In this cases we aren't using any of the merging features of git. No pull requests, no committing.  We are just using this as an Issue Queue, and a code repository.

## Use Github Issues
Please use the Issue Queue here in Github for all feedback. Please label your issue with either, bug, question, question, or enhancement depending on the type of issue it is.

### Include Tests
All functions in this library are tested. We do not fix a bug or add a feature without writing tests to prove that the new changes work, and do not break existing code.  If you have a bug report, it will get fixed faster if you include Tests.  If you have a new feature idea, it will get included faster if you include a test file that show it passing all tests

#### How to Include Tests

Download the JSONAdditions.fmp12 file. and open it. Each record on that opening screen is a test. Press the Run all Tests button at the top of the screen. All tests should pass. 

There first text field is for Test JSON that you can use in your Test.  The second text field is for you to put your FileMaker expression that IS the test.  The third text box is the result of your test. It will populate when you run the test.  The final text field on the right is the Expected Result.  You need to put the correct result your test should return.

Write your test that *should* pass if your bug is fixed or your new feature is added.  Run all tests again. Your new test or tests should fail.

If that is all you can do; if you don't know how to fix the bug or solve the feature, then just go ahead and attach your file with the new test to the new issue you are creating.

#### Contributing New Features or Fixes

If you know how to fix the bug, or add the feature, please go ahead and add it to the file.  Make sure it passes your new test and all the others. Once you have it working, attach this file to the Github Issue you created for this feature or bug.

#### Fixing Bugs in the Queue

If you see an issue that you think you can fix.  Please download the Test file attached to the issue. Make the changes you think will fix it, and run the tests.  If all tests Pass, add your fixed test file, back to the issue as a comment.