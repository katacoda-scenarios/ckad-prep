Why not use round-robin DNS?
A question that pops up every now and then is why we do all this stuff with virtual IPs rather than just use standard round-robin DNS. There are a few reasons:

There is a long history of DNS libraries not respecting DNS TTLs and caching the results of name lookups.
Many apps do DNS lookups once and cache the results.
Even if apps and libraries did proper re-resolution, the load of every client re-resolving DNS over and over would be difficult to manage.
