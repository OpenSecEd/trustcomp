[![Trusted computing][img]][vid]

[img]: https://img.youtube.com/vi/Uj-ElonmxaI/hqdefault.jpg
[vid]: https://youtu.be/Uj-ElonmxaI

*Summary:* One can only do so much with software. One problem with
software and general purpose processors is that the software can be
modified and the processor will still execute it. Another is that, that
running software cannot evaluate the processing environment which
executes it.

Some examples: Alice had her laptop in her bag as it passed through the
security check. While she was busy with the scans, one customs official
booted the laptop from a USB stick and installed a different boot
loader. Or, how can Alice even trust the computer when it is brand new?
Another aspect of this is to protect parts of the system from Alice
herself, this is what <span acronym-label="DRM"
acronym-form="singular+short">DRM</span> is all about. We also have the
compartmentalization of apps in a smartphone. If Alice accidentally
installs a malicious app, it shouldn’t be able to compromize the banking
app. Here we will explore how to ensure the integrity of the computer
system.

*Intended learning outcomes:* More concretely, after this session you
should be able to

-   *understand* the problem of trusted computing, its approaches to
    solutions, the underlying assumptions and its limitations.

-   *analyse* different approaches to trusted computing and their
    limitations and *apply* them in a solution to a given problem.

*Reading:* We touch on the topics in Chapters 16, 17, 18 and 23 in
 (Anderson 2008). The papers (Genkin, Pipman, and Tromer 2015; Genkin,
Shamir, and Tromer 2014; Genkin et al. 2015) illustrates just how
difficult it can be to lock secrets into hardware.

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
