# TRC Ninja Database (trcninja-db)
Based on Dash Ninja By Alexandre (aka elbereth) Devilliers

Check the running live website at https://overview.terracoin.io

This is part of what makes the TRC Ninja monitoring application.
It contains:
- Database structure (MySQL/MariaDB)

## Requirement:
* You will need a running MySQL/MariaDB with a TRC Ninja database and user.

## Optional:
* A user for the public API with only SELECT ability.
* A user for the private API with SELECT/INSERT/UPDATE ability.

## Install:
* Import database structure in your MySQL server

## Update:
* Check your database version from cmd_config
* Use the each corresponding script in /update to update from that version until you reach the last version
