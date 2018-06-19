PHP Cron Expression Parser
==========================

This is a fork of [dragonmantank/cron-expression](https://github.com/dragonmantank/cron-expression).
Feel free to use this fork though I don't plan to support it.  This exists 
because the base library is awesome, but aims for compatibility with "standard" 
CRON expression syntax over functionality.

** Why This Fork Exists **

I was working on billing processor for a customer that invoices their customers
twice a month (15th and the "last day", whtever that is). While `cron-expression`
supports "L" as a placeholder for "last day", and supports multiple comma-separated
values in each part o the schedule, it does not support both at the same time.

The repo's creator said this is intentional to maintain compatibility with other
CRON schedules.  I don't care about this. I need the feature.

If you do too, feel free to pull this repo.  But if you want support, please
use the original.