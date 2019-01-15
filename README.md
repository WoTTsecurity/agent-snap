# (Ubuntu) Snap for WoTT Agent

Packages the WoTT Agent into a Snap.


## Installing

```
$ snap install wott-agent
```

##Running
```
$snap start wott-agent
```

## Building


```
$ snapcraft cleanbuild
$ snapcraft push --release=candidate wott-agent*.snap
```
