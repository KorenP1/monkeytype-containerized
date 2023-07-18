# MonkeyType Offline

Components: Frontend, Backend, MongoDB, Redis

<br />
<br />

### How to run
Frontend: `docker run -d docker.io/korenp/monkeytype:frontend`
Backend: `docker run -d docker.io/korenp/monkeytype:backend`
MongoDB: `docker run -d -p 27017:27017 -e MONGO_INITDB_DATABASE=monkeytype mongo`
Redis: `docker run -d -p 6379:6379 redis`

<br />
<br />

### Configure
Frontend: :)
Backend: Please configuire .env file
MongoDB: Volume at /data/MongoDB (Optional)
Redis: Volume at /data (Optional)

<br />
<br />

Dockerhub: https://hub.docker.com/r/korenp/monkeytype
