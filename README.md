AOSP 4.3 FOR Galaxy S4
===============================



Download:
------------------
* mkdir ~/oct
* cd ~/oct
* repo init -u git://github.com/Project-OctOS/manifest -b jb-4.3
* repo sync


Building(n=#cores-1):
--------------------
* build/envsetup.sh
* lunch
* make otapackage -j(n)
