# WARNING: This is the root branch, IT REMOUNTS / AS RW.
# This can break seal, if u are on A12+ DO NOT RUN THIS.
# You'll BRICK and not be able to RESTORE ( even via DFU mode ).
# Only use this in the proper enviroment.

don't use this if you don't know what ur doing. this isn't a jailbreak. this will merely strap procursus. as of now no tweaks will work. hardly any packages. hardly any repos. for developers to mess about with. have fun 

all this code is dog shit, it's thrown together with a knife and fork because quite frankly i don't give a fuck and neither should you. queen of ui design

out of sheer laziness this uses [SWCompression](https://github.com/tsolomko/SWCompression) for opening up the tar file 

to build just run `make` in root, needs xcode and other shittery

if u can't build ipa, use [nightly.link](https://nightly.link/elihwyma/Pogo/workflows/build/main/Pogo) or the artifact.

to install, boot ios with a modified kernel that disables amfi, open this ipa in trollstore and then press install

if u want a repo, add mineek.github.io/repo, it's not signed atm so make sure to do apt update --allow-insecure-repositories (if using sileo it works already, make sure to NOT open issues at procursus when using rootless.)

because of licensing issues, i can't include every deb, so if u want to compile Pogo yourself, you'll need to download the following debs and put them in the Required folder:

libswift

preferenceloader

safemode

substitute
