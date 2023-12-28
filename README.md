# awesome-systemd
A curated list of awesome projects that provide systemd-like functionality

## polkit
* [consolekit2](https://github.com/ConsoleKit2/ConsoleKit2): A framework for
defining and tracking users, login sessions, and seats

## systemd-dbus
* [basu](https://sr.ht/~emersion/basu/): The sd-bus library, extracted from
systemd
* [busd](https://github.com/dbus2/busd): A D-Bus bus (broker) implementation
in Rust
* [dbus-broker](https://github.com/bus1/dbus-broker): A high performance
and reliable implementation of a message bus as defined by the D-Bus
specification
* [sdbus-c++](https://github.com/Kistler-Group/sdbus-cpp): A high-level C++
D-Bus library for Linux designed to provide expressive, easy-to-use API in
modern C++
* [skabus](https://skarnet.org/software/skabus/): A suite of programs and
libraries for Unix systems that aim to implement a bus
* [ubus](https://openwrt.org/docs/techref/ubus): A micro system bus
architecture from OpenWRT to provide system-level Inter-process
Communication(IPC)

## systemd-journald
* [rsyslog](https://www.rsyslog.com/): The rocket-fast system for log
processing

## systemd-logind (Session Manager)
* [elogind](https://github.com/elogind/elogind): The systemd project's
"logind", extracted out to be a standalone daemon
* [greetd](https://git.sr.ht/~kennylevinsen/greetd): A minimal and flexible
login manager daemon that makes no assumptions about what you want to launch
* [seatd and libseat](https://git.sr.ht/~kennylevinsen/seatd): A minimal seat
management daemon, and a universal seat management library
* [sessiond](https://jcrd.github.io/sessiond/): A daemon for systemd-based
Linux systems that interfaces with systemd-logind to provide session management
features to X11 window managers
* [sessionman](https://github.com/KillingSpark/sessionman): An implementation
of a systemd-logind replacement in Rust
* [turnstile](https://github.com/chimera-linux/turnstile): A session/login
tracker and a service-manager-agnostic way to manage per-user service managers
for user services

## systemd-resolved
* [openresolv](https://roy.marples.name/projects/openresolv): A resolvconf
implementation, i.e. a resolv.conf management framework

## systemd-sysusers
* [catnest](https://github.com/eweOS/catnest): A substitution for
systemd-sysusers
* [opensysusers](https://github.com/cromerc/opensysusers): A utility written to
process sysusers.d files so that they can be handled on systems with or without
systemd installed

## systemd-tmpfiles
* [opentmpfiles](https://github.com/OpenRC/opentmpfiles): A standalone utility
for handling systemd-style tmpfiles.d settings
* [pawprint](https://github.com/eweOS/pawprint): A substitution of
systemd-tmpfiles
* [tmpfilesd](https://github.com/juur/tmpfilesd): A replacement for
systemd-tmpfiles that does not require systemd and includes support for
sysvinit style enviroments
* [tmpfiles-rs](https://github.com/rust-torino/tmpfiles-rs): A Rust
implementation of tmpfiles.d

## systemd-udev
* [devd-rs](https://codeberg.org/valpackett/devd-rs): A Rust library for
listening to FreeBSD (also DragonFlyBSD) devd's device attach-detach
notifications
* [eudev](https://github.com/eudev-project/eudev): A standalone dynamic and
persistent device naming support (aka userspace devfs) daemon that runs
independently from the init system
* [libudev (Go)](https://github.com/citilinkru/libudev): A Golang native
implementation Udev library
* [libudev (Rust)](https://github.com/dcuddeback/libudev-rs): A safe wrapper
around the native libudev library
* [libudev-devd](https://github.com/FreeBSDDesktop/libudev-devd): A
libudev-compatible interface for devd
* [libudev-fbsd](https://github.com/jiixyj/libudev-fbsd): A small udev shim for
FreeBSD/devd
* [libudev-zero](https://github.com/illiliti/libudev-zero): A drop-in
replacement for libudev intended to work with any device manager
* [libxdev](https://github.com/krytarowski/libxdev): An experimental native
libudev replacement for NetBSD
* [mdev (BusyBox)](https://busybox.net/): A mini udev for busybox
* [mdev like a boss](https://github.com/slashbeast/mdev-like-a-boss): A stash
for notes, scripts and configs for the system running with mdev as a udev
* [mdev (Rust)](https://github.com/rust-italia/mdev): An mdev daemon workalike,
written in pure rust
* [mdev (Toybox)](http://landley.net/toybox/): Populate /dev directory and
handle hotplug events
replacement
* [mdevctl](https://github.com/mdevctl/mdevctl): A mediated device management
and persistence utility
* [mdevd](https://skarnet.org/software/mdevd/): A small daemon managing kernel
hotplug events, similarly to udevd
* [nldev](https://core.suckless.org/nldev/): A netlink frontend for mdev,
replacing the over-engineered udevd
* [nlmon](https://core.suckless.org/nldev/): Replaces udevadm for monitoring
network devices
* [smdev](https://core.suckless.org/smdev/): A mostly mdev-compatible suckless
program to manage device nodes
* [smdev-phkr](https://aur.archlinux.org/packages/smdev): A configured smdev
* [udev (Rust)](https://github.com/Smithay/udev-rs): A safe wrapper around the
native libudev library
* [ueventd](https://android.googlesource.com/platform/system/core/+/master/init/README.ueventd.md):
Manages /dev, sets permissions for /sys, and handles firmware uevents
* [vdev](https://github.com/jcnelson/vdev): A portable userspace device-file
manager for UNIX-like operating systems

## Mirrors
* [Codeberg](https://codeberg.org/firasuke/awesome)
* [Framagit](https://framagit.org/firasuke/awesome)
* [GitHub](https://github.com/firasuke/awesome)
* [GitLab](https://gitlab.com/firasuke/awesome)
* [SourceHut](https://git.sr.ht/~firasuke/awesome)
