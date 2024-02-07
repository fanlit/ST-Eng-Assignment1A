Develop a Linux bash script to implement the checking of the following CIS requirements based on the Linux VM image that has been provided. 
 - Ensure SSH root login is disabled
 - Ensure SSH PermitEmptyPasswords is disabled
 - Ensure SSH Protocol is set to 2
 - Ensure password expiration is 90 days or less
 - Ensure system accounts are non-login

The bash script shall be executed every 8am and 5pm on a daily basis.

The bash script shall generate the output in para 1 to a log file or report.

The bash script shall send an email to alert any failure in the compliance check.
