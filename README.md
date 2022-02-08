# Build
docker build -t won10/proxy .

# Run
docker run --restart=always -p 8080:8080 -d won10/proxy 
