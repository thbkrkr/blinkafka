# blinkafka

[Blink](https://www.blinkstick.com/) LEDs on Kafka messages.

## Install

```sh
sudo apt-get install -y python python-pip
sudo pip install blinkstick
sudo pip install kafka-python
```

## Run

```sh
export B=broker:9093
export U=user
export P=password
export T=topic

./blinkafka
```
