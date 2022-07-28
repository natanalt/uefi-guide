# A Comprehensive Guide To UEFI Programming
*by Natalia Cholewa*

UEFI has been **the** standard of PC firmware for over a decade now. Despite that, many of its design choices are... irritating at times, and its [specification](https://uefi.org/specifications) doesn't help much either. This little book aims to act as a starting point for anyone wishing to write UEFI applications — mainly bootloaders. It explains the basics of the UEFI environment and the way it can be programmed.

> **Just so you know...**
>
> This book is very much in development. Not everything here is going to be correct, some information may be added, some may be removed, a lot if it may be missing, and in general require editing work to be more pleasant to go through. Thanks for reading, and take care ❤️

## Prerequisites
There are a few assumptions I will be making about you, dear reader. I won't be explaining basic systems programming concepts, like what "kernel mode", "paging", or "interrupts" are. That being said, I will do my best to make this guide as accessible as possible to everyone, regardless of their low-level programming knowledge. 

While the UEFI specification defines the standard for multiple architectures, I will be sticking to **x86_64 only** in this guide. Most of the information here will apply everywhere anyway, but keep this in mind.
