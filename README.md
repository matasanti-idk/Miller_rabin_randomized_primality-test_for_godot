Miller_rabin_randomized_primality-test_for_godot 

Let's you check for any given number if it's prime or composite and gives you the option to turn a prime number into a composite. this is great for anything that needs to check for primality and or change and fix the given number making this is great for dynamic coding, procedural generation, and adaptive game mechanics, but you have to know that's its only recommended for background use where something is prime and needs to be checked or turned into a composite. It's NOT recommended for normal use. This can be used for non-commercial or commercial uses, but credits are appreciated 

For Godot 4.6.3+ 

If you're interested in knowing more about it, check the sources used. https://www.cs.cornell.edu/courses/cs4820/2010sp/handouts/MillerRabin.pdf https://kconrad.math.uconn.edu/blurbs/ugradnumthy/millerrabin.pdf https://math.umd.edu/~immortal/ClassNotes/millerrabin.pdf https://homepages.math.uic.edu/~marker/math435/rm.pdf 

If you want to learn more but you can't understand or read the source, I will make a video later explain how it functions and why and a detailed wiki on how the code works. If you find any bugs or suggestions on how to improve the algorithm. feedback is highly appreciated 

additional information: while the Miller rabis randomized primality test is good, its inherently probabilistic so you must know that there will be 2 types available for you depending on your needs 

deterministic: The limit is for any number under 2^64 here. 

Probabilistic: Which has no limit but may give out false positives 

about the option to turn a prime number into a composite you must know that the Miller Rabin randomized primality test only checks if a number is prime for this option the value of the prime number will be altered to be composite. so, you will lose the original prime unless you make it save both numbers 
