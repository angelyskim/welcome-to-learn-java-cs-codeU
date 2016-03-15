# Welcome To Learn

Hello! Welcome to Learn. Learn is a Learning Management System. While that sounds quite fancy, for you it means, Learn is an online campus. Through Learn.co we've taught hundreds of students how to iOS and Web Developers. Now, we are teaching developers Computer Science theory with Java to _existing_ developers. Before we get into environment setup and the actual work, let's talk about how Learn works, and what we expect the students of this class to already understand before starting it.

## How Learn Works

Learn uses real tools. That means we don't have students coding in the browser, we don't have small games or quizzes we just have you, a text editor and a set of failing tests that you need to pass. That's right, every lab comes with a set of directions as well as a set of tests that you need to pass. Real developers use [Test Driven Development](https://en.wikipedia.org/wiki/Test-driven_development). So you will too. For this track we use JUnit and Hamcrest for testing.

The other main tool that real developers use is source control. Here on Learn we use Git and Github. We use the same flow that most other Open Source projects use to contribute code. Throughout this course, we assume you know how to use Git. If you don't check out [this awesome tutorial from GitHub](https://try.github.io). The basic flow for working on and submitting labs on Learn is:

  1. Fork the repository
  2. Clone your fork down to your local machine
  3. Work, work, work. As you need to run the tests, run either `learn` for OSX and Linux, or `learn-test` for Windows. This will run the tests as well as submit your results up to Learn.
  4. When you get all the tests to pass, push your code up, and submit a pull request.

If you are on OSX or Linux, most of this will be done for you using the `learn` tool. We'll cover more about the `learn` tool in future lessons after your environment is setup though.

## What We Expect You Already Know

We can't cover everything. It's simply too much! So because of that we have quizzes before every unit. These quizzes are meant to tell you what we expect you to know before starting that unit. If you know all of those basic things (ArrayLists, Java, LinkedLists, etc...) then you'll be fine and you'll probably get 100%. If you don't there are resources on each quiz that will explain those concepts. 

Other than that, we expect that you are already a developer. You've written Java code before, you are quite the expert at using your computer. So getting your environment setup should be a no-brainer. 

## A Note On Using IDEs 

All of the content will work fine if you want to use an IDE to code your JAVA. Truth is though, if you are using this content as interview prep, **you won't have an ide on an interview**. So, we highly recommend using a text editor to write your Java code. Then to compile/test your code just run `ant test` or `learn` on OSX/Linux and `learn-test` on Windows.

In summary, **don't use an IDE**. A text editor is way closer to the whiteboarding that you'll be doing in interviews.
