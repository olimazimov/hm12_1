# hm12_1

Created two playbooks to clean logs on servers.

<h1>1. Cleans only one folder, mentioned on variable `var`</h1>
Results are stored in `results.log`



<h1>2. Cleans several folders, mentioned on array `var`.</h1>
Currently working on it... Getting following error:

TASK [remove registered files] ********************************************************************************************************************************************************************
fatal: [192.168.137.20]: FAILED! => {"msg": "'dict object' has no attribute 'files'"}
fatal: [192.168.137.30]: FAILED! => {"msg": "'dict object' has no attribute 'files'"}

