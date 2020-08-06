The firmware for this challenge was larger than GitHub's allowed limit (100M). Due to this restriction the file archive has been split using the following command: `gzip --best -c h1_iotv_firmware_challenge.tar | split -d -b 45M - "pretty-happy-web-processor.tar.gz.part"`

To extract the firmware image: `cat pretty-happy-web-processor.tar.gz.part* | tar -zxv`
