# Pig Latin

Implement a program that translates from English to Pig Latin.

Pig Latin is a made-up children's language that's intended to be
confusing. It obeys a few simple rules (below), but when it's spoken
quickly it's really difficult for non-children (and non-native speakers)
to understand.

- **Rule 1**: If a word begins with a vowel sound, add an "ay" sound to the end of the word. Please note that "xr" and "yt" at the beginning of a word make vowel sounds (e.g. "xray" -> "xrayay", "yttria" -> "yttriaay").
- **Rule 2**: If a word begins with a consonant sound, move it to the end of the word and then add an "ay" sound to the end of the word. Consonant sounds can be made up of multiple consonants, a.k.a. a consonant cluster (e.g. "chair" -> "airchay").
- **Rule 3**: If a word starts with a consonant sound followed by "qu", move it to the end of the word, and then add an "ay" sound to the end of the word (e.g. "square" -> "aresquay").
- **Rule 4**: If a word contains a "y" after a consonant cluster or as the second letter in a two letter word it makes a vowel sound (e.g. "rhythm" -> "ythmrhay", "my" -> "ymay").

There are a few more rules for edge cases, and there are regional
variants too.

See <http://en.wikipedia.org/wiki/Pig_latin> for more details.

* * * *

To run the code in this exercise, you will only need to have [CommandBox CLI installed](https://commandbox.ortusbooks.com/setup/installation).  This binary runs CFML code from the command line.

To run the tests, `cd` into the exercise folder and run the following:

```bash 
box task run TestRunner
# Or start up a test watcher that will rerun when files change
box task run TestRunner --:watcher
```

The tests leverage a library called TestBox which supports xUnit and BDD style of testing.  All test suites will be written in the [BDD style](https://testbox.ortusbooks.com/content/primers/bdd/specs.html) which uses closures to define test specs.  You won't need to worry about installing TestBox.  The CLI test runner will take care of that for you.  You just need to be connected to the internet the first time you run it.  You can read more about it here:

[https://testbox.ortusbooks.com/content/](https://testbox.ortusbooks.com/content/)

## Source

The Pig Latin exercise at Test First Teaching by Ultrasaurus [https://github.com/ultrasaurus/test-first-teaching/blob/master/learn_ruby/pig_latin/](https://github.com/ultrasaurus/test-first-teaching/blob/master/learn_ruby/pig_latin/)

## Submitting Incomplete Solutions
It's possible to submit an incomplete solution so you can see how others have completed the exercise.
