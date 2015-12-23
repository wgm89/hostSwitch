Thanks for linpc

A CLI tool to easily switch between different hosts settings
Commands
--------
    $ hostSwitch help
    Usage:
        hostSwitch                     show current setting
        hostSwitch list <set>          show current setting of specific set
        hostSwitch dig <set>           show current host table of specific set
        hostSwitch digs                show all current valid hosts
        hostSwitch all-off <set>       (root) turn off all local settings (Use DNS)
        hostSwitch on <set> <group>    (root) to switch <group> hosts setting ON

Definition
----------
* __GROUP__: indicate one specific setting of some hostnames
* __SET__: indicate an aggregation of hosts. You can define several setting __*group*__ for one __*set*__, but only one __*group*__ setting can be activated simultaneously.


License
-------
FreeBSD License
