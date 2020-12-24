# qiita_django
id yukihagino  
pass hogefuga  
https://qiita.com/kaki_k/items/511611cadac1d0c69c54
## 環境構築
###1. django install
###2. start project
django-admin startproject mybook
###3. DB setting in setting.py
setting db and user/pass
## create app
###1. start app
python manage.py startapp [name of app]
###2. gene models for db
difine models of db on cms/models.py  
activate models cms/apps.py in mybook/setting.py INSTALLED_APPS  
python manage.py makemigrations [name of app]
python manage.py migrate [name of app]

## make schem of urls
touch cms/urls.py  
include urls in mybook/urls.py