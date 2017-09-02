# pypromptpay
QR Code PromptPay in Python 3.



## install

```
pip install pypromptpay
```

## Using

```python
from pypromptpay import qr_code
qr_code(account,one_time=True,path_qr_code="",country="TH",money="",currency="THB")
```

- account is phone number or  identification number.
- one_time : if you use once than it's True.
- path_qr_code : path save qr code.
- country : TH
- money : money (if have)
- currency : THB

## License

Apache Software License 2.0



## Develop

Wannaphong Phatthiyaphaibun (wannaphong@kkumail.com)