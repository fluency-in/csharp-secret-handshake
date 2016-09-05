# C#: Secret Handshake

Write a program that will take a decimal number, and convert it to the appropriate sequence of events for a secret handshake.

> There are 10 types of people in the world: Those who understand
> binary, and those who don't.

You and your fellow cohort of those in the "know" when it comes to
binary decide to come up with a secret "handshake".

```
1 = wink
10 = double blink
100 = close your eyes
1000 = jump


10000 = Reverse the order of the operations in the secret handshake.
```

Here's a couple of examples:

Given the input 9, the function would return the array
["wink", "jump"]

Given the input "11001", the function would return the array
["jump", "wink"]


The program should consider strings specifying an invalid binary as the
value 0.

Follow these instructions on how to [get your C# development environment set up][csharp-installation].

The exercises use NUnit. Follow [this guide][nunit-guide] to get started.

[csharp-installation]: https://github.com/exercism/xcsharp/blob/master/docs/INSTALLATION.md
[nunit-guide]: https://github.com/exercism/xcsharp/blob/master/docs/TESTS.md

## Source

Bert, in Mary Poppins [http://www.imdb.com/character/ch0011238/quotes](http://www.imdb.com/character/ch0011238/quotes)

This exercise is from the [C#][csharp] track on [Exercism][exercism]

[exercism]: http://exercism.io
[csharp]: http://exercism.io/languages/csharp



