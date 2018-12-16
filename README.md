# Investment Dashboard
It is a project that helps to optimize a budget for investments, It allows to compare offerings based on crowdfunding platforms.
supported Platforms:
* Briq
* cumplo
* m2crowd
* inverspot

## Installation

create virtual environment
using Anaconda
~~~
conda create --name invdash python=3.6
source activate invdash
~~~
or using virtualenv
~~~
virtualenv -p /usr/bin/python3.6 environment
source activate environment
~~~

configurate credentials
1. copy and rename the file dotcredentials.yaml `cp dotcredentials.yaml .credentials.yaml`
1. open the file dotcredentials.yaml
1. replace user and password for each  site
