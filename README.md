The main function takes three integers and an array.
Then checks whether these three integers exist in the array with their order given in the argument.
for example lets say the given array is 65 68 98 32 84 66 77421 546 35
and the given numbers are  68 98 32
this would return true since such subsequence exists with the given order between array indice one and four
if the given argument numbers were 32 84 35 it would return false. while given numbers exist on the array their order is diffrent.
if the given argument numbers were 1 56 8 it would return false since all three dont exist on the array
if the given argument numbers were 65 68 99 it would return false although 65 and 68 do exist in the array in the given order 99 does not.
[![Build Status](https://www.travis-ci.com/kaanefekeles/mydemoapp.svg?branch=main)](https://www.travis-ci.com/kaanefekeles/mydemoapp)
"Text for feature/xyz testing"

Demo site: https://pacific-dusk-58372.herokuapp.com/subsequentSubsetController