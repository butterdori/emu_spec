# emu_spec
Power and set configuration of semi-high speed electric multiple units (EMUs)  

# Table
| Train Model | Top Speed (km/h) | topSpeed (m/s) | Consist | Motor Config | Total Power (kW) | power per car (kW) | Total Tractive Effort (kN) | tractiveEffort per car (kN) | Total Weight (t) | weight per car (t) | Starting Acceleration | Profile Description |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **JR Shikoku 8600 Series** | 130 | 36.111 | 3 Cars | 2M1T (3-car); 1M1T (2-car); 2M2T (4-car); 3M2T (5-car); 4M3T (7-car); 4M4T (8-car) | 1,760 | 586.6 | 110 | 36.6 | 115 | 38.3 | 2.0 km/h/s (0.56 m/s²) | Matches legacy tilting trains for steep grades in Shikoku. |
| **Korail Class 200k (Nuriro)** | 150 | 41.667 | 4 Cars | 2M2T (4-car) | 2,000 | 500.0 | 145 | 36.25 | 171 | 42.7 | 2.5 km/h/s (0.69 m/s²) | High power-to-weight ratio designed for rapid regional departures. |
| **Siemens Desiro (Class 350)** | 160 | 44.444 | 4 Cars | 2M2T (4-car) | 1,500 | 375.0 | 200 | 50.0 | 170 | 42.5 | 3.6 km/h/s (1.00 m/s²) | Commuter-focused traction designed to clear platforms rapidly. |
| **JR Kyushu 885 Series** | 130 | 36.111 | 6 Cars | 3M3T (6-car); 3M2T (5-car historical) | 2,280 | 380.0 | 155 | 25.8 | 220 | 36.6 | 2.2 km/h/s (0.61 m/s²) | Balanced for mountainous terrain and maintaining speed through curves. |
| **JR West 681 Series** | 160 | 44.444 | 6 Cars | 2M4T (6-car); 1M2T (3-car); 3M6T (9-car) | 2,640 | 440.0 | 208 | 34.6 | 240 | 40.0 | 1.8 km/h/s (0.50 m/s²) | Heavy steel chassis limits starting acceleration, prioritizing momentum. |
| **Kintetsu 80000 Series (Hinotori)**| 130 | 36.111 | 6 Cars | 3M3T (6-car); 4M4T (8-car) | 2,880 | 480.0 | 190 | 31.6 | 234 | 39.0 | 2.5 km/h/s (0.70 m/s²) | Strong acceleration typical of Kintetsu's private railway express fleet. |
| **Korail Class 210k (ITX)** | 150 | 41.667 | 6 Cars | 3M3T (6-car) | 3,000 | 500.0 | 185 | 30.8 | 267 | 44.5 | 2.4 km/h/s (0.67 m/s²) | Strong initial acceleration to match historical predecessor timings. |
| **Stadler KISS (RABe 511)** | 160 | 44.444 | 6 Cars | 2M4T (6-car); 2M2T (4-car) | 4,000 | 666.6 | 400 | 66.6 | 297 | 49.5 | 3.9 km/h/s (1.10 m/s²) | Extremely high starting torque standard for European double-deck commuter EMUs. |
| **Odakyu 70000 Series (GSE)** | 120 | 33.333 | 7 Cars | 4M3T (7-car) | 3,040 | 434.2 | 200 | 28.5 | 256 | 36.5 | 2.0 km/h/s (0.56 m/s²) | Smooth acceleration profile for luxury sightseeing service. |
| **Keikyu N1000 Series** | 130 | 36.111 | 8 Cars | 6M2T (8-car); 4M2T (6-car); 4M0T / 2M2T (4-car) | 3,720 | 465.0 | 300 | 37.5 | 255 | 31.8 | 3.5 km/h/s (0.97 m/s²) | Exceptionally high acceleration, characteristic of Keikyu's aggressive timetable engineering. |
| **Keisei AE (Skyliner)** | 160 | 44.444 | 8 Cars | 6M2T (8-car) | 4,200 | 525.0 | 180 | 22.5 | 298 | 37.2 | 2.0 km/h/s (0.55 m/s²) | Tuned for sustained 160 km/h top-speed cruising rather than initial pull. |
| **JR East E353 Series** | 130 | 36.111 | 9 Cars | 5M4T (9-car); 2M1T (3-car); 7M5T (12-car) | 2,800 | 311.1 | 200 | 22.2 | 333 | 37.0 | 2.0 km/h/s (0.56 m/s²) | Modern standard for JR East Limited Express runs on the Chuo Main Line. |
| **JR East E657 Series** | 130 | 36.111 | 10 Cars | 6M4T (10-car) | 3,360 | 336.0 | 215 | 21.5 | 385 | 38.5 | 2.0 km/h/s (0.56 m/s²) | Standard acceleration for high-capacity commuter/express routes. |
| **TRA EMU900 Series** | 130 | 36.111 | 10 Cars | 4M6T (10-car) | 4,000 | 400.0 | 350 | 35.0 | 430 | 43.0 | 2.8 km/h/s (0.80 m/s²) | Modern commuter rail acceleration tuned for dense stop-and-go regional service. |
| **TRA EMU3000 Series** | 130 | 36.111 | 12 Cars | 6M6T (12-car) | 4,560 | 380.0 | 381 | 31.7 | 545 | 45.4 | 2.5 km/h/s (0.70 m/s²) | High starting torque utilizing 24 independent traction motors. |
| **Shinkansen 100 Series** | 220 | 61.111 | 16 Cars | 12M4T (16-car); 4M2T (6-car); 4M0T (4-car) | 11,040 | 690.0 | 540 | 33.7 | 925 | 57.8 | 1.6 km/h/s (0.44 m/s²) | Heavy double-deck cars and older DC motors limited the starting pull. |
| **Shinkansen 300 Series** | 270 | 75.000 | 16 Cars | 10M6T (16-car) | 12,000 | 750.0 | 430 | 26.8 | 711 | 44.4 | 1.6 km/h/s (0.44 m/s²) | First-generation Nozomi; lower acceleration due to early AC traction motor limitations. |
| **Shinkansen 700 Series** | 285 | 79.166 | 16 Cars | 12M4T (16-car); 6M2T (8-car) | 13,200 | 825.0 | 460 | 28.7 | 708 | 44.2 | 2.0 km/h/s (0.56 m/s²) | Improved acceleration over earlier Shinkansen models to navigate the Tokaido line. |
| **Shinkansen 500 Series** | 300 | 83.333 | 16 Cars | 16M0T (16-car); 8M0T (8-car) | 18,240 | 1,140.0 | 480 | 30.0 | 700 | 43.7 | 1.9 km/h/s (0.53 m/s²) | Gearing is entirely dedicated to maintaining 300 km/h rather than starting quickly. |
| **Shinkansen N700 Series** | 300 | 83.333 | 16 Cars | 14M2T (16-car); 8M0T (8-car) | 17,080 | 1,067.5 | 600 | 37.5 | 700 | 43.7 | 2.6 km/h/s (0.72 m/s²) | Very high acceleration for a bullet train, achieved via high motorization ratio (14M2T). |
