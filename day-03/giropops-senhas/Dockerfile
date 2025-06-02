FROM cgr.dev/chainguard/python:latest-dev AS build

WORKDIR /app

RUN python -m venv .venv
ENV PATH="/app/.venv/bin":$PATH

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

FROM cgr.dev/chainguard/python:latest

WORKDIR /app

COPY app.py app.py
COPY templates templates/
COPY static static/

COPY --from=build /app/.venv /app/.venv
ENV PATH="/app/.venv/bin:$PATH"
ENV FLASK_APP=app.py

ENTRYPOINT []
CMD ["python", "-m", "flask", "run", "--host=0.0.0.0"]