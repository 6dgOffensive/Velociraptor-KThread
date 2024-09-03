This artifact parses `/proc/[0-9]*/status` files and extracts the `ProcessName` and `Kthread` values. Helpful for identifying imposter processes.

There is some good information here on imposter processes which is a handy reference: https://blog.apnic.net/2020/04/27/detecting-linux-kernel-process-masquerading-with-command-line-forensics/

This module has now also been merged into the main velociraptor repo:

https://docs.velociraptor.app/exchange/artifacts/pages/linux.collection.kthread/

There is some useful information here on usage of artifacts etc:

https://docs.velociraptor.app/docs/gui/artifacts/
