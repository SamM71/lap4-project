# Lap 4 Project

## Installation and usage
1. Clone the repo and ensure you have the files for the submodules as well.
2. Add a `.env` file inside the server folder. Input the following values:
```sh
# .env
FLASK_APP=app
FLASK_DEBUG=1
SQLALCHEMY_DATABASE_URI=postgresql://user1:jkljkl@db:5432/db_dev
SQL_HOST=db
SQL_PORT=5432
DATABASE=postgres
```
3. Run the docker daemon.
4. `docker-compose up -d --build`
  - If this doesn't work, first run `chmod +x ./server/entrypoint.sh` to give `entrypoint.sh` execute permissions.
5. Open the frontend on [5173](http://localhost:5173/)
6. The backend runs on [5000](http://127.0.0.1:5000/)