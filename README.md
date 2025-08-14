# devops-task-7
> *Objective:* Install Netdata and visualize system and app performance metrics.

---

## 🛠 Tools Used

* *Docker:* Used for containerizing and running the Netdata application.
* *Netdata:* A free, open-source tool for real-time performance monitoring.

---

## 🚀 How to Run This Project

Follow these steps to reproduce the setup on your local machine.

### Prerequisites

* You must have [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed and running.

### Steps

1.  *Run the Netdata Container:*
    Open a terminal or PowerShell and execute the following command:
    bash
    docker run -d --name=netdata -p 19999:19999 netdata/netdata
    

2.  *Access the Dashboard:*
    Once the container is running, open your web browser and navigate to:
    [http://localhost:19999](http://localhost:19999)

    You will see the live dashboard monitoring your system's resources.

---

## 📊 Deliverable: Dashboard Screenshot

Here is the screenshot of the Netdata dashboard displaying real-time system metrics as required by the task.

![Netdata Dashboard](netdata-dashboard.png)

Note: Make sure the filename in the line above matches the name of your screenshot file in this repository.

---

## 🧑‍💻 Author

vasuswayambarapu4
