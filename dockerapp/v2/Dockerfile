FROM python:3.6
RUN pip install Flask==0.12.2
RUN useradd -ms /bin/bash admin
USER admin
WORKDIR /app
COPY app /app
CMD ["python","app.py"]