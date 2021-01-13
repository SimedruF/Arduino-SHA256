# Arduino-SHA256
generates SHA256 in Arduino, no need of any external header files

### Usage

String data = "enter your string here";

String hashed_data = SHA256(data);

#### hashed_data will contain the sha256 value of the data

Tested with string "xyz" and with empty string "".

SHA256 for xyz is 3608bca1e44ea6c4d268eb6db02260269892c0b42b86bbf1e77a6fa16c3c9282

SHA256 for "" is e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855

