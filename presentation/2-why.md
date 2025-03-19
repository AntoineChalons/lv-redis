# Use Redis, a fast in-memory database with your automation project

## Scenario

- multiple systems communicating on a production line
- not all built with LabVIEW

## Why Redis?

- it's very fast even with a huge amount of data
- open source and free
- can run on a Linux machine or in a docker container or on WSL
- cannot **yet** be [installed on via opkg](https://forums.ni.com/t5/LabVIEW-Real-Time-Idea-Exchange/Make-Redis-available-via-opkg/idi-p/4412352)
- can probably be built from source on a NI Linux RT Target
- it's easy to learn
  - [detailed doc](https://redis.io/docs/latest/)
  - [professional consulting available](https://redis.io/services/professional-services/)
  - [online university](https://university.redis.io/academy)
  - [active Discord server](https://redis.io/learn/community/discord)
- the alternatives to share a database between a Linux RT Target and a Host (Windows/Linux/Mac) running a LabVIEW app are not as flexible
- [A toolkit exits](https://forums.ni.com/t5/Example-Code/REDIS-database-LabVIEW-toolkit/ta-p/3508602) (it's embedded TCP, so it's easy to expand it)
- There are a few GitHub public repo built from the toolkit linked above
