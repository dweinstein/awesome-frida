# Awesome Frida [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome projects, libraries, and tools powered by Frida.

## What is Frida?

Frida is [Greasemonkey](https://en.wikipedia.org/wiki/Greasemonkey) for native apps, or, put in more technical terms, it’s a dynamic code instrumentation toolkit. It lets you inject snippets of JavaScript into native apps that run on Windows, Mac, Linux, iOS and Android.

Frida is an open source software.

More info [here](http://www.frida.re/).

## Table of Contents

<!-- MarkdownTOC depth=4 -->
- [Libraries](#libraries)
- [Projects](#projects)
- [Talks & Papers](#talks-and-papers)
- [Powered by Frida](#frida-powered-by)
- [Videos](#videos)
- [Blog posts](#blogs)
- [Community](#community)

<!-- /MarkdownTOC -->

<a name="libraries" />

## Libraries
* [frida-android-hooks](https://github.com/antojoseph/frida-android-hooks) - Hook method calls in Android
* [FridaAndroidTracer](https://github.com/Piasy/FridaAndroidTracer) - A runnable jar that generate Javascript hook script to hook Android classes
* [frida-panic](https://github.com/nowsecure/frida-panic) - Easy crash-reporting for Frida-based applications
* [frida-compile](https://github.com/frida/frida-compile) - Compile a Frida script comprised of one or more Node.js modules
* [frida-trace](https://github.com/nowsecure/frida-trace) - Trace APIs declaratively
* [frida-screenshot](https://github.com/nowsecure/frida-screenshot) - Grab (iOS) screenshots
* [frida-uiwebview](https://github.com/nowsecure/frida-uiwebview) - Inspect and manipulate UIWebView-hosted GUIs
* [frida-uikit](https://github.com/nowsecure/frida-uikit) - Inspect and manipulate UIKit-based GUIs
* [frida-contrib](https://github.com/dweinstein/node-frida-contrib) - Frida utility-belt
* [frida-load](https://github.com/frida/frida-load) - Load a Frida script comprised of one or more Node.js modules (Deprecated, use [frida-compile](https://github.com/frida/frida-compile))
* [frida-remote-stream](https://github.com/nowsecure/frida-remote-stream) - Create an outbound stream over a message transport.
* [frida-memory-stream](https://github.com/nowsecure/frida-memory-stream) - Create a stream from one or more memory regions.
* [frida-fs](https://github.com/nowsecure/frida-fs) - Create a stream from a filesystem resource.
* [frida-push](https://github.com/AndroidTamer/frida-push) - Automatically `adb push` the correct frida-server matching your current frida installation.

<a name="projects" />

## Projects
- [as0ler/frida-scripts](https://github.com/as0ler/frida-scripts) - Repository including some useful frida script for iOS Reversing
- [0xdea/frida-scripts](https://github.com/0xdea/frida-scripts) - instrumentation scripts to facilitate reverse engineering of android and iOS Apps.
- [roxanagogonea/frida-scripts](https://gitlab.com/roxanagogonea/frida-scripts) - Repository including some useful frida scripts for Android
- [iddoeldor/frida-snippets](https://github.com/iddoeldor/frida-snippets) - another useful frida snippets repository
- [IDA Pro plugin](https://github.com/techbliss/Frida_For_Ida_Pro) - IDA Pro plugin
- [poxyran/misc](https://github.com/poxyran/misc) - Misc Frida scripts [read-process-memory.py](https://github.com/poxyran/misc/blob/master/frida-read-process-memory.py), [write-process-memory.py](https://github.com/poxyran/misc/blob/master/frida-write-process-memory.py), [frida-heap-trace](https://github.com/poxyran/misc/blob/master/frida-heap-trace.py),
- [frida-cycript](https://github.com/nowsecure/frida-cycript) - Fork of cycript with new runtime called [Mjølner](https://github.com/nowsecure/mjolner) powered by Frida.
- [r2frida](https://github.com/nowsecure/r2frida) - static and dynamic analysis synergy
- [ios-inject-custom](https://github.com/oleavr/ios-inject-custom) - use Frida for standalone injection of a custom payload for iOS.
- [davuxcom/frida-scripts](https://github.com/davuxcom/frida-scripts) - Repository including scripts for COM, .NET and WinRT for Windows

<a name="talks-and-papers" />

## Talks & Papers
* [OSDC 2015](http://act.osdc.no/osdc2015no/):
  [Putting the open back into closed software](http://act.osdc.no/osdc2015no/talk/6165)
  ([PDF](osdc-2015-putting-the-open-back-into-closed-software.pdf) · [Recording](https://youtu.be/tmpjftTHzH8))
* [OSDC 2015](http://act.osdc.no/osdc2015no/):
  [The engineering behind the reverse engineering](http://act.osdc.no/osdc2015no/talk/6195)
  ([PDF](osdc-2015-the-engineering-behind-the-reverse-engineering.pdf) · [Recording](https://youtu.be/uc1mbN9EJKQ))
* [NLUUG 2015](https://www.nluug.nl/activiteiten/events/nj15/index.html):
  [Frida: Putting the open back into closed software](https://www.nluug.nl/activiteiten/events/nj15/abstracts/ab08.html)
  ([Slides](http://slides.com/oleavr/nluug-2015-frida-putting-the-open-back-into-closed-software)
  · [Demos](https://github.com/frida/frida-presentations/tree/master/NLUUG2015)
  · [Recording](https://youtu.be/3lo1Y2oKkE4))
* [ZeroNights 2015](http://2015.zeronights.org/):
  [Cross-platform reversing with Frida](http://2015.zeronights.org/workshops.html)
  ([PDF](zeronights-2015-cross-platform-reversing-with-frida.pdf)
  · [Demos](https://github.com/frida/frida-presentations/tree/master/ZeroNights2015))
* [r2con 2016 - r2frida](http://rada.re/con/) ([PDF](https://github.com/radareorg/r2con/raw/master/2016/talks/08-r2frida/r2frida.pdf) · [Recording](https://www.youtube.com/watch?v=ivCucqeVeZI))
* [RMLL 2017](https://2017.rmll.info/) Unlocking secrets of proprietary software (@oleavr) ([slides](https://slides.com/oleavr/frida-rmll-2017#/) · [Recording](https://rmll.ubicast.tv/videos/frida_03038/))

<a name="frida-powered-by" />

## Powered by Frida
* [Aurora](https://github.com/frida/aurora) - Web app built on top of Frida
* [CloudSpy](https://github.com/frida/cloudspy) - Web app built on top of Frida
* [CryptoShark](https://github.com/frida/cryptoshark) - Self-optimizing cross-platform code tracer based on dynamic recompilation
* [diff-gui](https://github.com/antojoseph/diff-gui) - Web GUI for instrumenting Android
* ~~[Lobotomy](https://github.com/LifeForm-Labs/lobotomy)~~[Lobotomy Fork](https://github.com/AndroidSecurityTools/lobotomy) - Android Reverse Engineering Framework & Toolkit
* [Appmon](https://github.com/dpnishant/appmon) - Runtime Security Testing Framework for iOS, Mac OS X and Android Apps
* [Fridump](https://github.com/Nightbringer21/fridump) - A universal memory dumper using Frida
* [frida-extract](https://github.com/OALabs/frida-extract) - Automatically extract and reconstruct a PE file that has been injected using the RunPE method
* [r2frida](https://github.com/nowsecure/r2frida) [memory search](https://www.nowsecure.com/blog/2017/03/14/spearing-data-mobile-memory-building-better-r2frida-memory-search/)
* [r2frida-wiki](https://github.com/enovella/r2frida-wiki) - Unofficial wiki that provides practical examples on how to use r2frida
* [google/ssl_logger](https://github.com/google/ssl_logger) - Decrypts and logs a process's SSL traffic.
* [google/tcp_killer](https://github.com/google/tcp_killer) - Shuts down a TCP connection based using output from a `netstat` cmd.
* [brida](https://github.com/federicodotta/Brida) - Bridge between Burp Suite and Frida
* [objection](https://github.com/sensepost/objection) - Runtime Mobile Exploration for iOS and Android
* [passionfruit](https://github.com/chaitin/passionfruit) - iOS App Analyzer with Web UI
* [House](https://github.com/nccgroup/house) - A runtime mobile application analysis toolkit with a Web GUI, powered by Frida
* [Dwarf](https://github.com/igio90/Dwarf) - A debugger built on top of PyQt5 and frida
* [Dexcalibur](https://github.com/FrenchYeti/dexcalibur) - A dynamic binary instrumentation tool designed for Android apps and powered by Frida
* [bagbak](https://github.com/ChiChou/bagbak) - Decrypt apps from AppStore on jailbroken devices. Supports decrypting app extensions.

<a name="videos" />

## Videos
* [Frida vs Spotify](https://www.youtube.com/watch?v=dvOdwHpQycw) - Spotify RE
* [CryptoShark](https://www.youtube.com/watch?v=hzDsxtcRavY) - a self-optimizing cross-platform code tracer based on dynamic recompilation, powered by Frida and Capstone
* [Frida Memory Hacking - Angry Birds](https://www.youtube.com/watch?v=nk3rUn2ip0g) - Frida having fun with Angry Birds running on an iPhone
* [Frida Memory Hacking - Windows Live Messenger](https://www.youtube.com/watch?v=0Blc0T-Z-ys) - Frida having fun with Windows Live Messenger
* [Frida Intro @ NowSecure](https://www.youtube.com/watch?v=4Ag-2LZQM8g) - Frida introduction by Ole
* ~~[Lobotomy - Frida Demo](https://asciinema.org/a/24269) - This demo is leveraging the Frida toolkit to instrument a target app's Activity calls.~~
* [Install SSL CA to device via ManagedConfiguration tracing](https://www.youtube.com/watch?v=qfOm5b9MZtk)

<a name="blogs" />

## Blog posts
* [Build a debugger in 5 minutes](https://medium.com/@oleavr/build-a-debugger-in-5-minutes-1-5-51dce98c3544#.mn48pvhok)
* [Reverse Engineering with Javascript](https://www.nowsecure.com/blog/2015/08/06/reverse-engineering-with-javascript/)
* [iOS 9 Reverse Engineering with Javascript](https://www.nowsecure.com/blog/2015/11/16/ios-9-reverse-engineering-with-javascript/)
* [iOS Instrumentation without Jailbreak](https://www.nowsecure.com/blog/2015/11/23/ios-instrumentation-without-jailbreak/)
* [Introduction to Fridump](http://pentestcorner.com/introduction-to-fridump/) - Fridump is an open source memory dumper tool
* [Hacking Android apps with Frida part1](https://www.codemetrix.net/hacking-android-apps-with-frida-1/), [part2/crackme](https://www.codemetrix.net/hacking-android-apps-with-frida-2/), [part3](https://www.codemetrix.net/hacking-android-apps-with-frida-3/)
* [OWASP iOS crackme tutorial: Solved with Frida](https://www.nowsecure.com/blog/2017/04/27/owasp-ios-crackme-tutorial-frida/)
* Detecting Frida [poxyran](https://crackinglandia.wordpress.com/2015/11/10/anti-instrumentation-techniques-i-know-youre-there-frida/), [Bernhard Mueller](http://www.vantagepoint.sg/blog/90-the-jiu-jitsu-of-detecting-frida)

<a name="community" />

## Community
* [Stack Overflow](http://stackoverflow.com/questions/tagged/frida)
* [@fridaotre on Twitter](https://twitter.com/fridadotre)
* [@oleavr on Twitter](https://twitter.com/oleavr)
* [Reddit](https://www.reddit.com/r/frida)
* [Frida CodeShare](https://codeshare.frida.re/) - Share frida snippets and recipes with others.


<a name="contributions" />

## Contributions
Your contributions are always welcome!

If you want to contribute to this list (please do), send me a pull request or contact me [@insitusec](https://twitter.com/insitusec)

Also, if you notice that a listing should be deprecated or replaced:

* Repository's owner explicitly say that "this library is not maintained".
* Not committed for long time (2~3 years).

More info on the [guidelines](https://github.com/dweinstein/awesome-frida/blob/master/CONTRIBUTING.md)


<a name="credits" />

## Credits

* This awesome list was originally based on [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow)
