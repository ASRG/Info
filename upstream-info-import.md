# Upstream Info Import

1. Change the date format in the excel file from MM/DD/YYYY to DD.MM.YY format. The end commas need to be semi-colons. &#x20;
2. Save as CSV
3. Copy from local to server
4.

![](<.gitbook/assets/image (11).png>)

5\. Login to server with SSH.

6\. copy the file to /tmp

7\. Go to Upstream\_CSV Integration in the intel.asrg.io interface

8\. add local to the actual file name and path.&#x20;

9\. Enable

Possible Issue:

It's a good idea to process the data first in python, using pycharm to read in the data and parse it.  This will show any possible errors.  A common error is the single qoutations which need to be vertical and without sloped.&#x20;

Find and replace could be used as well



