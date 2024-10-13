FROM python:3.8.10
ENV OPEN_AI_ORG=
ENV OPEN_AI_KEY=
ENV ELEVEN_LABS_API_KEY=

WORKDIR /src

ADD ./ /src

RUN pip3 install --upgrade pip
RUN pip3 install --no-cache-dir -r requirements.txt

EXPOSE 8000 

CMD ["python3", "main.py"]
