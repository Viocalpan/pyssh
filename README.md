# pyssh
rewite greenplum tools (gpssh,gpscp,gpssh-exkeys) with python3 and remove 3th library only Dependencies pexpect & ptyprocess

+ pysshexK -f hosts -u root
+ pyscp -f hosts /viocal/*.gz  =:/tmp -u root
+ pyssh -f hosts -u root
* version=0.6  from greenplum 6.0
* pyssh  Dependencies pexpect 
* pyscp  Dependencies no 3th library
* pysshexK Dependencies pexpect 
* fix pyssh quit bug,this from greenplum
+ add remotehost user to login 
