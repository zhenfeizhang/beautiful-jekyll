<!---
This is the source code of my resume
templates credit: https://mszep.github.io/pandoc_resume/
--->

Zhenfei Zhang
============

-------------------     ----------------------------
Cryptography Engineer   zhenfei.zhang@hotmail.com
Algorand                https://zhenfeizhang.github.io/
Boston, MA              https://www.linkedin.com/in/zhenfeizhang/
-------------------     ----------------------------


Experience
----------

**Cryptography Engineer**, _Algorand_, 2018-now

Identify, develop and standardize cryptographic tools to be used
by Algorand blockchain protocol.

* Design: Identify suitable cryptography for Algorand blockchain;

* Coding:
Product level __Rust__ code for
  * [Pixel aggregatable signature](https://github.com/algorand/pixel);
  * [BLS signature](https://github.com/algorand/bls_sigs_ref);
  * [Pointproofs](https://github.com/algorand/pointproofs): Aggregating Proofs for Multiple Vector Commitments;

* Standardization:
[Internet draft](https://datatracker.ietf.org/doc/draft-irtf-cfrg-bls-signature/) for BLS signature scheme, IETF/CFRG working group.

**Director of Cryptography Research**, _Security Innovation_ -> _OnBoard Security_, 2014-2018

* Homomorphic encryptions (IARPA project);
* Post-quantum cryptography;
* blockchain cryptography.

Highlights
--------------------

Standards
: Contribute to **2** out of 7 finalists of NIST's [post-quantum standardization process](https://csrc.nist.gov/projects/post-quantum-cryptography/round-3-submissions):
[Falcon](https://falcon-sign.info/) and [NTRU](https://ntru.org).
: [LAC](https://eprint.iacr.org/2018/1009) won the first prize of [Chinese post-quantum cryptography competition](https://www.cacrnet.org.cn/site/content/854.html).
: Internet draft: [BLS-signature](https://datatracker.ietf.org/doc/draft-irtf-cfrg-bls-signature/), Quantum safe hybrid for [TLS 1.2](https://datatracker.ietf.org/doc/draft-whyte-qsh-tls12/) and [TLS 1.3](https://datatracker.ietf.org/doc/draft-whyte-qsh-tls13/).
: Former member of ETSI [Quantum-safe Cryptography (QSC)](https://www.etsi.org/technologies/quantum-safe-cryptography)  working group.
: Former member of [ISO/SC27](https://www.iso.org/committee/45306.html) working group.


Publication and patents
: __3__ U.S. patents; __25+__ peer reviewed paper at ACM CCS 2020, PKC 2020, Asiacrypt 2019, Crypto 2019, Asiacrypt 2018, PKC 2018, IEEE Transaction on Computers, etc.;
: See next pages for full list.


Programming Languages
:   **Rust**: Cryptographic library at product level.

:   **C**: Cryptographic library, nearly product level code.

:   **Python/Sage**: 	Proof of concept codes.


<div style="page-break-after: always; visibility: hidden">
\pagebreak
</div>


Software
--------------------

Pixel
: A pairing based, forward-secure and aggregatable signature, written in python (PoC) and rust (product level). Improves existing (non-aggregatable) solution by 100x,
 open sourced and external audited. [Source code](https://github.com/algorand/pixel).

Pointproofs:
: A pairing based, aggregatable prove system over multiple vector commitments, written in rust (product level). [Source code](https://github.com/algorand/pointproofs).

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



Education
---------

2010-2014
:   **PhD, Computer Science**, _University of Wollongong, Australia_;

    *Thesis title: Revisiting Fully Homomorphic Encryption Schemes and Their Cryptographic Primitives*


2008-2009
:   **Master of Engineering - Research**, _University of Wollongong, Australia_;

2007
:   **Master of Internet Technology**, _University of Wollongong, Australia_;

2001-2005
:   **Bachelor of Computer Science**, _BeiHang University, China_.



Research Interest
--------------------

* Practical aspects of lattice based cryptography;
* Cryptographic primitives for blockchains privacy, such as ring signatures, zero knowledge proofs;

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

2020
-------
* __Pointproofs: Aggregating Proofs for Multiple Vector Commitments__
  * _Sergey Gorbunov, Leonid Reyzin, Hoeteck Wee, Zhenfei Zhang_
  * ACM CCS 2020. [IACR eprint](https://eprint.iacr.org/2020/419). [Source code](https://github.com/algorand/pointproofs).

* __MPSign: A Signature from Small-Secret Middle-Product Learning with Errors__
  * _Shi Bai, Dipayan Das, Ryo Hiromasa, Miruna Rosca, Amin Sakzad, Damien Stehle, Ron Steinfeld, Zhenfei Zhang_
  * PKC 2020. [IACR eprint](https://eprint.iacr.org/2020/198). [Source code](https://github.com/pqc-ntrust/middle-product-LWE-signature)


2019
-------
* __Modular Lattice Signatures, revisited__
  * _Dipayan Das, Jeffrey Hoffstein, Jill Pipher, William Whyte, Zhenfei Zhang_
  * Design, Codes and Cryptography. [IACR eprint](https://eprint.iacr.org/2019/1301)
  * [1st round](https://csrc.nist.gov/Projects/post-quantum-cryptography/round-1-submissions), NIST post-quantum cryptography standardization process.

* __Middle-Product Learning with Rounding Problem and its Applications__
  * _Shi Bai, Katharina Boudgoust, Dipayan Das, Adeline Roux-Langlois, Weiqiang Wen, Zhenfei Zhang_
  * Asiacrypt 2019. [IACR eprint](https://eprint.iacr.org/2019/1001).

* __Efficient Lattice-Based Zero-Knowledge Arguments with Standard Soundness: Construction and Applications__
  * _Rupeng Yang, Man Ho Au, Zhenfei Zhang, Qiuliang Xu, Zuoxia Yu, William Whyte_
  * Crypto 2019.   [IACR eprint](https://eprint.iacr.org/2019/747).

* __(Linkable) Ring Signature from Hash-Then-One-Way Signature__
  * _Xingye Lu, Man Ho Au, Zhenfei Zhang_
  * TrustCom 2019.  [IACR eprint](https://eprint.iacr.org/2019/567).

* __Ring Signatures based on Middle-Product Learning with Errors Problems__
  * _Dipayan Das, Man Ho Au, Zhenfei Zhang_
  * Africacrypt 2019.

* __Raptor: A Practical Lattice-Based (Linkable) Ring Signature__
  * _Xingye Lu, Man Ho Au, Zhenfei Zhang_
  * ACNS 2019. [IACR eprint](https://eprint.iacr.org/2018/857). [Source code](https://github.com/zhenfeizhang/raptor).

* __Round5: Compact and Fast Post-Quantum Public-Key Encryption__
  * _Hayo Baan, Sauvik Bhattacharya, Scott Fluhrer, Oscar Garcia-Morchon, Thijs Laarhoven, Ronald Rietman, Markku-Juhani O. Saarinen, Ludo Tolhuizen, Zhenfei Zhang_
  * PQCrypto 2019. [IACR eprint](https://eprint.iacr.org/2019/090.pdf). [Website](https://round5.org).
  * [2nd round](https://csrc.nist.gov/Projects/post-quantum-cryptography/round-2-submissions), NIST post-quantum cryptography standardization process.

* __Cryptanalysis of an NTRU-based Proxy Encryption Scheme from ASIACCS'15__
  * _Zhen Liu, Yanbin Pan, Zhenfei Zhang_
  * PQCrypto 2019. [IACR eprint](https://eprint.iacr.org/2019/083.pdf).

2018
------------------------
* __LAC: Practical Ring-LWE Based Public-Key Encryption with Byte-Level Modulus__
  * _Xianhui Lu, Yamin Liu, Zhenfei Zhang, Dingding Jia, Haiyang Xue, Jingnan He, Bao Li_
  * Pre-print. [IACR eprint](https://eprint.iacr.org/2018/1009). [Source code](https://github.com/luxianhui007/LAC). [talk](../../talks/nist-lac-2019.pdf)
  * __First prize__ of [Chinese post-quantum cryptography competition](https://www.cacrnet.org.cn/site/content/854.html).
  * [2nd round](https://csrc.nist.gov/Projects/post-quantum-cryptography/round-2-submissions), NIST post-quantum cryptography standardization process.

* __Shorter Messages and Faster Post-Quantum Encryption with Round5 on Cortex M__
  * _Markku-Juhani O. Saarinen, Sauvik Bhattacharya, Oscar Garcia-Morchon, Ronald Rietman, Ludo Tolhuizen, Zhenfei Zhang_
  * Cardis 2018. [IACR eprint](https://eprint.iacr.org/2018/723).

* __On the Hardness of the Computational Ring-LWR Problem and its Applications__
  * _Long Chen, Zhenfeng Zhang, Zhenfei Zhang_
  * Asiacrypt 2018. [IACR eprint](https://eprint.iacr.org/2018/536).

* __A signature scheme from the finite field isomorphism problem.__
  * _Jeffrey Hoffstein, Joseph H. Silverman, William Whyte, Zhenfei Zhang_
  * MathCrypt 2018. [IACR eprint](https://eprint.iacr.org/2018/675), [Slides](../../talks/FiniteFieldSignatures.pdf).
  * Journal of Mathematical Cryptology. [Journal version](https://www.degruyter.com/view/journals/jmc/14/1/article-p39.xml)

* __Practical Signatures from the Partial Fourier Recovery Problem Revisited: A Provably-Secure and Gaussian-Distributed Construction.__
  * _Xingye Lu, Zhenfei Zhang, Man Ho Au_
  * ACISP 2018.

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
  * The Computer Journal.

2016
---------------
* __Circuit-extension handshakes for Tor achieving forward secrecy in a quantum world.__
  * _John M. Schanck, William Whyte, Zhenfei Zhang_
  * PoPETs 2016. [IACR eprint](https://eprint.iacr.org/2015/287), [Tor feature request](https://gitweb.torproject.org/torspec.git/tree/proposals/269-hybrid-handshake.txt), [Source code](https://github.com/NTRUOpenSourceProject/ntru-tor).

* __NTRU modular lattice signature scheme on CUDA GPUs.__
  * _Wei Dai, Berk Sunar, John M. Schanck, William Whyte, Zhenfei Zhang_
  * HPCS 2016. [IACR eprint](https://eprint.iacr.org/2016/471).


2015 and earlier
--------------------

* __LLL for ideal lattices: re-evaluation of the security of Gentry-Halevi's FHE scheme.__
  * _Thomas Plantard, Willy Susilo, Zhenfei Zhang_
  * Design, Codes and Cryptography.

* __DA-Encrypt: Homomorphic Encryption via Non-Archimedean Diophantine Approximation.__
  * _Jeffrey Hoffstein, Jill Pipher, John M. Schanck, Joseph H. Silverman, William Whyte, Zhenfei Zhang_
  * Pre-print. [IACR eprint](https://eprint.iacr.org/2015/844).

* __Fully Homomorphic Encryption Using Hidden Ideal Lattice.__
  * _Thomas Plantard, Willy Susilo, Zhenfei Zhang_
  * IEEE Transation on Information Forensics and Security.

* __Adaptive Precision Floating Point LLL.__
  * _Thomas Plantard, Willy Susilo, Zhenfei Zhang_
  * ACISP 2013.

* __On the CCA-1 Security of Somewhat Homomorphic Encryption over the Integers.__
  * _Zhenfei Zhang, Thomas Plantard, Willy Susilo_
  * ISPEC 2012.

* __Lattice Reduction for Modular Knapsack.__
  * _Thomas Plantard, Willy Susilo, Zhenfei Zhang_
  * SAC 2012.

* __Reaction Attack on Outsourced Computing with Fully Homomorphic Encryption Schemes.__
  * _Zhenfei Zhang, Thomas Plantard, Willy Susilo_
  * ISPEC 2012.
