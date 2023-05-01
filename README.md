# 🎥Dockerizing DRF Cinema API🎬

API service for cinema management written in DRF
## 🌍Installing using GitHub:

Install PostgreSQL and create db
 
```
git clone https://github.com/NazarHladaniuk/Cinema_API_DRF.git
cd cinema_API
python -m ven venv 
venv\Scripts\activate
source venv/bin/activate 
pip install -r requirements.txt 
python manage.py migrate 
python manage. py runserver
 ```
Also, add our environment variable to your .env ✏️
```
set DB HOST=<your db hostname> 
set DB NAME=<your ab name> 
set DB_USER=<your db username> 
set DB PASSWORD=<your db user password> 
set SECRET_KEY=<your secret key> 
```

### 🐳Run with docker:
```
Docker should be installed

docker-compose build
docker-compose up
```  

### 🔑Gerring access:
```
- create user vis /api/user/register/
- get access token via /api/user/token/
```
### 🌟Features:
```
- JWT authenticated
- Admin panel /admin/
- Documentation is located at /api/doc/swagger/
- Managing orders and tickets
- Create movies with genres and actors
- Create cinema halls
- Adding movie sessions
- Filtering movies and movie sessions
```