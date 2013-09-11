AOSP 4.3 FOR Galaxy S4
===============================



Download:
------------------
* mkdir ~/OctOS
* cd ~/OctOS
* repo init -u git://github.com/Team-OctOS/android -b jb-4.3
* repo sync


Building(n=#cores-1):
--------------------
* build/envsetup.sh
* lunch
* make -j(n)
