.PHONY: run setup clean

run: venv/bin/activate
	./venv/bin/python main.py

setup: venv/bin/activate
	./venv/bin/pip install -r requirements.txt

clean:
	rm -rf __pycache__
	rm -rf venv

venv/bin/activate: requirements.txt
	virtualenv venv
	./venv/bin/pip install -r requirements.txt