# MonkeyType Offline

For air gapped environments only the frontend will work sorry :)

### Components
Frontend \
Backend \
MongoDB \
Redis \
Firebase

<br />
<br />

### How to run
Frontend: `docker run -d -p 3000:3000 korenp/monkeytype:frontend` \
Backend: `docker run -d -p 5005:5005 korenp/monkeytype:backend` \
MongoDB: `docker run -d -p 27017:27017 -e MONGO_INITDB_DATABASE=monkeytype mongo` \
Redis: `docker run -d -p 6379:6379 redis` \
Firebase: `docker run -d -e GCP_PROJECT=monkeytype -p 9000:9000 -p 8080:8080 -p 4000:4000 -p 9099:9099 -p 8085:8085 -p 5001:5001 -p 9199:9199 -p 4400:4400 -p 4500:4500 spine3/firebase-emulator`

<br />
<br />

### Configure
Frontend: Configure firebase-config.js \
Backend: Configure .env file && Configure firebase ServiceAccount at /src/credentials/serviceAccountKey.json \
MongoDB: Volume at /data/MongoDB (Optional) \
Redis: Volume at /data (Optional) \
Firebase: :)

<br />
<br />

DockerHub: https://hub.docker.com/r/korenp/monkeytype
