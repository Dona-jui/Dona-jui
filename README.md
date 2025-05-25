<!-- Banner Section -->
![Image](https://github.com/user-attachments/assets/68580f51-8449-4123-a97d-7bfd8ce7375f)

```python
#Just Another Class in the ML Universe
import torch

class DonaRoy(torch.nn.Module):
    def __init__(self):
        super(DonaRoy, self).__init__()
        self.name = "Dona Roy"
        self.education = [
            "M.Tech CSE (Information Security) @ NITK Surathkal (2024–2026)",
            "B.Tech CSE @ JIS College of Engineering (2020–2024)"
        ]
        self.role = "Information Security | AI/ML Enthusiast"
        self.day_skills = [
            "Java", "Python", "Tensorflow", "Pytorch", "Javascript"
        ]
        self.night_skills = [
            "DSA", "Full-Stack Experiments", "Side Projects", "Research Papers"
        ]
        self.creative_skills = [
            "Fiction", "Painting", "Photography", "Music"
        ]
        self.links = {
            "email": "donaroy5889@gmail.com",
            "github": "https://github.com/Dona-jui",
            "linkedin": "https://linkedin.com/in/donaroy",
            "kaggle": "https://kaggle.com/donajui"
        }

    def forward(self, curiosity, caffeine):
        return self.day_skills + self.night_skills + ["More Ideas"]

    def creative_mode(self, inspiration=1.0):
        if inspiration > 0.5:
            return f"Engaged in: {', '.join(self.creative_skills)}"

# Example instance
dona = DonaRoy()
```

<p align="center">
  <i>“Stay curious. Stay building. Stay kind.”</i><br/>
  <sub>Last updated on: May 25, 2025</sub>
</p>
