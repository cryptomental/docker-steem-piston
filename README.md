# docker-steem-piston
Docker image for steem-piston. Piston is the Swiss army knife for STEEM blockchain.


# Building and running the image

## You can pull and run the image from Docker Hub:

`$ docker pull cryptomental/steem-piston`
`$ docker run -it cryptomental/steem-piston`

## Or build it yourself using this GitHub repo:

`docker build -t steem-piston .`
`docker run -it steem-piston`

If everything goes fine you should be in container shell and able to execute piston:


```
piston@084a7a2cf152:~$ piston read @xeroc/piston-cli-quickstart
                                                    Congratulations                                                     

you have succesfully opened the piston-cli quickstart post on the Steem network.
```
