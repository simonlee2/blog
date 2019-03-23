---
title: "Swift Summit 15"
date: 2019-03-23T22:53:08+08:00
draft: true
---

Some of my takeaways from the awesome talks at Swift Summit. The videos will be posted on https://www.swiftsummit.com, so you can check out all the talks when they are available.

# Feet in Both Worlds: from Objective-C to Swft
[Andy Matuschak](https://twitter.com/andy_matuschak)

Prior to the talk I didn’t think it would be relevant to me. I haven’t touched Objective-C since Swift was introduced, and my project at work is 99.9% Swift. However, Swift still uses the same Objective-C runtime, and there are design decisions in Swift that are there to make interop possible. It still makes sense to understand how Swift and Objective-C interoperate.

`@NSManaged` on an `NSManagedObject` allows Core Data to dynamically provides its implementation at runtime, based on the associated entity description
`@NSCopying` give a property similar behavior to Objective-C’s `copy` property
`@objc` marks a declaration in Swift so that it can be used in Objective-C code

# Lessons Learned: Dealing with Swift and CocoaPods

# Simple Asynchronous Swift Code with ReactiveCocoa 4

# Working with Binary Data in Swift

# Error Handling in Swift 2

# How to Build a More Compelling Watch App

# Simpler Tables with Values, Enums, & Protocols

# Emerging Best Practices in Swift

# What the 55 Swift Standard Library Protocols Taught Me

# Exploring Apple Pay with Swift