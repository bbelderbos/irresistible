## Git (no Docker) Install

If you prefer to run the applications on your own system rather than using the Docker container, you need to have Git and Node.js installed on your system. 

The commands needed to pull the repository to your system and install and run node are as follows:

	$ git clone https://github.com/synedra/irresistible
	$ cd irresistible
	$ npm install 
	$ node toppings.js

Go to `http://0.0.0.0:8080/demo/` in your browser. Or use `http://0.0.0.0:8080/api/v1.0/toppings/` if you're using tools like curl or Postman.
