[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/fcddc7cdcf13e0805f68e8d22bbc1a83 "githalytics.com")](http://githalytics.com/grenaud/freeIbis)

=================================================
  freeIbis - Improved Base Identification System
=================================================

* Documentation
See https://github.com/grenaud/freeIbis/ for a detailed description and our
wiki (https://github.com/grenaud/freeIbis/wiki) documentation.

* INSTALLATION

In the same folder as this README, there are also three other folders,
run the following commands:

$ make

This should build the required binaries for freeIbis. Be sure you have bgzip (http://samtools.sourceforge.net/tabix.shtml ) installed and in your path as freeIbis requires this to generate bam files. Try typing "bgzip -h" to see if it works. 

You may now edit params.py in the current directory to change default values.
In most cases this is not necessary, however if your /tmp folder does not have
at least 30 Gb free disk space, you should use another default temp folder.

Base calling should typically be started using

./runBaseCalling.py

This should give you the list of options. Ideally, you will only need a few of them.
However, you should check the website above for details.

Enjoy using freeIbis.
