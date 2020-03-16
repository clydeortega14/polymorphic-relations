#clone the repository
 - git clone https://github.com/clydeortega14/polymorphic-relations.git

#Install composer
 - composer install
 
#copy .env.example file and create new .env file
 - cp .env.example .env
 
#generate new key
 - php artisan key:generate

#set up database for table migration then migrate tables
 - php artisan migrate
