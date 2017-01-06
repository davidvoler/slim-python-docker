FROM sruml/alpine-python:2.7-onbuild

# Add the application to the image
ADD . /app

WORKDIR /app

# Expose the Flask port
EXPOSE 8000

# Run the Flask app
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]