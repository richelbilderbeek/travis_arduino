# travis_arduino

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_arduino.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_arduino)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:

 * Build system: Arduino
 * C++ compiler: Arduino
 * C++ version: Arduino
 * Libraries: Arduino library
 * Code coverage: none
 * Source: one single file, `main.cpp`

More complex builds:
 * Use of OCLint: [travis_arduino_oclint](https://www.github.com/richelbilderbeek/travis_arduino_oclint)

## Details

For compiling, [ino](https://github.com/amperka/ino.git) is used. It works great! 

The main function is put in `src/travis_arduino.ino`. It is required by [ino](https://github.com/amperka/ino.git)
that the sketch is in a `src` folder.

## More complex examples

 * [![Build Status](https://travis-ci.org/richelbilderbeek/ApproxyClock.svg?branch=master)](https://travis-ci.org/richelbilderbeek/ApproxyClock) [ApproxyClock](https://github.com/richelbilderbeek/ApproxyClock)
