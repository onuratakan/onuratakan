
<p align="center">
  <a href="https://github.com/onuratakan">
    <img src="https://avatars.githubusercontent.com/u/41792982?v=4" alt="Avatar" width="260" height="260">
  </a>

  <h1 align="center">Onur Atakan ULUSOY</h1>

  <p align="center">
    Hi there 👋 I’m currently working on the Python, Django, WEB, WordPress, Java, Robotics, Image Proccessing, Cyber Security and Blockchain.
    <br />
    <br />

  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=onuratakan&theme=blue-green&layout=compact)](https://github.com/anuraghazra/github-readme-stats" alt="Most used languages">
  <br />
  <br />
  <img src="https://github-readme-stats.vercel.app/api?username=onuratakan&theme=blue-green&show_icons=true)](https://github.com/anuraghazra/github-readme-stats" alt="Onur Atakan's github stats">

  <br />
  <br />
  
  <img src="https://github-profile-trophy.vercel.app/?username=onuratakan&theme=darkhub&row=1&no-bg=true)](https://github.com/ryo-ma/github-profile-trophy" alt="Onur Atakan's github trophy">
  
  </p>
</p>

<p align="center">
  <img align="center" src="/github-metrics.svg" alt="Metrics" width="450">
</p>

```python
#!/usr/bin/python3
# -*- coding: utf-8 -*-


import json
from hashlib import sha256


class Onur_Atakan_ULUSOY:
    """
    Onur Atakan ULUSOY is a human, loves programming, and supports open source projects.
    """

    def __init__(self):
        self.type = "Human-Male"
        self.age = 15
        self.country = "Turkey"
        self.city = "Sivas"

        self.job = "Programmer"
        self.working_areas = [
            "Python",
            "Django",
            "WEB",
            "WordPress",
            "Java",
            "Robotics",
            "Image Proccessing",
            "Cyber Security",
            "Blockhain"
        ]

        self.projects = [
            ["Decentra Network", "https://github.com/Decentra-Network/Decentra-Network"],
            ["MIXON", "https://github.com/onuratakan/MIXON"],
            ["(POW) Blockchain Network Infrustructure", "https://github.com/onuratakan/POW-Blockchain-Network-Infrustructure"],
            ["ONUR Voice Assistant", "https://github.com/onuratakan/ONUR_Voice_Assistant"],
            ["HACON", "https://github.com/onuratakan/HACON"],
            ["Site Seo Scanner", "https://github.com/onuratakan/Site_Seo_Scanner"],
            ["Ask Me Something", "https://github.com/onuratakan/ask_me_something"],
            ["Say Me Something", "https://github.com/onuratakan/say_me_something"],
            ["Linear Congruential Generator", "https://github.com/onuratakan/Linear_Congruential_Generator"],
            ["Get Crypto Price", "https://github.com/onuratakan/get_crypto_price"],
            ["RSI Calculator", "https://github.com/onuratakan/rsi_calculator"],
            ["TD Sequential Calculator", "https://github.com/onuratakan/td_sequential_calculator"],
            ["Haimgard", "https://github.com/onuratakan/Haimgard"],
            ["Speed Calculator", "https://github.com/onuratakan/speed_calculator"],
            ["Blur Image", "https://github.com/onuratakan/blur_image"],
            ["My System Monitor", "https://github.com/onuratakan/mysystemmonitor"],
            ["GitHub Full Backup", "https://github.com/onuratakan/GitHub-Full-Backup"]
        ]

        self.libraries = [
            ["HACON", "https://pypi.org/project/hacon/"],
            ["Linear Congruential Generator", "https://pypi.org/project/Linear-Congruential-Generator/"],
            ["Site Seo Scanner", "https://pypi.org/project/Site-Seo-Scanner/"],
            ["Say Me Something", "https://pypi.org/project/say-me-something/"],
            ["Ask Me Something", "https://pypi.org/project/ask-me-something/"],
            ["ONUR Voice Assistant", "https://pypi.org/project/ONUR-Voice-Assistant/"],
            ["Get Crypto Price", "https://pypi.org/project/get-crypto-price/"],
            ["RSI Calculator", "https://pypi.org/project/rsi-calculator/"],
            ["TD Sequential Calculator", "https://pypi.org/project/td-sequential-calculator/"],
            ["Haimgard", "https://pypi.org/project/haimgard/"],
            ["Speed Calculator", "https://pypi.org/project/speed-calculator/"],
            ["Blur Image", "https://pypi.org/project/blur-image/"]
            ["My System Monitor", "https://pypi.org/project/mysystemmonitor/"],
            ["GitHub Full Backup", "https://pypi.org/project/GitHub-Full-Backup/"]            
        ]

        self.website = "https://onuratakan.github.io/"
        
        self.cv = "https://onuratakan.github.io/online-cv/"
        
        self.linkedin = "https://www.linkedin.com/in/onur-atakan-ulusoy/"

    def dump_json(self):
        """
        Returns a json containing the Onur_Atakan_ULUSOY data.
        """

        data = {
            "type": self.type,
            "age": self.age,
            "country": self.country,
            "city": self.city
        }
        return data

    def get_hash(self, encoding="ascii"):
        """
        Returns a sha256 created using the dump_json() function.
        """

        transaction_data = json.dumps(self.dump_json()).encode(encoding)
        return sha256(transaction_data).hexdigest()


if __name__ == "__main__":
    the_onur = Onur_Atakan_ULUSOY()
    print(f"ID: {the_onur.get_hash()}")

    print("\nProjects:")
    for project in the_onur.projects:
        print(f"{project[0]}: {project[1]}")

    print("\nLibraries:")
    for library in the_onur.libraries:
        print(f"{library[0]}: {library[1]}") 
    
    print(f"\nWebsite: {the_onur.website}")
    
    print(f"\nCV: {the_onur.cv}")
    
    print(f"\nLinkedIn: {the_onur.linkedin}")

```
