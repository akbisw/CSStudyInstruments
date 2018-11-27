# Week 2 Progress Report

After getting the hang of crash simulator, this week I'm testing which, zipinfo, HEAD, groups, sort.

* Submitted an [issue for implementing faccessat](https://github.com/pkmoore/rrapper/issues/42) and Preston added a patch to fix. Now it can be replayed without an issue.

* Submitted an [issue for UnusualFiletype mutator](https://github.com/pkmoore/rrapper/issues/48) and Preston fixed the bug in record time.

* Submitted an [issue for 85(readlink) syscall support](https://github.com/pkmoore/rrapper/issues/50) and Preston pushed a fix.

* which: Ran into issues while using the mutator option. Opened issues and preston fixed them.

* HEAD: time() is called 197,1381,3291,4193,4329. Trace snips are too long and ran into trouble with crashisim hitting a possible bug.

* zipinfo: Crashed as it should when testing file type anomalies.

* sort: blk does not get handled, but chr does. 100% utilization on /dev/urandom

* groups: Handles file type anomalies to /etc/group as expected and nothing else to it.
