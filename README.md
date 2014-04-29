# VMWare Fusion Headless Helper

VMWare Fusion is not very friendly sometimes.

This wraps vmrun slightly for starting and stopping headless vm's from the command line using friendly names and not full paths

Before:
    /Applications/VMware Fusion.app/Contents/Library/vmrun start $HOME/Documents/Virtual\ Machines.localized/<vmname>.vmwarevm/<vmname>.vmx nogui

After:
    vm start <vmname>

## Features
- start vms
- sustpend vms
- list running vms

## Maintainer Contacts

* Tim Noise <tim@drkns.net>

## Requirements

- OSX
- VMWare Fusion, tested approx 1 time using 6.x

## Installation

* Clone repository
* Add vm script to $PATH however you like it or just ./ it

## Usage

start a headless vm:
    vm start <vmname>

suspend a headless vm:
    vm stop <vmname>

list running vms:
    vm list

## FAQ
Q: Cant I already do all this stuff and more with vmrun ?
A: Yes, but you have to do more typing

Q: Can I start headless VM's from the Fusion GUI?
A: Not that I could find easily.

Q: This Doesn't Do X and could be better if Y
A: Good idea! fork it.

Q: Did you even test this?
A: Not really.