# Jupyter Hub template

## Installation in a single Machine

Make sure you have python3, python3-dev, curl and git installed.

    $ sudo apt install python3 python3-dev git curl

Download and execute the installation process:

    $ curl -L https://tljh.jupyter.org/bootstrap.py | sudo -E python3 - --admin <admin-user-name>

Copy the Public IP of your server, and try accessing http://<public-ip> from your browser. 

# References

- [Jupyter Hub](https://tljh.jupyter.org/en/latest/install/custom-server.html)