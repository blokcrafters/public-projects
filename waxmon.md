<h2>BlokCrafters WAX Blockchain Monitor</h2>

<h1>Description</h1>
BlokCrafters is working on development of a monitoring and alert system for the WAX Blockchain
that will be freely available for other to implement for their own use or to easily integrate
with for ease of use and administration.

<h1>The Problem</h1>
Currently there are no systems readily available for a WAX Guild to install and use for
monitoring their systems and nodes.  Each guild is responsible for building out their own
monitoring and alert system, and then maintaining it.  This problem should not exist and
is relatively easy to fix.  We aim to produce a monitoring and alert system for blockchain
guilds that is easy to integrate into existing systems.

<h1>Project Roadmap</h1>

<h3>Backbone</h3>

ZooKeeper Ensemble

* ~~5 machine ensemble setup and running~~ completed

<h3>Monitoring</h3>

WaxMon

* ~~easy to configure monitor system feeds heartbeat data to zookeeper~~ completed
* Add certificate based access
 * Allow for other guild integration and security

<h3>Alert</h3>

Build an easy to configure alert system

* Send alerts to a slack channel
* Send alerts to a telegram channel
* Send text messages to a cell phone number

<h3>Status</h3>

WebWaxMon

* Web Frontend for viewing system status of zookeeper information

<h1>Development Team Members</h1>

* Dan Dickey
  * dan@blokcrafters.com
  * https://t.me/BlokCrafterDan
