# BROKERS

## PREREQUISITE
1. Install Python package from official website
2. Install VSCode extension and set the correct interpreter by typing `Ctrl + Shift + P` and typing `Python Select Interpreter`
3. Navigate to the appropriate directory and create virtual environment using `python3 -m venv kafka_env`
4. Activate the new virtual environment using `source kafka_env/bin/activate`
5. Install `confluent-kafka` package using `pip3 install confluent-kafka`
6. Pull depdencies in `requirements.txt` by using `pip freeze > requirements.txt`. This will automatically create the file if it doesn't exist.
7. Create a new file called `client.properties` and paste the details from Confluent
8. Run the code in main.py using `python3 main.py`
