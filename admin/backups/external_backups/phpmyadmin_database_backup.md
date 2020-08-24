### PhpMyAdmin database backup {#phpmyadmin-database-backup}

Databases can be saved from the [P](http://fr.wikipedia.org/wiki/PhpMyAdmin)[hpMyAdmin](http://fr.wikipedia.org/wiki/PhpMyAdmin) interface, connecting using the login and password created during the [LAMP](http://fr.wikipedia.org/wiki/LAMP) server installation, the database installation, or in the data transmitted by your hosting provider[^14].

![](../../assets/phpaccueuil.png)Illustration 15: Administration - PHPMyAdmin

Once in the graphical interface of PhpMyAdmin, go to the _Export_tab and select the database to be saved. There&#039;s probably another one called “information_schema”, which you can just ignore.

You may want to change the output format of the backup file. To save, choose on the desired format below the databases to export. In the present example we chose SQL.

The name of the saved file can also be changed in the _Output_ section. It can be compressed using one of the three offered formats. Do not forget to select the _Save output to a file_ option, otherwise it will just print the backup result on screen, which will not really help you.

You&#039;re only left with downloading the file. It will be saved by default in your _Downloads_ directory or on your desktop, depending on your browser&#039;s configuration.

Saving the databases through _hpMyAdmin_ is over. The saved file will be to the SQL format (.sql extension) and will be importable later on, in case of problem, through PhpMyAdmin.

[^14]: You can also recover the database credentials from the main/inc/conf/configuration.php file