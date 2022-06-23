# db_backup

## Description

This scripts does the following:
- Loops though all `.env` files;
- Connects (ssh) into the remote server;
- Creates a dump of a MySQL db;
- Downloads (ssh) the dump file;
- Compresses (xz) the dump file.

## Setup

1. `cp env.dist mydb1.env`
2. `vim mydb.env`
3. `./db_backup`

Automate with cron.

