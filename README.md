
<p align="center">
<img src="https://www.office1.com/hubfs/Office1%20Blog%20-%20Graphics%20and%20Images/Phishing%20Blog%201.png#keepProtocol", width="500", height="500">
</p>
<h1 align="center"> DEDSEC_Zloy_moshennik</h1>
<h4 align="center">Dedsec_Zloy_moshennik is a Linux-based scammer phishing page flooder capable of sending ultra-realistic account information (username and password).
</h4>

## DESCRIPTION
Dedsec_Zloy_moshennik is a Linux-based tool designed for phishing attacks. This tool serves as a page flooder, flooding phishing pages with traffic to mimic realistic user interactions. Notably, it possesses the capability to dispatch ultra-realistic account information, including both username and password details, enhancing its deceptive nature in fraudulent activities.

<h3 align="center"> FLOODER IMAGE</h3>
<p align="center">
<img src="https://i.imgur.com/DLYYGmp.png", width="900", height="900">
</p>

<h3 align="center"> ACTUAL PHISHING PAGE</h3>
<p align="center">
<img src="https://i.imgur.com/iGVKiC0.png", width="500", height="500">
</p>

### You can replace the code below for your website's url, header and body
```python
            url = "https://api.ldpform.com/sendform"

            headers = {
                "Host": "api.ldpform.com",
                "Origin": "https://www.lucky-gift-hunyo.online",
                "Referer": "https://www.lucky-gift-hunyo.online/",
                "User-Agent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/119.0.0.0 Safari/537.36"
            }

            body = {
                "form_config_id": random_id,
                "ladi_form_id": "FORM24",
                "ladipage_id": random_id,
                "tracking_form": [
                    {"name": "url_page", "value": "https://www.lucky-gift-hunyo.online/"},
                    {"name": "utm_source", "value": ""},
                    {"name": "utm_medium", "value": ""},
                    {"name": "utm_campaign", "value": ""},
                    {"name": "utm_term", "value": ""},
                    {"name": "utm_content", "value": ""},
                    {"name": "variant_url", "value": ""},
                    {"name": "variant_content", "value": ""}
                ],
                "form_data": [
                    {"name": "form_item12", "value": f"{email}"},
                    {"name": "password", "value": f"{password}"}
                ],
                "data_key": None,
                "status_send": 2,
                "total_revenue": 0,
                "time_zone": 7
            }
```
## INSTALLATION 
    * git clone https://github.com/0xbitx/DEDSEC_Zloy_moshennik.git
    * cd DEDSEC_Zloy_moshennik
    * python3 dedsec_flood.py

### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 
* Ubuntu
  
<h1 align="center"> DISCLAIMER </h1>

<h4 align="center">I'm not responsible for anything you do with this program, so please only use it for good and educational purposes. </h4>
