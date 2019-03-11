### Simple blockchain API written in Golang
Written after reading code samples on [this](https://medium.com/@mycoralhealth/part-2-networking-code-your-own-blockchain-in-less-than-200-lines-of-go-17fe1dad46e1) article. 

##Usage
Ensure Golang is installed on your system and the ```$GOPATH``` and ```$GOROOT``` are in the right directories/have the correct links. 

To run the program, invoke: ```go run main.go```.

## Ze Blockchain

To view the blockchain API and visualize our hashing, navigate to your localhost:8080(http://localhost:8080/) and use Postman or curl with a POST request.

##Curling for POST example:
``` curl --header "Content-Type: application/json" --request POST --data '{"BPM":120}' http://localhost:8080 ```
