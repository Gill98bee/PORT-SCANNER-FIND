# PORT-SCANNER-FINDER

FAST-PORT-SCANNER(FAST)
This is simple python port scanner that scans for open ports prints them out on the screen. It works by scanning port ranges and shows which ones are open ONLY.

USAGE:
usage: python fastportscanner.py [-h] [--ports PORT_RANGE] host

Simple port scanner

positional arguments:
  host                  Host to scan.

options:
  -h, --help            show this help message and exit
  --ports PORT_RANGE, -p PORT_RANGE
                        Port range to scan, default is 1-65535 (all ports)

FIND-OPEN-PORTS(SLOW)
This is scans for both open or closed ports. It is by a slow scan but carefully make sure none is missed and will display both open and closed ports.  

Requirement:
# pip3 install colorama

USAGE:
python find-open-ports.py HOST


