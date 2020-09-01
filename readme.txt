What is this?
===========================
This NodeJS script imports purchase files to Sailthru. Files should be local to the machine running this script. API key, secret and filepath are passed as command line arguments.

How do I use it?
==========================
1. Download or clone the package from this repository
2. In terminal, navigate to the cloned directory OR to the one created by unzipping the downloaded file
3. Run the command 'npm install' to install the sailthru-client dependency
4. Run the following command to run the import job: 'node index.js <api_key> <api_secret> <filepath> <list name>'

A note on list names
==========================
The list name parameter is a list within Sailthru that users will be imported to, and is required for the "import" job to run. List names within Sailthru can contain whitespace characters. If you intend to use these in your list name, please be careful to treat your list name as a string, wrapping it in either single or double quotation marks.
