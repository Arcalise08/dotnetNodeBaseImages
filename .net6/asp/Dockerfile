FROM mcr.microsoft.com/dotnet/aspnet:6.0
RUN apt update && apt install -y curl
RUN curl -fsSL https://deb.nodesource.com/setup_18.x | bash - &&\
apt-get install -y nodejs
RUN node --version
RUN npm --version
RUN npm i -g yarn
