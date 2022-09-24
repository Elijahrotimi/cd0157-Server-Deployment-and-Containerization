FROM python:3.7.2-slim	#defines source image

COPY . /app				#copies file to the image
WORKDIR /app			#defines working directory for other commands

RUN pip install --upgrade pip		#'RUN' is used to run commands other than the main executable
RUN pip install flask


ENTRYPOINT ["python", "app.py"]		#Entrypoint is used to define the main executable

