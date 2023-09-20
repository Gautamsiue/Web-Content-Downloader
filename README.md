### Web Content Downloader

This Python script allows you to download the text content from a given URL and save it to a text file.

### Prerequisites

Before running this script, the following things needs to be installed:

- Python 3.8
- Conda (for managing dependencies)

### Setup

- Clone this GitHub repository to your local machine:

   ```bash
   git clone https://github.com/your-username/web-content-downloader.git

-Create a Conda environment (if not already created) and activate it using the following code :

      conda create --name web_downloader python=3.8
      conda activate web_downloader

-Install the required Python packages:
   
    conda install requests beautifulsoup4


### Usage
- To download the content of a web page, use the following command:

       python web_downloader.py URL

- Replace the URL with the URL link of the web page  to download using the following command line:

       python web_downloader.py " URL LINK "

The script will download the text content from the provided URL and save it to a file named web_content.txt in the same directory.


### Exporting Conda Environment
If you need to recreate the Conda environment with the required dependencies, you can export it to a YAML file using the following command:


### Contributing
Feel free to open an issue or create a pull request if you have suggestions, improvements, or bug fixes. Contributions are  more than welcome!

### License
This project is licensed under the MIT License. See the LICENSE file for details
