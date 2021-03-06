Amaze was created with a vision to provide all the basic and advanced features a file manager in Android is supposed to have, with a friendly material design.
As with any other open source project, contributions are the key to achieve this goal of ours.

Contributions are always welcome!

To start contributing, I'll assume you know how to use git and write and debug Android apps - don't expect we can teach you ;)

Please keep in mind below few points before considering contributing to Amaze:
- Make sure to write your name and Email-ID in format ````Name<email>```` in the license declaration above every file you make change to.
You won't be able to claim the license for changes made by you unless you do that. 
If there's no license header in any file, please include one from [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html) webpage.
- Please follow [Android/JAVA code style](https://source.android.com/source/code-style.html) for writing any code, but do not use the hungarian notation proposed, discussion [here](https://github.com/TeamAmaze/AmazeFileManager/issues/986). 
And [Android Material Design guidelines](https://material.io/guidelines/material-design/introduction.html) in case you make changes to any UI element.
- To file a bug report, it is recommended to capture a bug report along with reporting the steps to reproduce it. 
It is also recommended to enroll to our beta program from Play Store to test and verify any fix for the same.

We work with pull requests, so, for improvements, new features or bugfixes, please submit your changes as pull requests.
We will then:

1. start review of your code for cleanliness and robustness
2. test them to see if they work as you said
3. merge the pull request

To speed up the review process, please:

- write your code cleanly. We also have our day time work, we are not able to correct your code for mistakes
- describe cleanly what your pull request does
- if you're fixing a particular bug in the issue list, please explicitly say "Fixes #<issue number>" in your description
- while not required (because automated tests can't test everything), it's recommended you to include [Robolectric](http://robolectric.org/)/[Espresso](https://developer.android.com/training/testing/espresso/) tests in your pull request

Finally:

- it's good to start a new branch to start your work, not just for a shiny branch name, but also for your own good
- we can be harsh when reviewing your work but because we want to have good code in our codebase. Be patient and carefully read our comments
- we may be wrong. Please, be patient when arguing with us - we accept reason, but never accept hate speech

Ready to roll? Start forking ;)