---
title: "Is Trying to index into String really hard?"
collection: publications
permalink: /publication/2021/index-into-string
excerpt:  'Since Swift 2,`String` does no longer conform to `SequenceType`.In other words, you can not iterate through a string with a `for...in` loop.'
date: 2021-06-25
venue: 'Medium'
link: 'https://medium.com/@ahmed.samer43/is-trying-to-index-into-string-really-hard-eea704893258'
---

Paul Hudson published a great book called [Swift Coding Challenges](https://www.hackingwithswift.com/store/swift-coding-challenges) which I highly encourage you to buy it and dig into it.
But head back to the question. Paul said:
<blockquote>
This is one of the most common interview questions you’ll come across, and it has a particular quirk in Swift that might have caught you out: strings might look like arrays, but trying to index into them is hard.
</blockquote>

Since Swift 2,`String` does no longer conform to `SequenceType`.In other words, you can not iterate through a string with a `for...in` loop.In this article, we'll know trying to index into string is realy hard or no, and what are the options that you can use to trade-off this issue, and how to fix this issue easily without any conversion.

