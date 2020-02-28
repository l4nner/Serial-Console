# Serial-Console
Serial console capture

Creating a “console connection” to get access to a Linux instance console, is not one of the most straightforward tasks. Mostly for customers facing issues that require immediate resolution. It’s also very common to see customers creating and using console connections for the sole reason of seeing what is going on with the guest OS. For that, we can provide them this quick script. It will capture the contents of the serial console of a given instance.

It also helps with a few common issues like hitting the limit number of console history objects. It removes the older ones and tries again. Or adding the "length" parameter, which circumvents a very common issue when using the CLI for that. One that truncates the output. Something our public documentation fails to address. No problem, the script is here. Life is easy now.

In conclusion, all customer needs is to run this script.
