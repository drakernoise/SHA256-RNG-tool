# SHA256-RNG

An easy to use deterministic random number generator built in python that uses the SHA 256 cryptographic hash function as a means to get a sequence of pseudorandom bits. While being based on a cryptographic hash function, it is not guaranteed to be secure as a random number generator. That being said, it performs reasonably well on the DIEHARD test suite. 

### Installation

No installation is required, just import rng.py and use the classes provided.

# modified.py

It allows you to run it directly. It will propmpt you to give a hash and two limits (lower and upper) in order to generate a random number within a given range.

Given a hash, the same hash should generate the same random number each time while the range has not changed. It gives you proof of authenticity about the generation process.

I would like to give thanks to the original rng.py author @jordanhatcher who made the hard work and shared it to us.
