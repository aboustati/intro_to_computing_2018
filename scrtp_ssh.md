# SCRTP

The SCRTP manages high performance computing (HPC) facilities that are available for you to use.  First you will need an SCRTP account (which differs from, but requires your normal Warwick ITS account).  Obtain your SCRTP account [here](https://warwick.ac.uk/research/rtp/sc/desktop/gettingstarted).

# Facilities Available

## Complexity SCRTP Machines

The list of hostnames for the complexity SCRTP machines are:

adobo     bulalo   halabos

inihaw    jamon    kinilaw 

niliga    okoy     pinakbet

sinuglaw  rilyeno  galunggong

You can access these machines using the following command in terminal,

ssh username@hostname.complexity.warwick.ac.uk

Once you have your scrtp account, try accessing one of the complexity machines.

## Cluster of Workstations (CoW)
The CoW is a set of Linux desktops that you access remotely.

The main node of the CoW is called godzilla, which can be accessed using,

ssh username@godzilla.csc.warwick.ac.uk

but note, **do not** run scripts directly on godzilla (instead you submit jobs, but this wil l be explained in a computational techniques session).

Once you have your scrtp account, try accessing godzilla.

## Chiron, Orac, Tinis

These are three supercomputers that you have to register for access for separately (no need to do so now, can take a while to obtain access).  The three main strengths of these machines are as follows ([more information](https://warwick.ac.uk/research/rtp/sc/hpc/)):

Orac -> Parallel computing

Tinis -> Parallel computing and GPU computing

Chiron -> Large amount of memory, big data