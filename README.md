## Project Description

Deploy Grafana and Prometheus to AWS EC2 instances automatically with Terraform, Ansible and Jenkins.

## Dockerfile

The Dockerfile is used to build a customized Jenkins docker image that will be installed with the required
environments inluding AWS CLI, Terraform, Ansible and JQ.

The basic image and running guide could be found at
https://www.jenkins.io/doc/book/installing/docker/#on-macos-and-linux

## Terraform

Terraform cloud is used for Terraform state backup. Resources that Terraform will create include AWS VPC,
subnets, rout tables, internet gateway, security groups and EC2 instances. With several .tfvars files for
different environments.

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)