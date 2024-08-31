import requests
import json

headers = {
    'Content-Type': 'application/json; charset=utf-8',
    'User-Agent': 'Dalvik/2.1.0 (Linux; U; Android 11; Redmi 8A MIUI/V12.5.2.0.QCMMIXM)',
    'Host': 'new-fapi.syriatel.sy',
    'Connection': 'Keep-Alive',
}

data = json.dumps('{gsm:your number,password:your pass,appVersion:5.5.0,OS_Type:2,mobileManufaturer:Xiaomi,mobileModel:Redmi}')
response = requests.post('https://new-fapi.syriatel.sy/Wrapper/app/7/SS2MTLGSM/api2/SignIn', headers=headers, data=data).text
