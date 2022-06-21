# Chuck-black-course
from pprint import pprint

# DICTIONARY representing  a device
device = {
    "name": "sbx-n9kv-ao",
    "vendor": "cisco",
    "model": "Nexus9000 C9300 Chassis",
    "OS":"nxos",
    "version":"9.3(3)",
    "ip":"10.1.1.1",

}

# SIMPLE PRINT
print("\n _________SIMPLE PRINT____________________")
print("device:", device)
print("device name:", device["name"])

# PRETTY PRINT
print("\n _____PRENTY PRINT_____")
pprint(device)

# FOR LOOP, NICELY FORMATTED PRINT
print("\n____FOR LOOP, USING F_STRING________")
for key, value in device.items():
    print(f"{key:>16s} : {value}")

