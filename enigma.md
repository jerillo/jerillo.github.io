---
layout: inner
title: Enigma
permalink: /enigma/
---
# Enigma Encryption Simulator
##### Written in Java
--- 
An implementation of the Enigma machines, which encodes or decodes messages.    
This project was created for UC Berkeley's CS 61B: Data Structures in Spring 2020.

*Source code for this project can be provided upon request.*

---

## Features
Some of the functionality of enigma:
- Uses a configuration of rotors that encrypts communications
- Implement a progressive substitution cipher that makes decryption considerably more difficult than a plain substitution cipher
- Wrote unit tests and integration tests to ensure quality of the application

--- 

## Preview
To use, run:
```
java -ea enigma.Main [configuration file] [optional=input] [optional=output]
```
The configuration file describes the configuration of the rotors that can be used. 
The first line of input must be a settings line, describing the sequence of rotors and other additional settings.

Here as an example of running the Enigma machine with `default.conf`:
```
ABCDEFGHIJKLMNOPQRSTUVWXYZ
 5 3
 I MQ      (AELTPHQXRU) (BKNW) (CMOY) (DFG) (IV) (JZ) (S)
 II ME     (FIXVYOMW) (CDKLHUP) (ESZ) (BJ) (GR) (NT) (A) (Q)
 III MV    (ABDHPEJT) (CFLVMZOYQIRWUKXSG) (N)
 IV MJ     (AEPLIYWCOXMRFZBSTGJQNH) (DV) (KU)
 V MZ      (AVOLDRWFIUQ)(BZKSMNHYC) (EGTJPX)
 VI MZM    (AJQDVLEOZWIYTS) (CGMNHFUX) (BPRK) 
 VII MZM   (ANOUPFRIMBZTLWKSVEGCJYDHXQ) 
 VIII MZM  (AFLSETWUNDHOZVICQ) (BKJ) (GXY) (MPR)
 Beta N    (ALBEVFCYODJWUGNMQTZSKPR) (HIX)
 Gamma N   (AFNIRLBSQWVXGUZDKMTPCOYJHE)
 B R       (AE) (BN) (CK) (DQ) (FU) (GY) (HW) (IJ) (LO) (MP)
           (RX) (SZ) (TV)
 C R       (AR) (BD) (CO) (EJ) (FN) (GT) (HK) (IV) (LM) (PW)
           (QZ) (SX) (UY)

```
The first line `* B Beta I II III AAAA (TD) (KC) (JZ)` is the settings line.

![Preview](../img/preview/enigma/preview.gif)
