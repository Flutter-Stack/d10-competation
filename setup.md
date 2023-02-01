composer create-project drupal/recommended-project "competation"
mariadb -uroot -p -e "create database competation;"
cd competation
sudo chmod -R 777 web/sites/default/ 

