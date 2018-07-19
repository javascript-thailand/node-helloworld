# nodejs-helloworld

Run the following command:

docker run --rm --mount type=bind,source="$(pwd)"/js,target=/js node:8 node /js/helloworld.js
