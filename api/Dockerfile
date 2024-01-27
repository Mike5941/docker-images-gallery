FROM python:3.9

WORKDIR /app

EXPOSE 5050

COPY Pipfile Pipfile.lock ./

RUN pip install pipenv
RUN pipenv install --deploy --ignore-pipfile

COPY . ./

CMD ["pipenv", "run", "python", "main.py"]