# Z31VS1.CCKD

https://archive.org/details/zos31_version1

## Starting

SYS0.IPLPARM has 6 members. LOADAU, LOADA0, LOADGK, LOADK2, LOADNZ, LOADZT.
`IPL DE27 LOADPARM DE28A0`

If I respond to DSI802A CNM01 with "R 0003, CLOSE DUMP", I won't be able to access the logon UI.

## Shutting down

1. `F CNMPROC,SHUTDOWN` or `%NETV SHUTDOWN`
2. `<stop`
3. `d a,l`
4. `z eod`
5. `quiesce`

I'm not sure if it is right way.

https://www.ibm.com/docs/ko/zvdt/1.4.x?topic=zvdt-automated-netview 
