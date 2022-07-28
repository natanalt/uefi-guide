# Quick overview of UEFI
UEFI, or the *Unified Extensible Firmware Interface*, is a standardization of computer firmware. It's meant to replace old firmware designs, often referred to as the *legacy BIOS* or just the BIOS. There are many good reasons to get rid of the legacy stuff. The BIOS wasn't really standardized, its behavior varied across vendors, it required starting the bootloader in what's effectively an 8086 compatbility mode, and it abstracted hardware in a really poor way. The list of complaints can just keep growing.

This specification tries to replace the BIOS with a well defined specification, allowing for programming in C or a C compatible language, and in general just being less of a pain... or at least that's the theory. In reality UEFI has a lot of issues, we still have cases of behavior varying between vendors, and whatever else. Criticisms of UEFI surely deserve a dedicated chapter.

UEFI is a rather complex piece of firmware. It specifies support for a lot of potential features, starting with basic runtime utilities, ending at a whole network stack. The UEFI specification is **large**, with UEFI 2.9 reaching over 2500 pages of length for just the base specification — most of it being code descriptions of various protocols.

Explaining every single supported functionality would be impossible to do here, but once you get confident enough with UEFI, you should be able to comfortably read API specifications for built-in protocols.

> **UEFI or EFI?**
> 
> UEFI started off as just EFI, or the *Extensible Firmware Interface*. At some point, it transitioned into UEFI we have today. Nowadays, both names refer to basically the same thing.

## Boot Manager

## UEFI shell

## Core protocols and services

## UEFI executables
