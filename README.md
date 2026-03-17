# emu_spec
Power and set configuration of semi-high speed electric multiple units (EMUs)  

# Table
<table>
  <thead>
    <tr>
      <th>Train Model</th>
      <th>Top Speed (km/h)</th>
      <th>topSpeed (m/s)</th>
      <th>Consist</th>
      <th>Motor Config</th>
      <th>Total Power (kW)</th>
      <th>power per car (kW)</th>
      <th>Total Tractive Effort (kN)</th>
      <th>tractiveEffort per car (kN)</th>
      <th>Total Weight (t)</th>
      <th>weight per car (t)</th>
      <th>Starting Acceleration</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>JR Shikoku 8600 Series</strong></td>
      <td>130</td>
      <td>36.111</td>
      <td>3 Cars</td>
      <td>2M1T (3-car); 1M1T (2-car); 2M2T (4-car); 3M2T (5-car); 4M3T (7-car); 4M4T (8-car)</td>
      <td>1,760</td>
      <td>586.6</td>
      <td>110</td>
      <td>36.6</td>
      <td>115</td>
      <td>38.3</td>
      <td>2.0 km/h/s (0.56 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Matches legacy tilting trains for steep grades in Shikoku.</em></td>
    </tr>
    <tr>
      <td><strong>Korail Class 200k (Nuriro)</strong></td>
      <td>150</td>
      <td>41.667</td>
      <td>4 Cars</td>
      <td>2M2T (4-car)</td>
      <td>2,000</td>
      <td>500.0</td>
      <td>145</td>
      <td>36.25</td>
      <td>171</td>
      <td>42.7</td>
      <td>2.5 km/h/s (0.69 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>High power-to-weight ratio designed for rapid regional departures.</em></td>
    </tr>
    <tr>
      <td><strong>Siemens Desiro (Class 350)</strong></td>
      <td>160</td>
      <td>44.444</td>
      <td>4 Cars</td>
      <td>2M2T (4-car)</td>
      <td>1,500</td>
      <td>375.0</td>
      <td>200</td>
      <td>50.0</td>
      <td>170</td>
      <td>42.5</td>
      <td>3.6 km/h/s (1.00 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Commuter-focused traction designed to clear platforms rapidly.</em></td>
    </tr>
    <tr>
      <td><strong>JR Kyushu 885 Series</strong></td>
      <td>130</td>
      <td>36.111</td>
      <td>6 Cars</td>
      <td>3M3T (6-car); 3M2T (5-car historical)</td>
      <td>2,280</td>
      <td>380.0</td>
      <td>155</td>
      <td>25.8</td>
      <td>220</td>
      <td>36.6</td>
      <td>2.2 km/h/s (0.61 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Balanced for mountainous terrain and maintaining speed through curves.</em></td>
    </tr>
    <tr>
      <td><strong>JR West 681 Series</strong></td>
      <td>160</td>
      <td>44.444</td>
      <td>6 Cars</td>
      <td>2M4T (6-car); 1M2T (3-car); 3M6T (9-car)</td>
      <td>2,640</td>
      <td>440.0</td>
      <td>208</td>
      <td>34.6</td>
      <td>240</td>
      <td>40.0</td>
      <td>1.8 km/h/s (0.50 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Heavy steel chassis limits starting acceleration, prioritizing momentum.</em></td>
    </tr>
    <tr>
      <td><strong>Kintetsu 80000 Series (Hinotori)</strong></td>
      <td>130</td>
      <td>36.111</td>
      <td>6 Cars</td>
      <td>3M3T (6-car); 4M4T (8-car)</td>
      <td>2,880</td>
      <td>480.0</td>
      <td>190</td>
      <td>31.6</td>
      <td>234</td>
      <td>39.0</td>
      <td>2.5 km/h/s (0.70 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Strong acceleration typical of Kintetsu's private railway express fleet.</em></td>
    </tr>
    <tr>
      <td><strong>Korail Class 210k (ITX)</strong></td>
      <td>150</td>
      <td>41.667</td>
      <td>6 Cars</td>
      <td>3M3T (6-car)</td>
      <td>3,000</td>
      <td>500.0</td>
      <td>185</td>
      <td>30.8</td>
      <td>267</td>
      <td>44.5</td>
      <td>2.4 km/h/s (0.67 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Strong initial acceleration to match historical predecessor timings.</em></td>
    </tr>
    <tr>
      <td><strong>Stadler KISS (RABe 511)</strong></td>
      <td>160</td>
      <td>44.444</td>
      <td>6 Cars</td>
      <td>2M4T (6-car); 2M2T (4-car)</td>
      <td>4,000</td>
      <td>666.6</td>
      <td>400</td>
      <td>66.6</td>
      <td>297</td>
      <td>49.5</td>
      <td>3.9 km/h/s (1.10 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Extremely high starting torque standard for European double-deck commuter EMUs.</em></td>
    </tr>
    <tr>
      <td><strong>Odakyu 70000 Series (GSE)</strong></td>
      <td>120</td>
      <td>33.333</td>
      <td>7 Cars</td>
      <td>4M3T (7-car)</td>
      <td>3,040</td>
      <td>434.2</td>
      <td>200</td>
      <td>28.5</td>
      <td>256</td>
      <td>36.5</td>
      <td>2.0 km/h/s (0.56 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Smooth acceleration profile for luxury sightseeing service.</em></td>
    </tr>
    <tr>
      <td><strong>Keikyu N1000 Series</strong></td>
      <td>130</td>
      <td>36.111</td>
      <td>8 Cars</td>
      <td>6M2T (8-car); 4M2T (6-car); 4M0T / 2M2T (4-car)</td>
      <td>3,720</td>
      <td>465.0</td>
      <td>300</td>
      <td>37.5</td>
      <td>255</td>
      <td>31.8</td>
      <td>3.5 km/h/s (0.97 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Exceptionally high acceleration, characteristic of Keikyu's aggressive timetable engineering.</em></td>
    </tr>
    <tr>
      <td><strong>Keisei AE (Skyliner)</strong></td>
      <td>160</td>
      <td>44.444</td>
      <td>8 Cars</td>
      <td>6M2T (8-car)</td>
      <td>4,200</td>
      <td>525.0</td>
      <td>180</td>
      <td>22.5</td>
      <td>298</td>
      <td>37.2</td>
      <td>2.0 km/h/s (0.55 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Tuned for sustained 160 km/h top-speed cruising rather than initial pull.</em></td>
    </tr>
    <tr>
      <td><strong>JR East E353 Series</strong></td>
      <td>130</td>
      <td>36.111</td>
      <td>9 Cars</td>
      <td>5M4T (9-car); 2M1T (3-car); 7M5T (12-car)</td>
      <td>2,800</td>
      <td>311.1</td>
      <td>200</td>
      <td>22.2</td>
      <td>333</td>
      <td>37.0</td>
      <td>2.0 km/h/s (0.56 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Modern standard for JR East Limited Express runs on the Chuo Main Line.</em></td>
    </tr>
    <tr>
      <td><strong>JR East E657 Series</strong></td>
      <td>130</td>
      <td>36.111</td>
      <td>10 Cars</td>
      <td>6M4T (10-car)</td>
      <td>3,360</td>
      <td>336.0</td>
      <td>215</td>
      <td>21.5</td>
      <td>385</td>
      <td>38.5</td>
      <td>2.0 km/h/s (0.56 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Standard acceleration for high-capacity commuter/express routes.</em></td>
    </tr>
    <tr>
      <td><strong>TRA EMU900 Series</strong></td>
      <td>130</td>
      <td>36.111</td>
      <td>10 Cars</td>
      <td>4M6T (10-car)</td>
      <td>4,000</td>
      <td>400.0</td>
      <td>350</td>
      <td>35.0</td>
      <td>430</td>
      <td>43.0</td>
      <td>2.8 km/h/s (0.80 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Modern commuter rail acceleration tuned for dense stop-and-go regional service.</em></td>
    </tr>
    <tr>
      <td><strong>TRA EMU3000 Series</strong></td>
      <td>130</td>
      <td>36.111</td>
      <td>12 Cars</td>
      <td>6M6T (12-car)</td>
      <td>4,560</td>
      <td>380.0</td>
      <td>381</td>
      <td>31.7</td>
      <td>545</td>
      <td>45.4</td>
      <td>2.5 km/h/s (0.70 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>High starting torque utilizing 24 independent traction motors.</em></td>
    </tr>
    <tr>
      <td><strong>Shinkansen 100 Series</strong></td>
      <td>220</td>
      <td>61.111</td>
      <td>16 Cars</td>
      <td>12M4T (16-car); 4M2T (6-car); 4M0T (4-car)</td>
      <td>11,040</td>
      <td>690.0</td>
      <td>540</td>
      <td>33.7</td>
      <td>925</td>
      <td>57.8</td>
      <td>1.6 km/h/s (0.44 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Heavy double-deck cars and older DC motors limited the starting pull.</em></td>
    </tr>
    <tr>
      <td><strong>Shinkansen 300 Series</strong></td>
      <td>270</td>
      <td>75.000</td>
      <td>16 Cars</td>
      <td>10M6T (16-car)</td>
      <td>12,000</td>
      <td>750.0</td>
      <td>430</td>
      <td>26.8</td>
      <td>711</td>
      <td>44.4</td>
      <td>1.6 km/h/s (0.44 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>First-generation Nozomi; lower acceleration due to early AC traction motor limitations.</em></td>
    </tr>
    <tr>
      <td><strong>Shinkansen 700 Series</strong></td>
      <td>285</td>
      <td>79.166</td>
      <td>16 Cars</td>
      <td>12M4T (16-car); 6M2T (8-car)</td>
      <td>13,200</td>
      <td>825.0</td>
      <td>460</td>
      <td>28.7</td>
      <td>708</td>
      <td>44.2</td>
      <td>2.0 km/h/s (0.56 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Improved acceleration over earlier Shinkansen models to navigate the Tokaido line.</em></td>
    </tr>
    <tr>
      <td><strong>Shinkansen 500 Series</strong></td>
      <td>300</td>
      <td>83.333</td>
      <td>16 Cars</td>
      <td>16M0T (16-car); 8M0T (8-car)</td>
      <td>18,240</td>
      <td>1,140.0</td>
      <td>480</td>
      <td>30.0</td>
      <td>700</td>
      <td>43.7</td>
      <td>1.9 km/h/s (0.53 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Gearing is entirely dedicated to maintaining 300 km/h rather than starting quickly.</em></td>
    </tr>
    <tr>
      <td><strong>Shinkansen N700 Series</strong></td>
      <td>300</td>
      <td>83.333</td>
      <td>16 Cars</td>
      <td>14M2T (16-car); 8M0T (8-car)</td>
      <td>17,080</td>
      <td>1,067.5</td>
      <td>600</td>
      <td>37.5</td>
      <td>700</td>
      <td>43.7</td>
      <td>2.6 km/h/s (0.72 m/s²)</td>
    </tr>
    <tr>
      <td colspan="12"><em>Very high acceleration for a bullet train, achieved via high motorization ratio (14M2T).</em></td>
    </tr>
  </tbody>
</table>
