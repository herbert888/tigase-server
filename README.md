<p align="center">
  <a href="https://tigase.net/">
    <img
      alt="Highly optimized, extremely modular and very flexible XMPP/Jabber server"
      src="https://github.com/tigaseinc/website-assets/blob/master/tigase/images/tigase-logo.png?raw=true"
      width="300"
    />
  </a>
</p>

<p align="center">
  Highly optimized, extremely modular and very flexible XMPP/Jabber server
</p>

<p align="center">
  <img alt="Tigase Tigase Logo" src="https://github.com/tigaseinc/website-assets/blob/master/tigase/images/tigase-logo.png?raw=true" width="25"/>
  <img src="https://tc.tigase.net/app/rest/builds/buildType:(id:TigaseServer_Build)/statusIcon" width="100"/>
</p>

# What it is

Tigase XMPP Server is highly optimized, extremely modular and very flexible XMPP/Jabber server written in Java.

This repository contains source code of the main part of the Tigase XMPP Server.

# Features

Tigase XMPP Server contains full support for [RFC 6120 - XMPP CORE](http://xmpp.org/rfcs/rfc6120.html), [RFC 6121 - XMPP IM](http://xmpp.org/rfcs/rfc6120.html) and [RFC 7395 - XMPP over WebSockets](https://tools.ietf.org/html/rfc7395) making it accessible using XMPP client connections:
* over TCP
* over HTTP/HTTPS (BOSH)
* over WebSockets

and over server-to-server connections as well as over XMPP component connections.

Additionally Tigase XMPP Server provides HTTP API for integration with other services unable to communicate over XMPP.

Moveover, Tigase XMPP Server comes with support for Push Notifications making it possible to push notification to mobile devices.

Following features are supported by Tigase XMPP Server:
* [XEP-0016: Flexible Offline Message Retrieval](http://xmpp.org/extensions/xep-0016.html)
* [XEP-0030: Service Discovery](http://xmpp.org/extensions/xep-0030.html)
* [XEP-0045: Multi User Chat](http://xmpp.org/extensions/xep-0045.html)
* [XEP-0060: Publish-Subscribe](http://xmpp.org/extensions/xep-0060.html)
* [XEP-0079: Advanced Message Processing](http://xmpp.org/extensions/xep-0079.html)
* [XEP-0114: Jabber Component Protocol](http://xmpp.org/extensions/xep-0114.html)
* [XEP-0115: Entity Capabilities](http://xmpp.org/extensions/xep-0115.html)
* [XEP-0133: Service Administration](http://xmpp.org/extensions/xep-0133.html)
* [XEP-0136: Message Archiving](http://xmpp.org/extensions/xep-0136.html)
* [XEP-0163: Personal Eventing Protocol](http://xmpp.org/extensions/xep-0163.html)
* [XEP-0198: Stream Management](http://xmpp.org/extensions/xep-0198.html)
* [XEP-0199: XMPP Ping](http://xmpp.org/extensions/xep-0199.html)
* [XEP-0206: XMPP over BOSH](http://xmpp.org/extensions/xep-0206.html)
* [XEP-0225: Component Connections](http://xmpp.org/extensions/xep-0225.html)
* [XEP-0237: Roster Versioning](http://xmpp.org/extensions/xep-0237.html)
* [XEP-0280: Message Carbons](http://xmpp.org/extensions/xep-0280.html)
* [XEP-0313: Message Archive Management](http://xmpp.org/extensions/xep-0313.html)
* [XEP-0357: Push Notifications](http://xmpp.org/extensions/xep-0357.html)
* [XEP-0363: HTTP File Upload](http://xmpp.org/extensions/xep-0363.html)
* and many more...

# Support

When looking for support, please first search for answers to your question in the available online channels:

* Our online documentation: [Tigase Docs](https://docs.tigase.net)
* Our online forums: [Tigase Forums](https://help.tigase.net/portal/community)
* Our online Knowledge Base [Tigase KB](https://help.tigase.net/portal/kb)

If you didn't find an answer in the resources above, feel free to submit your question to either our 
[community portal](https://help.tigase.net/portal/community) or open a [support ticket](https://help.tigase.net/portal/newticket).

# Downloads

You can download distribution version of the Tigase XMPP Server directly from [here](https://github.com/tigaseinc/tigase-server/releases).

If you wish to downloand SNAPSHOT build of the development version of Tigase XMPP Server you can grab it from [here](https://build.tigase.net/nightlies/dists/latest/tigase-server-dist-max.zip).

# Installation and usage

Documentation of the project is part of the Tigase XMPP Server distribution package. Quickstart guide is also available [here](https://docs.tigase.net/tigase-server/snapshot/Administration_Guide/html/#QuickStart).

# Compilation 

Compilation of the project is very easy as it is typical Maven project. All you need to do is to execute
````bash
mvn package test
````
to compile the project and run unit tests.

# License

<img alt="Tigase Tigase Logo" src="https://github.com/tigaseinc/website-assets/blob/master/tigase/images/tigase-logo.png?raw=true" width="25"/> This is official <a href="https://tigase.net/">Tigase</a> Repository.
Copyright (c) 2013-2019 Tigase, Inc.

Licensed under AGPL License Version 3. Other licensing options available upon request.