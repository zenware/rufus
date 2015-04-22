# Rufus: The Reliable USB Formatting Utility

1. [Features](#features)
2. [Compiling](#compiling)
3. [Additional Information](#additional-information)
4. [Enhancements / Bugs](#enhancements-and-bugs)

## Features
- Formats USB flash drives as well as VHD images to FAT/FAT32/NTFS/UDF/exFAT/ReFS
- Creates DOS bootable USB drives, using FreeDOS or MS-DOS with no external files required
- Creates MBR or GPT/UEFI bootable drives, including UEFI bootable NTFS
- Creates bootable drives from bootable ISOs (Windows, Linux, etc.)
- Creates bootbale drives from disk images, including compressed ones
- Creates Windows To Go drives
- [Twice as fast as Microsoft's USB/DVD tool or UNetbootin, on ISO->USB](#benchmarks)
- Can perform bad blocks check, with fake drive detection
- Modern and familiar UI, with [more than 30 languages natively supported][translations]
- Small footprint, no installation required
- 100% Free Software (GPL v3)

## Compiling
  Use either Visual Studio 2013, WDK 7.1 (Windows Driver Kit) or MinGW and then
  invoke the .sln, wdk_build.cmd or configure/make respectively.

  Note that, since Rufus is an OSI compliant Open Source project, you are entitled to
  download and use the **freely available** Visual Studio 2013 Community Edition to
  build, run or develop for Rufus. As per the Visual Studio Community Edition license
  this applies regardless of whether you are an individual or a corporate user.
  For details, see [Visual Studio Community][] or [This Blog Entry][vs-blog-entry]

## Additional information
  Rufus provides extensive information about what it is doing, either through
  its easily accessible log, or through the Windows debug facility.
- [Main Website][]
- [Frequently Asked Questions][]

## Enhancements and Bugs
  [Github Issues][]

## Benchmarks
    Tests carried out with a 16 GB USB 3.0 ADATA pen drive on a
    Core 2 duo/4 GB RAM platform running Windows 7 x64.
    ISO: en_windows_7_ultimate_with_sp1_x64_dvd_618240.iso
    - Windows 7 USB/DVD Download Tool v1.0.30:  8 mins 10s
    - UNetbootin v1.1.1.1:                      6 mins 20s
    - Rufus v1.1.0:                             3 mins 25s

[Visual Studio Community]: http://www.visualstudio.com/products/visual-studio-community-vs "VS Community Edition 2013"
[vs-blog-entry]: http://pete.akeo.ie/2014/11/visual-studio-2013-has-now-become.html "Visual Studio has become essentially free..."
[translations]: http://rufus.akeo.ie/translations
[Github Issues]: https://github.com/pbatard/rufus/issues "Github Issues"
[Frequently Asked Questions]: https://github.com/pbatard/rufus/wiki/FAQ "Github Wiki FAQ"
[Main Website]: http://rufus.akeo.ie "Rufus - Create bootable USB drives the easy way"
