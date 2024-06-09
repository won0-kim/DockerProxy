# Build
docker build -t won10/proxy .

# Run
docker run --restart=always -p 3128:3128 -d won10/proxy 
