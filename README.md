# onlinestss


##### Set up GIT
https://docs.github.com/en/get-started/getting-started-with-git/set-up-git#password-caching

##### Set up SSH connection with git remote repo
https://code.tutsplus.com/quick-tip-how-to-work-with-github-and-multiple-accounts--net-22574t



## Troubleshooting


##### Hosting has too many inodes
Diagnosis: check cpanel on the right-hand side under 'Statistics'
<img width="251" alt="image" src="https://github.com/user-attachments/assets/25f0eaaf-f6f3-49f5-a23c-d3c9bc4a1a34" />

Solution:
Delete unused files. The main culprits are pdf invoices and emails. 
To find which folders have a lot of inodes, run `sudo find [/path/to/check] -xdev -printf '%h\n' | sort | uniq -c | sort -nr | head` in command line.

