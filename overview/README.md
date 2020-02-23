[Trusted computing] discusses common approaches and their limitations to 
trusted computing.

One can only do so much with software. The problem with software and
general purpose processors is that the software can be modified and the
processor will still execute it. Some examples: Alice left the laptop in
the hotel room while having breakfast, perhaps the hotel aide replaced
the bootloader to break Alice’s full-disk encryption? Or, how can Alice
even trust the computer when it is brand new? Another aspect of this is
to protect parts of the system from Alice herself, e.g. this is what
<span acronym-label="DRM" acronym-form="singular+short">DRM</span> is
all about. We also have the compartmentalization of apps in a
smartphone. If Alice accidentally installs a malicious app, it shouldn’t
be able to compromize the banking app. Here we will explore how to
ensure the integrity of the computer system.

More concretely, after this session you should be able to

-   *understand* the problem of trusted computing, its approaches to
    solutions, the underlying assumptions and its limitations.

-   *analyse* different approaches to trusted computing and their
    limitations and *apply* them in a solution to a given problem.

We treat the material in Chapters 16, 17, 18, 22 and 23 in  (Anderson
2008). The papers (Genkin, Pipman, and Tromer 2015; Genkin, Shamir, and
Tromer 2014; Genkin et al. 2015) illustrates just how difficult this can
be. The authors extract encryption keys using acoustic side-channels,
i.e. they analyse the sound emitted by the electrical circuitry to find
the computations done and hence derive the bits of the key used.

Anderson, Ross J. 2008. *Security Engineering: A Guide to Building
Dependable Distributed Systems*. 2nd ed. Indianapolis, IN: Wiley.
<http://www.cl.cam.ac.uk/~rja14/book.html>.

Genkin, Daniel, Lev Pachmanov, Itamar Pipman, and Eran Tromer. 2015.
“Stealing Keys from Pcs Using a Radio: Cheap Electromagnetic Attacks on
Windowed Exponentiation.” In *Cryptographic Hardware and Embedded
Systems – Ches 2015*, edited by Tim Güneysu and Helena Handschuh,
207–28. Berlin, Heidelberg: Springer Berlin Heidelberg.

Genkin, Daniel, Itamar Pipman, and Eran Tromer. 2015. “Get Your Hands
Off My Laptop: Physical Side-Channel Key-Extraction Attacks on Pcs.”
*Journal of Cryptographic Engineering* 5 (2): 95–112.
<https://doi.org/10.1007/s13389-015-0100-7>.

Genkin, Daniel, Adi Shamir, and Eran Tromer. 2014. “RSA Key Extraction
via Low-Bandwidth Acoustic Cryptanalysis.” In *Advances in Cryptology –
Crypto 2014*, edited by JuanA. Garay and Rosario Gennaro, 8616:444–61.
Lecture Notes in Computer Science. Springer Berlin Heidelberg.
<https://doi.org/10.1007/978-3-662-44371-2_25>.
