## Meta
* Project: sort
* Current Stage: Bug reported
* Link to Bug on Project Bug Tracker: https://bugs.launchpad.net/ubuntu/+source/coreutils/+bug/1807295
* Brief description: 

description


## Updates


### Week 3

**Current Stage: Bug Identified**

Potential lack of handling for block file type. Sort application may be responding to char filetype somewhere. But have not found any checks in the source code. Going to work on a patch to filter blk, chr and fifo.

### Week 4

**Current Stage: Testing Patch**

Testing patch to check file type and die on unsupported file types.

### Week 5

**Current Stage: Submitted Bug Report**

Created a [bug report](https://bugs.launchpad.net/ubuntu/+source/coreutils/+bug/1807295) on Launchpad for Ubuntu maintainers to look at.
