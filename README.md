# CS208 Full Stack Final Project
- Name: Zeke Bohner
- GitHub: https://github.com/GirrafeEDU/CS208-12.03-lab-FullStack/
- Term: Fall 2026

## Project Description

This is a full stack project using pug, MariaDB, and JavaScript, to create a task list.
## Install the Database

To set up the database, run the `install_db.sh` script in the setup_scripts
directory. This script will install MariaDB and start the server running. You
only need to run this script once per Codespace.

```bash
./setup_scripts/install_db.sh
```
Reply n to the first question, followed by a Y. Then set the password to 12345. Afterwards respond y to the rest of the questions.

## Create the Database Tables

Create the initial tables by running the following command:

```bash
sudo mysql -u root -p < ./setup_scripts/create_demo_table.sql
```

## Install Dependencies

Install the required dependencies using npm:

```bash
npm install
```

## Run the Application

Start the application using the following command:

```bash
npm start
```

## Access the Application

On Codespaces, you can access the application by forwarding port 3000. Open the
forwarded port in your browser to view the application.
