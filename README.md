# Minecraft data
Contains a collection of usernames from Minecraft users (Java + Bedrock). In the future, this repo will contain conversation data as well.

# Usernames
Every username file contains three versions.  
**Raw**: Includes Java and Bedrock usernames. Bedrock usernames start with either `.` (new) or `*` (old)  
**Fixed**: Includes Java and Bedrock usernames. Bedrock usernames start with `.`, even if the last recorded name started with `*`  
**UUID**: Includes Java and Bedrock usernames and UUIDs. Bedrock usernames start with `.`, even if the last recorded name started with `*`  

In any case, the fixed/UUID version is recommended.

# Data files
[150k+ usernames (raw)](usernames_151633.txt)  
[150k+ usernames (fixed)](usernames_fixed_151633.txt)  
[150k+ usernames (UUID)](usernames_uuid_151633.txt)  
[300k+ usernames (raw)](usernames_331283.txt)  
[300k+ usernames (fixed)](usernames_fixed_331283.txt)  
[300k+ usernames (UUID)](usernames_uuid_331420.txt)  

# Known issues
- The UUID versions are slightly different from raw/fixed versions and may exclude some usernames (for reasons unknown)
- Some names appear double in the UUID versions even though their UUIDs are different because of name changes not being taken into account for some users