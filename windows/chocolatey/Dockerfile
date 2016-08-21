# DOCKER-VERSION 1.12
#
# https://github.com/richardkdrew/dockerfiles
#
FROM windowsservercore

MAINTAINER Richard Drew <richardkdrew@gmail.com>

# Install Chocolatey
RUN @powershell -NoProfile -ExecutionPolicy unrestricted -Command "(iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))) >$null 2>&1" \
    && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bi

CMD powershell