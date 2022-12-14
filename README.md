# hm12_1

Created a playbook to clean logs on servers.

<h2>Cleans files in the folder, mentioned on variable `var` and files that older than mentioned in variable `age`</h2>
Results are stored in `results.log`



As an upgrade working on cleaning several folders, mentioned on array `var`.</h2>
For now getting a following error:

TASK [remove registered files] ********************************************************************************************************************************************************************
fatal: [192.168.137.20]: FAILED! => {"msg": "'dict object' has no attribute 'files'"}
fatal: [192.168.137.30]: FAILED! => {"msg": "'dict object' has no attribute 'files'"}

Working on it...