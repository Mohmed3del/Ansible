# Ansible Playbooks for Server Configuration

This repository contains a collection of Ansible playbooks that can be used to configure servers for different purposes. The playbooks are organized by role, with each role representing a specific aspect of server configuration.

## Usage

To use these playbooks, you'll need to have Ansible installed on your local machine. There are different ways to install Ansible:

### Installing Ansible using the system package manager

You can use the system package manager to install Ansible. For example, in Ubuntu, you can install Ansible using the following command:

```
sudo apt-get update
sudo apt-get install ansible
ansible --version
```

### Installing Ansible using the system package manager

You can use the system package manager to install Ansible. Here are the instructions for installing Ansible on RHEL:

```
sudo yum install epel-release
sudo yum install ansible
ansible --version
```

### Installing Ansible using pip

You can install Ansible using pip, the Python package manager. First, you need to install pip if it's not already installed. You can do that using the following command:

```
sudo apt-get update
sudo apt-get install python3-pip
sudo pip3 install ansible
ansible --version
```

## Roles

Here's a list of the roles included in this repository:

### `common`

The `common` role contains tasks that are common to all types of servers, such as installing basic packages and configuring the system timezone.

### `mysql`

The `mysql` role contains tasks that configure a MySQL database server, including installing MySQL, creating databases and users, and configuring backups.

### `sonarqube`

The `sonarqube` role contains tasks that configure a SonarQube server. This includes installing SonarQube, configuring the database, and setting up plugins. SonarQube is a tool for continuous code quality inspection that can be used to analyze code for bugs, vulnerabilities, and code smells.

### `postgresql`

The `postgresql` role contains tasks that configure a PostgreSQL database server. This includes installing PostgreSQL, creating databases and users, and configuring backups. PostgreSQL is a powerful and open-source relational database management system that is widely used in web applications.

### `jenkins`

The `jenkins` role contains tasks that configure a Jenkins server. This includes installing Jenkins, configuring plugins, and setting up jobs. Jenkins is a popular open-source automation server that can be used to automate tasks such as building, testing, and deploying software.

### `docker`

The `docker` role contains tasks that install Docker and Docker Compose, and configure Docker on the target server. Docker is a platform for developing, shipping, and running applications in containers. Docker Compose is a tool for defining and running multi-container Docker applications.

### `kubectl`

The `kubectl` role contains tasks that install kubectl and configure it to work with a Kubernetes cluster. kubectl is a command-line tool for managing Kubernetes clusters. Kubernetes is an open-source container orchestration system that can be used to deploy, scale, and manage containerized applications.

### frok this repo and then clone

```
git clone <your url>
```

## Contributing

If you'd like to contribute to this repository, feel free to submit a pull request or open an issue. Contributions are always welcome!
