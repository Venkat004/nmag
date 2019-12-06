# nmag
NMAG - Micromagnetic modelling tool based on finite elements

## Update 2019

Nmag has not been activily developed further since around 2012. However, it is still in use 
by several research groups; citations for the nmag paper are around 185 (Web of Science) 
and 300 (Google Scholar) at the end of 2019.

### What is the status of the software?

It is essentially usable: the deployment method chosen has proved surprisingly robust. 
Based on a tarball of all required libraries, Nmag can be compiled with a little bit of care and manual corrections

Nmag documentation is available at https://nmag.soton.ac.uk/nmag/ and in the Wiki at https://nmag.soton.ac.uk/community/wiki/nmag

Binaries are avaialble at https://nmag.soton.ac.uk/nmag/download.html

### What needs doing 

- The server nmag.soton.ac.uk needs to be decommissed. It would be good to take all data on there, 
  and make it available elsewhere. This includes the documentation, the content of the Wiki and maybe binaries. 
  
  - Static html could go to nmag.github.io (or similar)
  - Wiki content needs to be converted into static html (unless someboy wants to run a Wiki or can convert this into a github Wiki)
  - binary files should be presereved on Zenodo

- The compilation as described on the current webpages doesn't work automatically. 
  It would be good if this could be fixed and a fixed version made available.
  There are patches available (for example https://groups.google.com/forum/#!topic/nmag-users/XglwvaFdQs8), somebody 
  needs to integrate them, and ideally create a new tarball that extracst and copmiles out of the box (at least on Linux, 
  ideally also on OS X).
  
## Help needed!

The original developers had to move on to other tasks. This is a call to the Nmag users: those with interest and/or skill to hepl with the above
tasks, please step forward and contact ...