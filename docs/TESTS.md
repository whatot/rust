## Writing the Code

Write your code in `src/lib.rs`. Some exercises come with a stub file in `src/lib.rs` that will show you the signatures of the code you'll need to write. If the exercise does not come with a `src/lib.rs` file, create one.

The directory must be named `src` and the file must be named `lib.rs` otherwise your code will not compile. For more details, check out the rustlang book [chapter on crates and modules](http://doc.rust-lang.org/stable/book/crates-and-modules.html)

### Running Tests

To run the tests, all you need to do is run the following command:

```bash
$ cargo test
```

Only the first test is enabled by default.  After you are ready to pass the next test, remove the ignore flag from the next test (`#[ignore]`).  You can also remove the flag from all the tests at once if you prefer.

You should try to write as little code possible to get the tests to pass.  Let the test failures guide you to what should be written next.

Because Rust checks all code at compile time you may find that your tests won't compile until you write the required code. Even `ignore`d tests are checked at compile time. You can [comment out](https://doc.rust-lang.org/stable/book/comments.html) tests that won't compile by starting each line with a `//`. Then, when you're ready to work on that test, you can un-comment it.
