# Moving Forward from Scala 2 to Scala 3

## Description

This target audience for this course is the Scala Application Developer Community. So, there's a focus on people who use the language to develop 'end-user' applications and not necessarily those developers who design and write libraries, toolkits or frameworks (although they may benefit from what's in this course if they haven't already worked with Dotty).

The goal of the course is to explore the new features in the Scala language brought by [the Dotty project](https://dotty.epfl.ch). Even though it's still early days and the first release candidate of the Scala 3 language is probably out for another 6 months, it is our believe that one can never start too early by learning Dotty for the following reasons:

- There's a lot to learn, so if you wait until everything is ready, you're already too late.
- There are many opportunities to contribute to the Dotty project, which will accelerate it's development, exercise it which will inevitably expose issues that can be corrected well in time. Using Dotty will provide opportunities to do this.

## Approach

We start from an existing Scala 2 application: an [[Akka](https://akka.io)] actor based Sudoku solver. We start from the application as-is, but with an sbt build definition that uses the Dotty compiler.

Through a series of exercises, we look at specific Dotty features and apply these to the Scala 2 code, thereby transforming it step-by-step into a version that exploits a whole series of nice features offered by the new language.

Note that this is work in progress, so keep watching this space!
