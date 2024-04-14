Build the image
`docker build -t {your_name}/simplest-node-app .`

Run a container using built image
`docker run -p 3000:3000 --rm {your_name}/simplest-node-app`

Stop the container by `Ctrl + C`
