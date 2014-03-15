Nyandroid Daydream
==================

About
------

This project is a modification of the Nyandroid portion of [Zhuowei Zhang]’s [original nyandroid source].  It replaces the Nyandroid sprites with Bruce The Wonder Yak (and old Apple Final Cut Pro easter egg).


This project is a re-package of certain code, with some modifications,
from the [Android Open Source Project (AOSP)][AOSP], with the aim of allowing users of newer
versions of Android to enjoy the easter eggs of years past.

[AOSP]: https://android.googlesource.com

This app installs one app drawer shortcut and one daydream for the modified Nyandroid.

It can be found on the Play Store under the name [Bruce The Wonder Yak][applink],
published by [Alex Brofsky][].


[original nyandroid source]: https://github.com/zhuowei/nyandroid-daydream
[applink]: https://play.google.com/store/apps/details?id=com.alexbrofsky.nyandroid
[Zhuowei Zhang]: https://github.com/zhuowei
[Alex Brofsky]: https://plus.google.com/u/0/+AlexBrofsky

Building
--------
To build the code, it can be imported into Eclipse:
(This abbreviated list of steps assumes some knowledge of Git and Android Devlopement, as well as a set-up environment.)

1. Get the code
2. Open Eclipse (with the ADT installed, download [here][SDK_Bundle])
3. File -> New -> Other
4. Select "Android Project from Existing Code"
5. Point Eclipse at the folder where you put the code, then click through the import screens
6. Run from Eclipse (See [here][BuildAndRun] for more info)

(The .gitignore file should keep Eclipse files from getting tangled up in git.)

[SDK_Bundle]: https://developer.android.com/
[BuildAndRun]: https://developer.android.com/tools/building/building-eclipse.html#RunningOnDeviceEclipse

