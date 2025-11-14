# Description
Saltstack desktop configuration for a deterministic, declarative and reproducible system.

> [!info] Note: 

# Details
- The `desktop` folder configures a masterless minion allowing us to execute salt commands from the SLS files on our host machine
- The `acl-setup` script helps to avoid having to always edit the files with sudo (because the `/srv` directory isn't writable for normal users)
