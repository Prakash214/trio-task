#Use Python 3.6 as a base image
FROM python3.6
# Copy contents into image
COPY . .
# install pip dependencies from requirements file
RUN pip3 install -r requirements.txt
# Expose correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT [ "python", "app.py" ]
