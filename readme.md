# rc.d services for Bhyve VM management

These are some of the services I use to run the VMs in my internal grid under FreeBSD. It offers very basic management and monitoring at the moment.

# Usage

	# service bhyve_vm {start,stop,status}

> When you run `service <srvname>` it usually lists a bunch of default commands implemented in the `rc.subr` script. Except for the three listed above, their behavior is **undefined**.
