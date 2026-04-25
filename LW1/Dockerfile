FROM python:latest 
# Bad: using full image
# Bad: using latest tag

# Bad: Don't set a working directory

COPY . . 
# Bad: Copying everything and after running install dependencies

RUN pip install -r requirements.txt 

CMD ["python3", "main.py"]