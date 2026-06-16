# Miller_rabin_randomized_primality-test_for_godot
lets you check for any given number if it's prime or composite and gives you the option to turn a prime number into a composite.
this is great for anything that needs to check for primality and or change and fix the given number making this is
great for dynamic coding, procedural generation, and adaptive game mechanics, but you have to know thats its only recomended for background use where something is prime and needs to be checked or turned into a composite
. Its NOT recommended for normal use.
this can be used for non-commercial or commercial uses, but credits is appreciated

For godot 4.6.3+

if your interasted on knowing more about it check the sources used.
https://www.cs.cornell.edu/courses/cs4820/2010sp/handouts/MillerRabin.pdf
https://math.umd.edu/~immortal/ClassNotes/millerrabin.pdf
if you want to learn more but you can't understand or read the source i will make a video later on explaing how it functions and why
and a detailed wiki on how the code works
if you find any bugs or suggestions on how to improve the algorithm feedback is highly appreciated

additional information:
while the Miller rabis randomized prmality test is good its inheranlty probabilistic 
you have to know that their will be 2 types aviable for you depending on your needs

deterministic: the limit is for any number under 2^64 here. 

Probabilistic: which has no limit but may give out false positives

about the option to turn a rpime number into a composite you must know that the Miller Rabin randomized primality test only checks if a number is prime for this option the value of the prime number will be altterd to be composite so you will lose the orignal prime 
