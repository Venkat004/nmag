# nmag
NMAG - Computationall Micromagnetics [Micromagnetic modelling tool based on finite elements]

# "Nmag Migration 2020"

Nmag has not been activily developed further since around 2012. However, it is still in use 
by several research groups; citations for the nmag paper are around 185 (Web of Science) 
and 300 (Google Scholar) at the end of 2019.

## What is the status of the software?

It is essentially usable: the deployment method chosen has proved surprisingly robust. 
Based on a tarball of all required libraries, Nmag can be compiled with a little bit of care and manual corrections, but doesn't work out of the box.

Nmag documentation is available at https://nmag.soton.ac.uk/nmag/ and in the Wiki at https://nmag.soton.ac.uk/community/wiki/nmag

Binaries are avaialble at https://nmag.soton.ac.uk/nmag/download.html

## What needs doing 

- The server nmag.soton.ac.uk needs to be decommissed. It would be good to take all data on there, 
  and make it available elsewhere. This includes the documentation, the content of the Wiki and binaries. 

- The compilation as described on the current webpages doesn't work automatically. 
  It would be good if this could be fixed and a fixed version made available.
  There are patches available (for example https://groups.google.com/forum/#!topic/nmag-users/XglwvaFdQs8), somebody 
  needs to integrate them, and ideally create a new tarball that extracst and copmiles out of the box (at least on Linux, 
  ideally also on OS X).
  
See below for a more detailed breakdown of the required tasks.
  
## Help needed!

The original developers had to move on to other tasks. 

This is a call to the Nmag users: those with interest and/or skill to hepl with the above
tasks, please step forward and contact nmag.project@gmail.com to offer to help. 

# Status of migration 2020

### Todo

- [ ] move nmag webpage to nmag.github.io (https://github.com/fangohr/nmag/issues/1)
- [ ] update tar-ball to compile automatically and make available (https://github.com/fangohr/nmag/issues/2)
- [ ] Update the new webpages to point to new URLs (https://github.com/fangohr/nmag/issues/3)
- [ ] Save information from https://nmag.soton.ac.uk/community/wiki/nmag (https://github.com/fangohr/nmag/issues/4)
- [ ] Shut down old server (https://github.com/fangohr/nmag/issues/5)

### Completed

- [X] The documentation from https://nmag.soton.ac.uk/nmag/0.2/manual/singlehtml/manual.html is available at http://nmag.readthedocs.io/en/latest/. The source of the documentation is available at https://github.com/fangohr/nmag-doc. Thanks @rpep for this.

### Optional activities

- [ ] Compile Nmag in container (https://github.com/fangohr/nmag/issues/6)

--------------

# Related information

- Virtual micromagnetics provides a compiled version of Nmag in a virtual machine (http://virtualmicromagnetics.org)

- Recent paper reviewing Nmag; comments on installation: https://arxiv.org/abs/1601.07392, section 4.12
