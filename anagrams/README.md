Anagram checker
===============
An [anagram](https://en.wikipedia.org/wiki/Anagram) requires letters to be rearranged into new words or phrases.

Specifically, output anagrams should be valid words in a chosen language.

## Goals
This is an interesting problem in terms of **performance**. What is the performance characteristic of the letter permutation? What is the performance characteristic of validity checking?

This problem can also demonstrate effective **unit tests**.

## Input

The input file will contain a list of input phrases, one per line.

A dictionary will be given as an argument.

## Expected output

Print the input strings and valid outputs, one input per line. The input/output should be delimited by an equals sign, and the outputs should be delimited by a comma. No additional spaces or newlines should be added.

## Unit tests

In addition to solving the problem, your solution **must** include basic unit tests using a common framework in the language of your choice. This should not require access to external resources, such as services/APIs or files outside of your repository.

### Optional: JSON

Give the output as JSON. Choose an appropriate representation of the inputs and outputs.

### Optional: visualization

Use [Highcharts](http://www.highcharts.com/) to produce a self-contained HTML file giving a [histogram](http://en.wikipedia.org/wiki/Histogram) displaying how many anagrams were generated per word. By "self-contained", the numeric data should be contained within the file- it's okay to call out to the jquery and highcharts library.

Since we don't expect you to have experience with Highcharts or graphing libraries, [here's an example](visualization-example.html) ([view in browser](http://htmlpreview.github.io/?https://github.com/adhoclabs/interview-code-tests/blob/master/anagrams/visualization-example.html)). It should be relatively easy to replace values to communicate this information.

## Restrictions

Use the language specified by your interviewer. Generally you should not use extended libraries/packages. This doesn't mean you need to reinvent the wheel, but sample problems generally don't need complicated libraries.

### Extended libraries allowed by language:

* **Java**: reusable components from [Apache Commons](http://commons.apache.org/components.html) are acceptable, as is [GSON](https://code.google.com/p/google-gson/).
* **Python**: no external libraries are necessary.


## Example

As an example, this command should output anagrams on most platforms, given a dictionary file:

    $ echo "nelson" | python anagram.py /path/to/dict
    nelson=lens no,lens on

# Source
Thanks to [streamtech](http://www.streamtech.nl/problemset/148.html) for the idea behind this.
