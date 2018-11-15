Hey everyone,

Most of my time has been put toward setting up CrashSimulator using the dockerfile, then on a 32 bit VM, then finally abandoning them both to use the VMWARE image provided by Preston/Alex.

* Looked at the commands: which, touch, pidof

* Ran into NotImplementedError for syscall geteuid when testing which. Opening issues to fix this and other syscalls not yet implemented.

* Could not get pidof to fail using filetype anomalies

* touch command doesn't have exploitable filetype or time anomalies.
