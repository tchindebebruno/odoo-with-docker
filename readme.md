# Odoo with Docker

## Prerequisites

- **Operating System**: Linux or Windows Subsystem for Linux (WSL). (Recommended: Ubuntu 24.04)
- **Git**: Ensure Git is installed on your system.

## Step 1: Install Docker and Docker Compose

Open your terminal and run the following commands:

```bash
sudo apt update
sudo apt install docker.io -y
sudo apt install docker-compose -y
```

## Step 2: Clone the Project

Next, clone the project repository:

```bash
git clone https://github.com/tchindebebruno/odoo-with-docker.git
cd odoo-with-docker/
```

## Step 3: Build and Run the Application

To start the application, execute:

```bash
docker compose up -d
```

## Step 4: Access Odoo

Once the application is running, you can access Odoo by navigating to:

[http://localhost:8069/](http://localhost:8069/)

## Additional Notes

- Ensure Docker is running properly before executing the `docker compose up` command.
- For any issues, refer to the [Docker documentation](https://docs.docker.com/) or check the repository for troubleshooting tips.
