# Project Work Time - Testing

## Learning Goals

- Spend some time working on your project.

## Project Work Time

Now that we have learned a little more about testing in Spring, it's time to
apply this new knowledge to our projects!

Consider the following instructions:

- Generate a unit test for the `ActivityController` class.
  - Remember, to generate a test class in IntelliJ, you can right-click anywhere
    in the code of the `ActivityController` class --> click "Generate..." -->
    choose "Test...".
  - Name the test class "ActivityControllerUnitTest". You will want to add a
    `setUp()` method along with all the methods in the `ActivityController`
    to test.
  - Make use of the Mockito framework when appropriate.
    - When testing a void method, use the `doNothing()` and `verify()` methods
      provided in the Mockito library. To learn more about these methods, please
      see:
      [Baeldung: Mockito Void Methods](https://www.baeldung.com/mockito-void-methods).
- Generate a unit test for the `CamperController` class.
  - Remember, to generate a test class in IntelliJ, you can right-click anywhere
    in the code of the `CamperController` class --> click "Generate..." -->
    choose "Test...".
  - Name the test class "CamperControllerUnitTest". You will want to add a
    `setUp()` method along with all the methods in the `CamperController` to
    test.
  - Make use of the Mockito framework when appropriate.
- Generate a unit test for the `SignupController` class.
  - Remember, to generate a test class in IntelliJ, you can right-click anywhere
    in the code of the `SignupController` class --> click "Generate..." -->
    choose "Test...".
  - Name the test class "SignupControllerUnitTest". Add all the methods in the
    `SignupController` to test. If there is more than one method, add a
    `setUp()` method as well.
  - Make use of the Mockito framework when appropriate.

## Stretch Goals

There are a couple of stretch goals regarding testing. You may choose to
implement these if time allows. We recommend implementing these stretch goals in
the following order:

- Add integration tests to the controller classes and repository classes.
- Add an acceptance test to test every endpoint in the application.

> Note it is **not** required to implement either of these stretch goals. They
> exist for students who want more of a challenge.

## Resources

- [Telerik: Unit Testing and Mocking Explained](https://www.telerik.com/products/mocking/unit-testing.aspx#:~:text=What%20is%20a%20mocking%20framework,substitutes%20for%20unit%20testing%20frameworks.)
- [Digital Ocean: Mockito Tutorial](https://www.digitalocean.com/community/tutorials/mockito-tutorial)
- [Baeldung: Mockito Void Methods](https://www.baeldung.com/mockito-void-methods)
