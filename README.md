
<p align="center">
  <a href="https://github.com/onuratakan">
    <img src="https://avatars.githubusercontent.com/u/41792982?v=4" alt="Avatar" width="260" height="260">
  </a>

  <h1 align="center">Onur Atakan ULUSOY</h1>

  <p align="center">
    Hi there 👋 I’m currently working on the Pyhton, Django, WEB, WordPress, Java, Robotics, Image Proccessing, Cyber Security and Blockchain.
    <br />
    <br />

  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=onuratakan&theme=blue-green&layout=compact)](https://github.com/anuraghazra/github-readme-stats" alt="Most used languages">
  <br />
  <br />
  <img src="https://github-readme-stats.vercel.app/api?username=onuratakan&theme=blue-green&show_icons=true)](https://github.com/anuraghazra/github-readme-stats" alt="Onur Atakan's github stats">

  <br />
  <br />
  
  <img src="https://github-profile-trophy.vercel.app/?username=onuratakan&row=1&no-bg=true)](https://github.com/ryo-ma/github-profile-trophy" alt="Onur Atakan's github trophy">
  
  </p>
</p>

```python
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
    print(Onur_Atakan_ULUSOY().get_hash())

```
