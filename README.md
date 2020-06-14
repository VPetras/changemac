# changemac
This repository is for systemd service which every start of raspberry pi change its mac adrress. This service execute shell script changemac.sh in the root directory of raspberry pi.
In the file changemac.sh rewrite xx:xx:xx:xx:xx:xx with your specific mac adrress.
The file changemac.service move to /etc/systemd/system/ and then type sudo systemctl enable changemac.service then sudo systemctl start changemac.service and it will start service.
