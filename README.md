fakerpmrepo-generator
=====================

Creates a set of RPM packages between 1-1000KB in size with random names and versions read in from /usr/share/dict/words

Run the top level script:

$ ./generate-repo.py --numpackages=10
fungitoxicity
8.5.5
fungitoxicity-scratch/fungitoxicity-8.5.5
317+0 records in
317+0 records out
324608 bytes (325 kB) copied, 0.0536074 s, 6.1 MB/s
fungitoxicity-8.5.5/
fungitoxicity-8.5.5/fungitoxicity-dummy-data
toxicity-8.5.5/fungitoxicity-test-file.txt
Executing(%prep): /bin/sh -e /var/tmp/rpm-tmp.vvNoit
+ umask 022
+ cd /home/mmccune/rpmbuild/BUILD
...

===========================================================
Your new fake repo is available at: /var/tmp/generated-repo

$ ls /var/tmp/generated-repo/
abstemious-10.2.0-1.elfake.noarch.rpm    kamahi-9.8.3-1.elfake.noarch.rpm        steadfast-4.7.6-1.elfake.noarch.rpm
alimony-4.10.6-1.elfake.noarch.rpm       mammose-5.6.4-1.elfake.noarch.rpm       straight-shooting-8.2.5-1.elfake.noarch.rpm
bodyplate-8.0.8-1.elfake.noarch.rpm      matthean-5.8.4-1.elfake.noarch.rpm      tattletale-6.7.8-1.elfake.noarch.rpm
cherry-lipped-0.6.8-1.elfake.noarch.rpm  Meara-0.10.2-1.elfake.noarch.rpm        tawny-visaged-8.0.2-1.elfake.noarch.rpm
chilicote-3.5.3-1.elfake.noarch.rpm      mouldiest-3.9.3-1.elfake.noarch.rpm     teagle-0.5.0-1.elfake.noarch.rpm
Crescas-1.4.9-1.elfake.noarch.rpm        Parcel-greek-6.4.3-1.elfake.noarch.rpm  unascendent-1.1.10-1.elfake.noarch.rpm
daggy-0.4.7-1.elfake.noarch.rpm          perilunes-3.5.2-1.elfake.noarch.rpm     ungranulated-4.7.7-1.elfake.noarch.rpm
extrajudicial-6.4.7-1.elfake.noarch.rpm  Pro-teutonic-2.3.3-1.elfake.noarch.rpm  waged-10.8.3-1.elfake.noarch.rpm
filose-0.1.2-1.elfake.noarch.rpm         raffinate-1.3.3-1.elfake.noarch.rpm     Werner-10.0.5-1.elfake.noarch.rpm
gay-colored-1.3.1-1.elfake.noarch.rpm    rayah-5.6.0-1.elfake.noarch.rpm
Hawkeye-10.0.8-1.elfake.noarch.rpm       repodata

