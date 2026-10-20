AI Smart Traffic Management System (Prototype)

Built for DEXATHON 2026 – category: AI & Machine Learning.

Problem

Standard traffic signals run their full timer even when the road is empty. Vehicles on the busy road keep waiting, fuel is wasted, and ambulances get stuck in the same queues.

Solution

An AI module that:

takes live traffic data (satellite imagery / Google Maps traffic layer) as input,
manages traffic lights and signals on its own, skipping empty lanes and giving green time where vehicles are waiting,
detects ambulances through a special in-vehicle sensor and clears the route ahead of them.
About this prototype

index.html is a browser-based simulation of a four-way junction. The traffic feed, sensor and AI controller are simulated so the idea can be demonstrated without hardware.

AI adaptive mode: skips empty lanes, gives green to the busier road (min 3 s, max 14 s green).
Fixed timer mode: switches every 8 s regardless of traffic (the problem we are solving).
Ambulance priority: a sensor ping forces a green corridor in AI mode.
Live stats: green time wasted on an empty road, average wait per vehicle, last ambulance delay.
Run it

No installation needed. Open index.html in any modern browser.

Host it free with GitHub Pages
Push this folder to a GitHub repository.
Go to Settings > Pages.
Under Branch, choose main and / (root), then save.
Your demo will be live at https://1kylash.github.io/AI-Smart-Traffic-Management-System/

Tech

HTML, CSS, JavaScript (Canvas). No external libraries.

Future scope
Real data from the Google Maps Traffic API
Vehicle detection from camera feeds (YOLO + OpenCV)
Real GPS transmitter in ambulances
City-wide coordination of multiple junctions
Accident and weather alerts, pedestrian-aware timing

Team Fantastic Six:                                                                                                                       
   1.Kevin Franco R V                                                                                                                     
   2.M Kylash                                                                                                                             
   3.Muhammed Rayyan                                                                                                                      
   4.Malavika M                                                                                                                           
   5.Nanthini R                                                                                                                           
   6.Maathyesh Vijay SP
