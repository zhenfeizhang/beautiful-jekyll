<!---
This is the source code of my resume
templates credit: https://mszep.github.io/pandoc_resume/
--->

Zhenfei Zhang
============

-------------------     ----------------------------
Cryptograhy Engineer                 zhenfei.zhang@hotmail.com
Algorand                         https://zhenfeizhang.github.io/
Boston, MA                          https://www.linkedin.com/in/zhenfeizhang/
-------------------     ----------------------------

Education
---------

2010-2014
:   **PhD, Computer Science**, _University of Wollongong, Australia_;

    *Thesis title: Revisiting Fully Homomorphic Encryption Schemes and Their Cryptographic Primitives*

<!--
2008-2009
:   **Master of Engineering - Research**, _University of Wollongong, Australia_;

2007
:   **Master of Internet Technology**, _University of Wollongong, Australia_;

2001-2005
:   **Bachelor of Computer Science**, _BeiHang _University, China_.
-->


Experience
----------

**Cryptography Engineer**, _Algorand_, 2018-now

Identify, develop and standardize cryptographic tools to be used
by Algorand blockchain protocol.

* Design: Identify suitable cryptography for Algorand blockchain from scratch;

* Coding:
Product level __Rust__ code for [Pixel aggregatable signature](https://eprint.iacr.org/2019/514.pdf);

* Standardization:
[Internet draft](https://datatracker.ietf.org/doc/draft-irtf-cfrg-bls-signature/) for BLS signature scheme, IETF/CFRG workgroup.

**Director of Cryptography Research**, _OnBoard Security_ (Acquired by Qualcomm), 2016-2018

NTRU and post-quantum cryptography research and standardization.

**Research Scientist**, _Security Innovation_, 2014-2016

IARPA project on Fully Homomorphic Encryptions.

Highlights
--------------------

Standards
:    Contribute to **4** out of 26 [2nd round candidates](https://csrc.nist.gov/Projects/Post-Quantum-Cryptography/round-2-submissions) of [NIST post-quantum standatdization process](https://csrc.nist.gov/Projects/Post-Quantum-Cryptography):
[Falcon](https://falcon-sign.info/), [LAC](https://eprint.iacr.org/2018/1009), [NTRU](https://ntru.org) and [Round5](https://round5.org);
: Internet draft: [BLS-signature](https://datatracker.ietf.org/doc/draft-irtf-cfrg-bls-signature/), Quantum safe hybrid for [TLS 1.2](https://datatracker.ietf.org/doc/draft-whyte-qsh-tls12/) and [TLS 1.3](https://datatracker.ietf.org/doc/draft-whyte-qsh-tls13/);
: Former member of ETSI [Quantum-safe Cryptography (QSC)](https://www.etsi.org/technologies/quantum-safe-cryptography)  working group;
: Former member of [ISO/SC27](https://www.iso.org/committee/45306.html) working group.


Publication and patents
: __3__ U.S. patents;
: __25+__ peer reviewed paper at Asiacrypt 2019, Crypto 2019, Asiacrypt 2018, PKC 2018, IEEE Transaction on Computers, etc.;
: See next pages for full list.


Programming Languages
:   **Rust**: Cryptographic library at product level; to be open sourced soon.

:   **C**: Cryptographic library, nearly product level code, submitted to NIST PQC competition.

:   **Python/Sage**: 	Prove of concept codes.



Software
--------------------

Pixel
: A pairing based, forward-secure and aggregatable signature, written in python (PoC) and rust (product level). Improves existing (non-aggregatable) solution by 100x,
to be open sourced and deployed soon.

Raptor
: A lattice based (linkable) ring signature, written in C as a PoC, aiming
to protect user's anonymity against quantum adversaries. [Source code](https://github.com/zhenfeizhang/raptor).

NTRUEncrypt
: A C implementation of NTRUEncrypt, submitted to NIST PQC standardization process. [Source code](https://github.com/zhenfeizhang/ntruencrypt_nist_submission).

Ring multiplication
: A C library for fast ring multiplication using AVX-2; improving
prior codes by
a factor of 2.23. [Source code](https://github.com/zhenfeizhang/polynomial_mul)

libgcrypt-ntru
: Enabling NTRUEncrypt for libgcrypt. [Source code](https://github.com/zhenfeizhang/libgcrypt-ntru).


Research Interest
--------------------

* Fully homomorphic encryptions, with use cases such as smart contracts, machine learning;
* Lattice based signatures, with additional features such as aggregation, anonymity;
* Efficient zero knowledge proofs secure against quantum computers.

\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\

```
See next pages for the full list of patents, standards and publications.
```
<!--------

==============================================
--->

<div style="page-break-after: always; visibility: hidden">
\pagebreak
</div>

# Patents

* __Chameleon Hash technique and linkable ring signature technique__
  * _Zhenfei Zhang_
  * Provisional patent, 2018.

* __Digital signature technique__
  * _Jeffrey Hoffstein, Jill Pipher, William J Whyte, Zhenfei Zhang_
  * United States Patent Application, 2018.

* __Digital signature method and apparatus__
  * _Jeffrey Hoffstein, Jill Pipher, Joseph H Silverman, William J Whyte, Zhenfei Zhang_
  * United States Patent 15530762, 2017.

# Standards

* __BLS Signature Scheme__
  * _D. Boneh, S.Gorbunov, R. Wahby, H.Wee, Z.Zhang_
  * Internet-Draft.

* __Quantum-Safe Hybrid (QSH) Ciphersuite for Transport Layer Security (TLS) version 1.2__
  * _J. M. Schanck, W. Whyte and Z. Zhang_
  * Internet-Draft.

* __Criteria for selection of public-key cryptographic algorithms for quantum-safe hybrid cryptography__
  * _J. M. Schanck, W. Whyte and Z. Zhang_
  * Internet-Draft.

* __Quantum-Safe Hybrid (QSH) Ciphersuite for Transport Layer Security (TLS) version 1.3__
  * _W. Whyte, Z. Zhang, S. Fluhrer and O. Garcia-Morchon_
  * Internet-Draft.

* __Efficient Embedded Security Standards (EESS) #1: Implementation Aspects of NTRUEncrypt__
  * _W. Whyte and Z. Zhang_
  * Consortium for Efficient Embedded Security

* __Quantum Safe Cryptography and Security; An introduction, benefits, enablers and challenges__
  * One of 22 contributors
  * European Telecommunications Standards Institute(ETSI) white paper

<div style="page-break-after: always; visibility: hidden">
\pagebreak
</div>

# Publications
2019
-------
* __Middle-Product Learning with Rounding Problem and its Applications__
  * _Shi Bai, Katharina Boudgoust, Dipayan Das, Adeline Roux-Langlois, Weiqiang Wen, Zhenfei Zhang_
  * Asiacrypt 2019.

* __Efficient Lattice-Based Zero-Knowledge Arguments with Standard Soundness: Construction and Applications__
  * _Rupeng Yang, Man Ho Au, Zhenfei Zhang, Qiuliang Xu, Zuoxia Yu, William Whyte_
  * Crypto 2019.   [IACR eprint](https://eprint.iacr.org/2019/747).

* __(Linkable) Ring Signature from Hash-Then-One-Way Signature__
  * _Xingye Lu, Man Ho Au, Zhenfei Zhang_
  * TrustCom 2019.  [IACR eprint](https://eprint.iacr.org/2019/567).

* __Ring Signatures based on Middle-Product Learning with Errors Problems__
  * _Dipayan Das, Man Ho Au and Zhenfei Zhang_
  * Africacrypt 2019.

* __Raptor: A Practical Lattice-Based (Linkable) Ring Signature__
  * _Xingye Lu, Man Ho Au, Zhenfei Zhang_
  * ACNS 2019. [IACR eprint](https://eprint.iacr.org/2018/857). [Source code](https://github.com/zhenfeizhang/raptor).

* __Round5: Compact and Fast Post-Quantum Public-Key Encryption__
  * _Hayo Baan, Sauvik Bhattacharya, Scott Fluhrer, Oscar Garcia-Morchon, Thijs Laarhoven, Ronald Rietman, Markku-Juhani O. Saarinen, Ludo Tolhuizen, Zhenfei Zhang_
  * PQCrypto 2019. [IACR eprint](https://eprint.iacr.org/2019/090.pdf). [Website](https://round5.org).

* __Cryptanalysis of an NTRU-based Proxy Encryption Scheme from ASIACCS'15__
  * _Zhen Liu, Yanbin Pan, Zhenfei Zhang_
  * PQCrypto 2019. [IACR eprint](https://eprint.iacr.org/2019/083.pdf).

2018
------------------------
* __LAC: Practical Ring-LWE Based Public-Key Encryption with Byte-Level Modulus__
  * _Xianhui Lu, Yamin Liu, Zhenfei Zhang, Dingding Jia, Haiyang Xue, Jingnan He, Bao Li_
  * Pre-print. [IACR eprint](https://eprint.iacr.org/2018/1009). [Source code](https://github.com/luxianhui007/LAC)

* __Shorter Messages and Faster Post-Quantum Encryption with Round5 on Cortex M__
  * _Markku-Juhani O. Saarinen, Sauvik Bhattacharya, Oscar Garcia-Morchon, Ronald Rietman, Ludo Tolhuizen, Zhenfei Zhang_
  * Cardis 2018. [IACR eprint](https://eprint.iacr.org/2018/723).

* __On the Hardness of the Computational Ring-LWR Problem and its Applications__
  * _Long Chen, Zhenfeng Zhang, Zhenfei Zhang_
  * Asiacrypt 2018. [IACR eprint](https://eprint.iacr.org/2018/536).

* __A signature scheme from the finite field isomorphism problem.__
  * _Jeffrey Hoffstein, Joseph H. Silverman, William Whyte, Zhenfei Zhang_
  * MathCrypt 2018. [IACR eprint](https://eprint.iacr.org/2018/675), [Slides](talks/FiniteFieldSignatures.pdf).

* __Practical Signatures from the Partial Fourier Recovery Problem Revisited: A Provably-Secure and Gaussian-Distributed Construction.__
  * _Xingye Lu, Zhenfei Zhang, Man Ho Au_
  * ACISP 2018. [Manuscript](pdf/PASS.pdf).

* __Optimizing polynomial convolution for NTRUEncrypt.__
  * _Wei Dai, William Whyte, Zhenfei Zhang_
  * IEEE Transaction on Computers. [IACR eprint](https://eprint.iacr.org/2018/229), [Source code](https://github.com/zhenfeizhang/polynomial_mul).

* __Fully Homomorphic Encryption from the Finite Field Isomorphism Problem.__
  * _Yarkin Doröz, Jeffrey Hoffstein, Jill Pipher, Joseph H. Silverman, Berk Sunar, William Whyte, Zhenfei Zhang:_
  * PKC 2018. [IACR eprint](https://eprint.iacr.org/2017/548).

2017
------------------------
* __Choosing parameters for NTRUEncrypt__
  * _Jeffrey Hoffstein, Jill Pipher, John M. Schanck, Joseph H. Silverman, William Whyte, Zhenfei Zhang_
  * CT-RSA 2017. [IACR eprint](https://eprint.iacr.org/2015/708).

* __Round2: KEM and PKE based on GLWR.__
  * _Hayo Baan, Sauvik Bhattacharya, Óscar García-Morchón, Ronald Rietman, Ludo Tolhuizen, Jose Luis Torre-Arce, Zhenfei Zhang_
  * NIST PQC submission. [IACR eprint](https://eprint.iacr.org/2017/1183).

* __A signature scheme from Learning with Truncation.__
  * _Jeffrey Hoffstein, Jill Pipher, William Whyte, Zhenfei Zhang_
  * Pre-print. [IACR eprint](https://eprint.iacr.org/2017/995).

* __Anonymous Announcement System (AAS) for Electric Vehicle in VANETs.__
  * _Man Ho Au, Joseph K. Liu, Zhenfei Zhang, Willy Susilo, Jin Li_
  * The Computer Journal. [Manuscript](pdf/aas.pdf).

2016
---------------
* __Circuit-extension handshakes for Tor achieving forward secrecy in a quantum world.__
  * _John M. Schanck, William Whyte, Zhenfei Zhang_
  * PoPETs 2016. [IACR eprint](https://eprint.iacr.org/2015/287), [Tor feature request](https://gitweb.torproject.org/torspec.git/tree/proposals/269-hybrid-handshake.txt), [Source code](https://github.com/NTRUOpenSourceProject/ntru-tor), [Slides](talks/ntrutor.pdf).

* __NTRU modular lattice signature scheme on CUDA GPUs.__
  * _Wei Dai, Berk Sunar, John M. Schanck, William Whyte, Zhenfei Zhang_
  * HPCS 2016. [IACR eprint](https://eprint.iacr.org/2016/471).


2015
--------------------

* __LLL for ideal lattices: re-evaluation of the security of Gentry-Halevi's FHE scheme.__
  * _Thomas Plantard, Willy Susilo, Zhenfei Zhang_
  * Design, Codes and Cryptography. [Manuscript](pdf/illl.pdf).

* __DA-Encrypt: Homomorphic Encryption via Non-Archimedean Diophantine Approximation.__
  * _Jeffrey Hoffstein, Jill Pipher, John M. Schanck, Joseph H. Silverman, William Whyte, Zhenfei Zhang_
  * Pre-print. [IACR eprint](https://eprint.iacr.org/2015/844).

2014 and earlier
-------------------

* __Fully Homomorphic Encryption Using Hidden Ideal Lattice.__
  * _Thomas Plantard, Willy Susilo, Zhenfei Zhang_
  * IEEE Transation on Information Forensics and Security. [Manuscript](pdf/HiddenLattice.pdf).

* __Adaptive Precision Floating Point LLL.__
  * _Thomas Plantard, Willy Susilo, Zhenfei Zhang_
  * ACISP 2013. [Manuscript](pdf/adp_lll.pdf).

* __On the CCA-1 Security of Somewhat Homomorphic Encryption over the Integers.__
  * _Zhenfei Zhang, Thomas Plantard, Willy Susilo_
  * ISPEC 2012. [Manuscript](pdf/cca.1.pdf).

* __Lattice Reduction for Modular Knapsack.__
  * _Thomas Plantard, Willy Susilo, Zhenfei Zhang_
  * SAC 2012. [Manuscript](pdf/rec_red.pdf).

* __Reaction Attack on Outsourced Computing with Fully Homomorphic Encryption Schemes.__
  * _Zhenfei Zhang, Thomas Plantard, Willy Susilo_
  * ISPEC 2012. [Manuscript](pdf/pracfheatt.pdf).