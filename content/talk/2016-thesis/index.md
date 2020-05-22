---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Quantum key distribution devices: How to make them and how to break them"
event: "Thesis defense"
event_url:
location: "University of Waterloo"
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "As more aspects of modern society depend on digital communication, we increasingly rely on infrastructure that ensures the privacy and security of this communication. Classically, this has been provided by cryptographic protocols such as public-key encryption, in which secrets called keys are exchanged between different parties to enable secure communication. The rapid development of quantum algorithms which violate the assumptions of these protocols, however, poses a security challenge to modern cryptography. Quantum resources can also be used to strengthen cryptographic security, particularly the security of key exchange protocols. This approach, QKD, can be implemented by encoding in quantum systems such as single photons sent through free-space or a fiber. Fiber based QKD devices are already commercially available, but are fundamentally limited to distributing keys over a few hundred kilometers. To address this distance limitation, research QKD systems are being developed to exchange keys through free-space to satellites. This work considers practical challenges to building and testing both types of QKD devices. Firstly, we consider modeling and mission analysis for airborne demonstrations of QKD to stratospheric balloons and aircraft to simulate a satellite. Based on the mission parameters available for both platforms, we found aircraft platforms were more promising for testing prototype QKD satellite systems. We developed a mission planning tool to help design the flight geometries for testing the device. Next, we developed three new components for a QKD satellite prototype. The requirements for electro-optical devices in orbit are very different from lab environments, mandating new approaches to designing QKD devices. We developed a quad single photon detector package to meet the requirements for free-space links to low earth orbit. Moreover, we designed and built optical systems for analyzing the polarization of photons and an adaptive optics unit to increase the efficiency of collecting the encoded photons. All three devices were tested in conditions that simulated the time and loss of a satellite pass. Finally, we demonstrated a laser damage attack on a live commercial QKD system. Our attack injected additional optical power into the sender device to modify security-critical components. Specifically, our attack damaged the PIN diodes which monitor the encoded photon number, reducing their sensitivity or completely blinding them. Our damage could compromise the entire key, and was performed during system operation while raising no alarms. In summary, this work shows the trade-offs of testing QKD payloads on different airborne platforms, develops components for a satellite QKD payload, and demonstrates a security vulnerability in a commercial QKD system that can fully compromise the key. These results help address practical challenges to building QKD devices, improving the security of modern cryptography."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2016-08-10T09:00:00-05:00
#date_end: 2020-04-29T22:11:08-07:00
all_day: false

# Schedule page publish date (NOT talk date).
#publishDate: 2020-04-29T22:11:08-07:00

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["Research"]
---
