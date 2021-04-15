# NGINX Configuration Template

This repo contains a bundle of NGINX configurations such as, load balancer, reverse proxy, static html php etc.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them on your ubuntu server

```
sudo apt install nginx
```
### High Level Configuration

#### Static HTML Content
This configuration makes the nginx to serve the static content of HTML.

![alt text](https://www.nginx.com/wp-content/uploads/2018/04/NGINX-Unit-WordPress-2-schemes.png "Static content configuration")

#### Load Balancer 
Load balancer configuration will distribute the load among several servers. You can determinte the load distribution for each server.

![alt text](https://miro.medium.com/max/964/1*wsxdxOWkR7arPfNQNnHxzw.png "Load Balancer Configuration")

### Installing

1. DetermA step by step series of examples that tell you how to get a development env running

Say what the step will be

```
sudo apt install nginx
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Fariz Alemuda** - *Initial work* - [PurpleBooth](https://github.com/farizalemuda)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc