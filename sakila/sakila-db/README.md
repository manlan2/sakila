# sakila-db

Contains database related data for several engines (SQL and No Sql)

Mongodb Instructions
To have launchd start mongodb at login:
  ln -sfv /usr/local/opt/mongodb/*.plist ~/Library/LaunchAgents
Then to load mongodb now:
  launchctl load ~/Library/LaunchAgents/homebrew.mxcl.mongodb.plist
Or, if you don't want/need launchctl, you can just run:
  mongod --config /usr/local/etc/mongod.conf


Mysql Instructions
We've installed your MySQL database without a root password. To secure it run:
    mysql_secure_installation

To connect run:
    mysql -uroot

To have launchd start mysql at login:
  ln -sfv /usr/local/opt/mysql/*.plist ~/Library/LaunchAgents
Then to load mysql now:
  launchctl load ~/Library/LaunchAgents/homebrew.mxcl.mysql.plistOr, if you don't want/need launchctl, you can just run:
  mysql.server start

  
