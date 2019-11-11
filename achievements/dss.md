# DSS

## About

DSS (Digital Signature Services) is an open-source software library for electronic signature creation and validation. DSS supports the creation and verification of interoperable and secure electronic signatures in line with European legislation. In particular, DSS aims to follow the eIDAS Regulation and related standards closely.
DSS is being re-used in different IT solutions for electronic signatures in various countries (including non-European).
DSS was developed by DIGIT and Nowina Solutions and it is maintained up-to-date via new releases.

On the Hackathon 2019 DSS has been represented by 3 participants: Apostolos Apladas (DIGIT – European Commission), Pierrick Vandenbroucke (Nowina Solutions) and Aleksandr Beliakov (Nowina Solutions).

* Portal : https://ec.europa.eu/cefdigital/wiki/display/CEFDIGITAL/eSignature
* FAQ : https://ec.europa.eu/cefdigital/wiki/display/CEFDIGITAL/eSignature+FAQ
* Demo / Doc : https://ec.europa.eu/cefdigital/DSS/webapp-demo
* GitHub : https://github.com/esig/

## Goals and achievements

For the event DSS team was mainly focused on the following topics:

* Security (Constant evolution, XSW, XXE, injections, vulnerabilities, misconfiguration/misusage);
* Performance (external resources, test environment, cache vs stateless objects, visualVM);
* PDF (PDFBox, OpenPDF, visible signatures);
* Java 12 (support since v5.5, module re-organization, smartcard.io, mocca, commons-io);
* Java FX (standalone application, offline mode, java 8).

During the workshop and a brainstorming session we have found the following issues / ideas for improvements and included it to the DSS agenda:
* [DSS-1816 : Timestamp only validation](https://ec.europa.eu/cefdigital/tracker/browse/DSS-1816)
* [DSS-1817 : Include schema version to validation reports](https://ec.europa.eu/cefdigital/tracker/browse/DSS-1817)
* [DSS-1818 : Custom validation policy must be applied on top of the default policy](https://ec.europa.eu/cefdigital/tracker/browse/DSS-1818)
* [DSS-1819 : Review exceptions](https://ec.europa.eu/cefdigital/tracker/browse/DSS-1819)
* [DSS-1820 : Timestamp qualification verification](https://ec.europa.eu/cefdigital/tracker/browse/DSS-1820)
* [DSS-1821 : Use WeakHashMap for efficient memory clean](https://ec.europa.eu/cefdigital/tracker/browse/DSS-1821)
* [DSS-1822 : PDF/A validation](https://ec.europa.eu/cefdigital/tracker/browse/DSS-1822)
* [DSS-1823 : Multiple Offline CRL/OCSP sources](https://ec.europa.eu/cefdigital/tracker/browse/DSS-1823)

This was a very productive weekend and we were happy to get a chance to meet with DSS users.

<p align="center"><img src="https://live.staticflickr.com/65535/48851755908_c6c1b572e8_b.jpg"/></p>

Thank you and hope to see you next time!
