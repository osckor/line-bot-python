# line-bot-python
Try line-bot-sdk with Python

## Reference
- https://qiita.com/shimajiri/items/cf7ccf69d184fdb2fb26

## Setup
```
$ git clone https://github.com/tayutaedomo/line-bot-python
$ cd line-bot-python
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

## ENV
```
$ export LINE_CHANNEL_ACCESS_TOKEN=<YOUR_CHANNEL_ACCESS_TOKEN>
$ export LINE_CHANNEL_SECRET=<YOUR_CHANNEL_SECRET>
```

## Local Server
```
$ cd line-bot-python
$ python app.py
$ open "http://localhost:5000/"
```

