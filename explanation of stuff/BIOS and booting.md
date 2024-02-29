External resources:
- https://wiki.osdev.org/Boot_Sequence

(this ignores UEFI, which is sort of like a BIOS but does some things differently, idk enough about it to write about it)

When a computer turns on a few things happen before the OS actually runs:

*add more to this*
- The computer does some self-tests
- The computer goes into a BIOS environment
- The BIOS tries to boot available boot devices in an order depending on its configuration
- The BIOS hands off execution to a boot record in an MBR (Master Boot Record)
- The MBR loads the rest of the Operating System
