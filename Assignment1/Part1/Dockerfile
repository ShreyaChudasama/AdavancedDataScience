# Use the basic Python 3 image as launching point
FROM ubuntu

# Update

# Add the script to the Dockerfile


RUN ["apt-get", "update"]
RUN ["apt-get", "install", "python","-y"]
RUN ["apt-get", "install","python-pip","-y"]
RUN ["apt-get", "install","python3-pip","-y"]
ADD WebScraping.py /home
RUN ["pip3", "install", "bs4"]
RUN ["pip3", "install", "lxml"]
CMD ["pip3", "install", "bs4"]
CMD ["pip3", "install", "lxml"]
CMD ["pip3", "install", "urllib3"]
RUN ["pip3", "install", "boto"]
# Execute the script