### Install: 
```bash
Make sure you have python installed
git clone "https://github.com/ravali121/NewProjectCreationAutomation.git"
cd NewProjectCreationAutomation
pip install -r dependencies.txt
touch .env
Then open the .env file and store your username, password, github auth_token and desired file destination. Use the provided format at the bottom of this README.
source ~/FILEPATH/.create_project.sh
```

### Usage:
```bash
To run the script type in 'create <name of your folder>'
```

### Env File Format:
```bash
USERNAME="Username123"
PASSWORD="Password123"
ACCESS_TOKEN="Generate this in your git account"
FILEPATH="/path/to/your/project/"
```
