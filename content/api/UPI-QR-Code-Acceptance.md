---
title: "UPI QR Code Acceptance"
date: 2020-10-26T16:44:55+08:00
draft: false
---
@[QR Code Payments|Acquirer|obile Payment]

UPI QR Code is a product of inter-bank switch for mobile payments. Through UPI system with API Interfaces, acquirers outside of mainland China will be able to support UPI QR Code payment for its merchants.

[TOC]

## API Introduction

#### What is it?
UPI QR Code product can be used by UPI QR Code merchants to support a low-cost, convenient and secure innovative payment solution by either displaying a static/dynamic QR Code (Merchant-Presented) or scanning consumer's payment QR Code (Consumer-Presented).

This set of API provides all the necessary functions, allowing acquirers to connect to UPI system with JSON message instead of traditional ISO 8583 message, and supporting UPI QR Code payments in both Merchant-Presented and Consumer-Presented mode.

#### Key Features
**Open**
The platform is open. QR Code can be displayed on merchant's app. The transaction can be completed with any APP that can support UPI's QR Code.

**Security**
Security is a basic requirement for payments. UPI adopts Tokenization technology which supports risk control for whole transaction process, making sure of safety and preventing leakage of account information.

**Interoperability**
UPI's QR Code is of EMVCo standard and extendable for future use of compatibility of other international card schemes, which makes QR Code payment in and out of mainland China interoperable.

**Integrity**
UPI's QR Code payment sticks to 4-party mode which is almost the same with bank card transaction only except for the information interaction. UPI's QR Code payment has a whole integrated mechanism of business, risk control, techniques which makes user's capital secured.

## Flow Chart
![Flow Chart](https://developer.unionpayintl.com/upload/cj/image/1526349102018026242.jpg)