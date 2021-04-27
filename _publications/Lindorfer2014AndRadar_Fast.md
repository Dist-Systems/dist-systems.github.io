---
# Automatically generated by bib2md.py
title: "AndRadar: Fast Discovery of Android Applications in Alternative Markets"
slug: "Lindorfer2014AndRadar_Fast"
date: "2014-07-01"
publishdate: "2000-01-01"

authors:
  - "Martina Lindorfer"
  - "Stamatis Volanis"
  - "Alessandro Sisto"
  - "Matthias Neugschwandtner"
  - "Elias Athanasopoulos"
  - "Federico Maggi"
  - "Christian Platzer"
  - "Stefano Zanero"
  - "Sotiris Ioannidis"

category: conference
venue: "Detection of Intrusions and Malware, and Vulnerability Assessment (Lecture Notes in Computer Science)"


slides: no
paper: no
text: no
external_url: http://link.springer.com/chapter/10.1007/978-3-319-08509-8_4
video_url: no

bibtex: |
    @inproceedings{Lindorfer2014AndRadar_Fast,
      title     = {{AndRadar: Fast Discovery of Android Applications in Alternative Markets}},
      author    = {Lindorfer, Martina and Volanis, Stamatis and Sisto, Alessandro and Neugschwandtner, Matthias and Athanasopoulos, Elias and Maggi, Federico and Platzer, Christian and Zanero, Stefano and Ioannidis, Sotiris},
      booktitle = {Detection of Intrusions and Malware, and Vulnerability Assessment},
      series    = {Lecture Notes in Computer Science},
      month     = {July},
      year      = {2014},
      copyright = {©2014 Springer International Publishing Switzerland},
      isbn      = {978-3-319-08508-1 978-3-319-08509-8},
      language  = {en},
      pages     = {51--71},
      publisher = {Springer International Publishing},
      url       = {http://link.springer.com/chapter/10.1007/978-3-319-08509-8_4}
    }




---

Compared to traditional desktop software, Android applications are delivered through software repositories, commonly known as application markets. Other mobile platforms, such as Apple iOS and BlackBerry OS also use the marketplace model, but what is unique to Android is the existence of a plethora of alternative application markets. This complicates the task of detecting and tracking Android malware. Identifying a malicious application in one particular market is simply not enough, as many instances of this application may exist in other markets. To quantify this phenomenon, we exhaustively crawled 8 markets between June and November 2013. Our findings indicate that alternative markets host a large number of ad-aggressive apps, a non-negligible amount of malware, and some markets even allow authors to publish known malicious apps without prompt action. Motivated by these findings, we present AndRadar, a framework for discovering multiple instances of a malicious Android application in a set of alternative application markets. AndRadar scans a set of markets in parallel to discover similar applications. Each lookup takes no more than a few seconds, regardless of the size of the marketplace. Moreover, it is modular, and new markets can be transparently added once the search and download URLs are known. Using AndRadar we are able to achieve three goals. First, we can discover malicious applications in alternative markets, second, we can expose app distribution strategies used by malware developers, and third, we can monitor how different markets react to new malware. During a three-month evaluation period, AndRadar tracked over 20,000 apps and recorded more than 1,500 app deletions in 16 markets. Nearly 8% of those deletions were related to apps that were hopping from market to market. The most established markets were able to react and delete new malware within tens of days from the malicious app publication date while other markets did not react at all.