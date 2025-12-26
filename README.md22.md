![mws_automation]( file:///C:/Users/Dell/Desktop/39e54d2f-6dbd-44d2-ab20-6699debabb88.png)
# Amazon MWS Order API to Google Sheets #
With the world taking a frog leap into the eCommerce world, more and more people start selling their products on Amazon. However, once you start hitting the mass scale and you have orders coming every minute, it can be hard to get a grasp of all the data. The basic Amazon dashboards are limited, and you will soon find yourself using proprietary tools charging hefty monthly subscriptions. In this video, I will show you how easy it is to integrate Amazon MWS API with Google Sheets and collect data of your orders daily. We will use the Python programming language with some 3rd party libraries.


## Create .env and get client_secret.json from GCP
.env example
```buildoutcfg
MWS_ACCESS_KEY="XXXXJJVN6XXNSP3XXXX"
MWS_SECRET_KEY="XXXXwQuqXXTshxEsQYmXXXX92eb6ZsNzjMmvXXXX"
MWS_SELLER_ID="XXXXJ965EXXXX"

GOOGLE_SHEET_KEY=XXXNDDjLr42RKWeqzmY_XXXX7d4yF_nuZKwHXXXX
```

## Setup Python Virtual Environment
```buildoutcfg
pipenv install
pipenv shell
```
## Running Script

```buildoutcfg
python script.py
```

