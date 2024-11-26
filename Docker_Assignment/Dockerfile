FROM python:3.11.5
WORKDIR /Docker_Assignment
COPY requirement.txt .
RUN pip install -r requirement.txt
COPY . .
EXPOSE 8000

# Command to run the application
CMD ["uvicorn", "app:app", "--host", "0.0.0.0", "--port", "8000"]
