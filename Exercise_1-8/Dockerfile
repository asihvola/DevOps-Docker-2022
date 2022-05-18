# Käytetään Ubuntun 20.04 versiota
FROM ubuntu:20.04

# Asennetaan curl
RUN apt-get update; apt-get install -y curl;

# Ajetaan scripti jossa kysellään webbiosoitetta
CMD echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;
