docker build -t api .
docker compose up -d
docker run -it --rm -p 8080:8080 api

curl http://localhost:8080

npx gitignore Node 
git init
git add .
git commit -m "Initial commit"