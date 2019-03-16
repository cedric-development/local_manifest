# local_manifests for this repos
There it is some changes to use a stable source to build AOSP-Based ROMs on cedric.

## How can i add this to my common repo sync?
by just ctrl+c and ctrl+v this:
```
curl --create-dirs -L -o .repo/local_manifests/aosp.xml -O -L https://raw.githubusercontent.com/cedric-development/local_manifest/master/aosp.xml
```
## For LineageOS based ROMs:
```
curl --create-dirs -L -o .repo/local_manifests/lineage.xml -O -L https://raw.githubusercontent.com/cedric-development/local_manifest/master/lineage.xml
```
