## To Add a ssh
'''
ssh username@hostname
'''

Meaning: Learned That we can use 'ssh username@hostname' where if you only put 'ssh hostname' then it will use the username which you are using.

## To add a user with id 1329 with home directory of /var/www/ravi
'''
sudo useradd -u 1329 -d /var/www/ravi -m ravi
'''

Meaning:-
- ravi is user that we are adding, 
- -m means to create home directory specified by -d if it doesn't exists, 
- -d /var/www/ravi defines custom directory instead of /home/ravi,
- -u 1329 sets UID of 1329 for user, 
- useradd is used to create user account, 
- sudo gives administrator privileges.
