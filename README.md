### mysqliro

A MySQL read only driver for Moodle. Using permissions to make Moodle read only can result in a change to behaviour and appearance. This driver silently throws away most database updates but allows through essential items such as those required to write to the log and download files. Original concept by Marcus Green with improvements by Hittesh Ahuja from Bath university. His repo is here https://github.com/hitteshahuja. Many thanks to Hittesh and to my employers, Moodle partners Titus Learning. https://www.tituslearning.com/

Update config.php to use this instead of standard mysqli
