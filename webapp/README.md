## Git Install

If you prefer to run the applications on your own system rather than using the Docker container, you need to have Git and Node.js installed on your system. 

The commands needed to pull the repository to your system, install the dependencies (package.json) and run node are:

	$ git clone https://github.com/synedra/irresistible
	$ cd irresistible
	$ npm install 
	$ node toppings.js

Next go to `http://0.0.0.0:8080/demo/` in your browser. 

Or use `http://0.0.0.0:8080/api/v1.0/toppings/` for tools like curl or Postman.
