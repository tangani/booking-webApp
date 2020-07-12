# systemctl show --property ActiveState docker
Tools:
	PHP
	Composer
	Docker
	MySQL
	git
	Zend


Steps
1. composer create-project zendframework/zend-expressive-skeleton expressive
	Gets packages from Github
2. open composer.json and customize
3. composer run --timeout=0 serve
4. composer development-status
5. vi data/schema.sql
6. vi docker-compose.yml
7. mkdir container-build/web
	7.1 vi Docfileker
8. sudo  docker-compose up -d
9. sudo docker ps