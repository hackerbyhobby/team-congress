#  Module 6 Challenge
> Module 6 Challenge for ASU AI Bootcamp

I did this assignment on my own, but there's a high possibility I help others as they experience challenges with their own code

In this challenge, I developed a prediction system that will help the NOOA Space Weather Prediction Center predict Geomagnetic Storms (GSTs). This was done using NASA's DONKI (The Space Weather Database Of Notifications, Knowledge, Information (DONKI))open API and more specifically, the APIs for Coronal Mass Ejections (CME) and Geomagnetic Storms (GST). Using each of the two component services (CME, GST) endpoints, I pulled data and created datasets, cleaning, exploring and analyzing the data. Developing the solutions for this project involved gave me additional practical understanding of data exploration, transformation, and analysis, preparing me for more complex data scenarios in future programs. By running this application, users will be able to better predict which CMEs will result in GSTs.

Geomagnetic storms are caused by so-called Coronal Mass Ejections (CMEs), which are a massive bursts of plasma emitted from the Sun in irregular intervals, that Earth's magnetic shield fortunately renders harmless to us. However, this interaction with the magnetic shield can still create so-called Geomagnetic Storms (which also cause the Northern and Southern Lights) that can be harmful to electronic devices such as satellites, GPS systems, and essential parts of our powergrids.

NASA and the Space Weather Prediction Center operate a number of measuring satellites that collect data on CMEs. This data is then used to warn powergrid operators and GPS system operators ahead of time, so that they can make necessary adjustments.

## Installing / Getting started

Open the retrieve_data.ipynb Jupyter notebook using a Jupyter server. Explore the data.

```jupyter lab
retrieve_data.ipynb
```

Run each part of the code in the notebook to explore the data. Note that some of the code is provided to confirm dataset information and to create the requirements for this project.

## Requirements
python version 3.10.14 (main, May  6 2024, 14:42:37) [Clang 14.0.6 ]
pandas version: 2.2.2
requests version: 2.32.3
json version: 2.0.9
also see requirements.txt for dependency details

## Contributing

"If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome."

