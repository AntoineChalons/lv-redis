# Use Redis, a fast in-memory database with your automation project

## Why Redis?

- it's very fast even with a huge amount of data
- open source and free
- can run on a Linux machine or in a docker container or on WSL
- cannot **yet** be installed on via opkg
- can probably be built from source on cRIO
- it's easy to learn (lots of online resource, including an active Discord server)
- the alternatives to share a database between a Linux RT Target and a Host (Windows/Linux/Mac) running a LabVIEW app are not as flexible
- an VIPM package exists (it's embedded TCP, so it's easy to expand it)
