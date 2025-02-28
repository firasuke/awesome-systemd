# awesome-systemd
A curated list of awesome projects that provide systemd-like functionality

## D-Bus
- [basu](https://git.sr.ht/~emersion/basu): The sd-bus library, extracted from
systemd
- [busd](https://github.com/dbus2/busd): A D-Bus bus (broker) implementation
in Rust based on zbus
- [dbus-broker](https://github.com/bus1/dbus-broker): A high performance and
reliable implementation of a message bus as defined by the D-Bus specification
- [dbus-native](https://github.com/diwic/dbus-rs/tree/master/dbus-native): An
experimental crate that replaces some functions in the libdbus C library with
similar functions written in Rust
- [dinit-dbus](https://github.com/chimera-linux/dinit-dbus): A D-Bus interface
to dinit built upon libdinitctl
- [kdbus](https://freedesktop.org/wiki/Software/systemd/kdbus/): A transport
layer for the DBus IPC system, meant as replacement for the UDS (Unix Domain
Socket) transport layer
- [librdbus](https://github.com/KillingSpark/librdbus): A toy project that tries
to reimplement the widely used libdbus in rust and uses rustbus internally
- [rustbus](https://github.com/KillingSpark/rustbus): A library that implements
the dbus specification for local unix sockets and enables clients to communicate
over the dbus daemon
- [sdbus-c++](https://github.com/Kistler-Group/sdbus-cpp): A high-level C++
D-Bus library for Linux designed to provide expressive, easy-to-use API in
modern C++
- [skabus](https://skarnet.org/software/skabus/): A suite of programs and
libraries for Unix systems that aim to implement a bus
- [tangle](https://github.com/chimera-linux/tangle): A standalone version of
sd-bus/sd-event extracted from systemd
- [ubus](https://openwrt.org/docs/techref/ubus): A micro system bus architecture
from OpenWrt to provide system-level Inter-process Communication (IPC)
- [zbus](https://github.com/dbus2/zbus): A Rust API for D-Bus communication

## systemd-journald
- [kslog](https://github.com/c-blake/kslog): A minimalistic kernel-syslogd for
Linux in Nim
- [procd](https://openwrt.org/docs/techref/procd): The OpenWrt process
management daemon written in C that has replaced `hotplug2`, `busybox-klogd`,
`busybox-syslogd` and `busybox-watchdog`
- [rsyslog](https://www.rsyslog.com/): The rocket-fast system for log processing
- [s6-log](https://skarnet.org/software/s6/s6-log.html): A reliable logging
program with automated log rotation, similar to daemontools' multilog, with full
POSIX regular expression support
- [socklog](https://smarden.org/socklog/): A small and secure replacement for
syslogd
- [stumpless](https://github.com/goatshriek/stumpless): A C logging library
built for high performance and a rich feature set
- [sysklogd](https://github.com/troglobit/sysklogd): A BSD syslog daemon with
syslog()/syslogp() API replacement for Linux, RFC3164 + RFC5424
- [syslog-ng](https://github.com/syslog-ng/syslog-ng): An enhanced log daemon,
supporting a wide range of input and output methods: syslog, unstructured text,
message queues, databases (SQL and NoSQL alike), and more

## systemd-logind (Session Manager)
- [consolekit2](https://github.com/ConsoleKit2/ConsoleKit2): A framework for
defining and tracking users, login sessions, and seats
- [elogind](https://github.com/elogind/elogind): The systemd project's "logind",
extracted out to be a standalone daemon
- [greetd](https://git.sr.ht/~kennylevinsen/greetd): A minimal and flexible
login manager daemon that makes no assumptions about what you want to launch
- [seatd and libseat](https://git.sr.ht/~kennylevinsen/seatd): A minimal seat
management daemon, and a universal seat management library
- [sessiond](https://jcrd.github.io/sessiond/): A daemon for systemd-based
Linux systems that interfaces with systemd-logind to provide session management
features to X11 window managers
- [sessionman](https://github.com/KillingSpark/sessionman): An implementation of
a session manager similar to systemd-logind in Rust
- [turnstile](https://github.com/chimera-linux/turnstile): A session/login
tracker and a service-manager-agnostic way to manage per-user service managers
for user services
- [utlogd](https://web.obarun.org/software/utlogd/latest/): A login/logout user
daemon tracker that uses the inotify API to survey the change of the user by the
utmp file
- [utmps](https://skarnet.org/software/utmps/): A secure implementation of user
accounting, using a daemon as the only authority to manage the utmp and wtmp
data

## systemd-resolved
- [openresolv](https://roy.marples.name/projects/openresolv): A resolvconf
implementation, i.e. a resolv.conf management framework

## systemd-sysusers
- [catnest](https://github.com/eweOS/catnest): A substitution for
systemd-sysusers
- [esysusers](https://packages.artixlinux.org/packages/system/x86_64/esysusers/):
The sysusers.d binary
- [obsysusers](https://web.obarun.org/software/obsysusers/0.1.2.1/index/):
A utility that parses and creates system users and groups, based on the file
format and location specified in sysusers.d directories
- [opensysusers](https://github.com/cromerc/opensysusers): A utility written to
process sysusers.d files so that they can be handled on systems with or without
systemd installed
- [sd-tools](https://github.com/chimera-linux/sd-tools): A collection of tools
forked from systemd that provides sysusers and tmpfiles

## systemd-tmpfiles
- [etmpfiles](https://packages.artixlinux.org/packages/system/x86_64/etmpfiles/):
The tmpfiles.d binary
- [opentmpfiles](https://github.com/OpenRC/opentmpfiles): A standalone utility
for handling systemd-style tmpfiles.d settings
- [pawprint](https://github.com/eweOS/pawprint): A substitution of
systemd-tmpfiles
- [sd-tools](https://github.com/chimera-linux/sd-tools): A collection of tools
forked from systemd that provides sysusers and tmpfiles
- [tmpfilesd](https://github.com/juur/tmpfilesd): A replacement for
systemd-tmpfiles that does not require systemd and includes support for sysvinit
style enviroments
- [tmpfiles-rs](https://github.com/rust-torino/tmpfiles-rs): A Rust
implementation of tmpfiles.d
- [usertmp.sh](https://codeberg.org/Zucca/usertmp.sh): A script to create temp
directories for users on systems where systemd-logind or elogind is absent

## systemd-udev
- [devd-rs](https://codeberg.org/valpackett/devd-rs): A Rust library
for listening to FreeBSD (also DragonFlyBSD) devd's device attach-detach
notifications
- [eudev](https://github.com/eudev-project/eudev): A standalone dynamic
and persistent device naming support (aka userspace devfs) daemon that runs
independently from the init system
- [hotplugd](https://github.com/oasislinux/hotplugd): oasis hotplug daemon
- [libdemi](https://github.com/illiliti/libdemi): A device enumeration,
monitoring and introspecting library
- [libudev (Go)](https://github.com/citilinkru/libudev): A Golang native
implementation Udev library
- [libudev (Rust)](https://github.com/dcuddeback/libudev-rs): A safe wrapper
around the native libudev library
- [libudev-compat](https://git.devuan.org/aitor_czr/libudev-compat): An
ABI-compatible libudev that does not need udevd to be running
- [libudev-devd](https://github.com/wulf7/libudev-devd): A libudev-compatible
interface for devd
- [libudev-fbsd](https://github.com/jiixyj/libudev-fbsd): A small udev shim
for FreeBSD/devd
- [libudev-zero](https://github.com/illiliti/libudev-zero): A drop-in
replacement for libudev intended to work with any device manager
- [libxdev](https://github.com/krytarowski/libxdev): An experimental native
libudev replacement for NetBSD
- [mdev (BusyBox)](https://git.busybox.net/busybox/tree/util-linux/mdev.c): A
mini udev for busybox
- [mdev like a boss](https://github.com/slashbeast/mdev-like-a-boss): A stash
for notes, scripts and configs for the system running with mdev as a udev
replacement
- [mdev (Rust)](https://github.com/rust-italia/mdev): An mdev daemon workalike,
written in pure rust
- [mdev (Toybox)](
https://github.com/landley/toybox/blob/master/toys/pending/mdev.c): Populate
/dev directory and handle hotplug events
- [mdevctl](https://github.com/mdevctl/mdevctl): A mediated device management
and persistence utility for Linux
- [mdevd](https://skarnet.org/software/mdevd/): A small daemon managing kernel
hotplug events, similarly to udevd, and is a drop-in replacement to mdev that
does not fork
- [ndev](https://github.com/TAAPArthur/ndev): A nano sized device manager with
mdev/sdev like syntax
- [nldev](https://core.suckless.org/nldev/): A netlink frontend for mdev,
replacing the over-engineered udevd
- [nlmon](https://core.suckless.org/nldev/): Replaces udevadm for monitoring
network devices
- [procd](https://openwrt.org/docs/techref/procd): The OpenWrt process
management daemon written in C that has replaced `hotplug2`, `busybox-klogd`,
`busybox-syslogd` and `busybox-watchdog`
- [smdev](https://core.suckless.org/smdev/): A mostly mdev-compatible suckless
program to manage device nodes
- [smdev-phkr](https://aur.archlinux.org/packages/smdev): A configured smdev
- [udev (Rust)](https://github.com/Smithay/udev-rs): A safe wrapper around the
native libudev library
- [udevmod](https://github.com/arsv/minibase/tree/master/src/udev): minibase
udev event monitor
- [ueventd](
https://android.googlesource.com/platform/system/core/+/master/init/README.ueventd.md):
Manages /dev, sets permissions for /sys, and handles firmware uevents
- [vdev](https://github.com/jcnelson/vdev): A portable userspace device-file
manager for UNIX-like operating systems

## Mirrors
- [Codeberg](https://codeberg.org/firasuke/awesome-systemd)
- [GitHub](https://github.com/firasuke/awesome-systemd)
- [SourceHut](https://git.sr.ht/~firasuke/awesome-systemd)
