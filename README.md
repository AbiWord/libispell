# libispell

This is the ispell-as-a-library fork of ISpell that shipped with [Enchant](https://github.com/AbiWord/enchant) up to and including version 1.6.1.

The code was found not to work with ispell dictionaries from the then-current version of ispell (3.4.00), on at least some systems, and was therefore removed, since there are good modern to ispell for most users.

Anyone who would like to resurrect ispell support in Enchant is welcome to do so. The most obvious way would be to get the code working again with current dictionaries, but this is likely to suffer the same problem again in future.

A better method would be to craft a new library interface as a patch to upstream ispell. (ispell's maintainer said he wasn't interested in adding such an interface (private communication, early 2017.) This would probably be easy to adapt to new versions of ispell (which is only infrequently maintained, and mostly in maintenance mode), and would be suitable for inclusion in enchant again.

If you're interested in doing this work, do file an issue on Enchant's bug tracker.
