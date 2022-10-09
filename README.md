# JARC - Just Another Remote Controller

*This is a work in progress, and there is no deadline*

JARC aims to create automatic code from a JSON file to remotelly control another device. The idea is to generate code from the JSON for both a server and a client and enable the client to control a remote device via a curses-based interface.

## Goal

The main goal is to implement a simple protocol (instead of something bigger such as SNMP) to be able to work better with embedded systems using Linux.

## Milestones

The first milestones aim to validate the project, based on the rpi.json file.

[ ] Create a basic code to control some pins of a Raspberry Pi
	[ ] Create server code with callbacks
	[ ] Create client code controlled via command line
[ ] Implement the interface
	[ ] Implement a fixed interface with ncurses, similar to Kconfig
	[ ] Implement the message transfer (UDP, TCP...)
[ ] Implement the code generation
	[ ] Parse the JSON
	[ ] Implement derived classes based on the JSON
