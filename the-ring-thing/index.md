---
layout: default
title: "The Ring Thing"
---

<style>
  .ring-table { width: auto; border-collapse: collapse; margin: 1rem auto 1.5rem; font-size: 0.95rem; }
  .ring-table th, .ring-table td { padding: 6px 16px; text-align: center; border-bottom: 1px solid #e2e8f0; white-space: nowrap; }
  .ring-table thead tr { background-color: #f4f7fb; border-bottom: 2px solid #cbd5e1; }
  .ring-table tbody tr:nth-child(even) { background-color: #fafafa; }
</style>

<div class="header-container" style="text-align: center; margin-bottom: 2rem;">
  <img src="{{ '/the-ring-thing/TheRingThing_icon.jpg' | relative_url }}" alt="The Ring Thing Logo" style="max-width: 120px; height: auto; border-radius: 20px; margin-bottom: 1rem;">
  <p class="subtitle" style="font-size: 1.1rem; color: #555; margin-top: 0; margin-bottom: 1.2rem;">
    Workshop Calculator for Jewellers & Makers
  </p>

  <div class="nav-buttons" style="display: flex; justify-content: center; gap: 10px; flex-wrap: wrap; margin-bottom: 1.5rem;">
    <a href="{{ '/' | relative_url }}" class="btn-link">PeacheyByte Studios Home</a>
    <a href="{{ '/the-ring-thing/' | relative_url }}" class="btn-link">The Ring Thing Home</a>
    <a href="{{ '/the-ring-thing/privacy' | relative_url }}" class="btn-link">Privacy Policy</a>
  </div>

  <a href="https://play.google.com/store/apps/details?id=com.peacheybyte.theringthing" target="_blank" rel="noopener noreferrer">
    <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" style="height: 60px;">
  </a>
</div>

---

**The Ring Thing** is a practical workshop calculator for jewellers, makers, and hobbyists crafting rings from metal strip, wire, or cutlery. Enter your target ring size and material thickness to calculate the exact blank length needed before cutting and bending.

Everything runs locally on your device—no accounts, no sign-ins, and no internet connection required at the workbench.

---

### Key Features

- **Blank Length Formula:** Calculates required cut length using `L = π × (D + t)` (inner diameter plus material thickness).
- **Fine Workshop Increments:** Supports inner diameters from **12.0 mm to 24.0 mm** and material thicknesses from **0.5 mm to 10.0 mm** in **0.1 mm** steps.
- **Metric & Imperial:** Displays thickness and length values in millimetres, decimal inches, and fractional inches (to the nearest 1/64").
- **International Ring Scales:** Converts between **AU / UK** (BS 6820), **US / CA**, **EU / ISO**, and **JP** (JIS).
- **Offline & Local:** Works completely offline with zero setup.

---

### Ring Size Comparison Table

Reference values below match the exact conversion formulas used in **The Ring Thing** (shown in 0.5 mm inner diameter increments; the app calculates in 0.1 mm steps).

<table class="ring-table">
  <thead>
    <tr>
      <th>Inner Diameter (mm)</th>
      <th>AU / UK</th>
      <th>US / CA</th>
      <th>EU / ISO</th>
      <th>JP</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>12.0</td><td>A</td><td>½</td><td>37.5</td><td>-</td></tr>
    <tr><td>12.5</td><td>B</td><td>1</td><td>39.5</td><td>-</td></tr>
    <tr><td>13.0</td><td>C½</td><td>1¾</td><td>41</td><td>1</td></tr>
    <tr><td>13.5</td><td>D½</td><td>2¼</td><td>42.5</td><td>2.5</td></tr>
    <tr><td>14.0</td><td>F</td><td>3</td><td>44</td><td>4</td></tr>
    <tr><td>14.5</td><td>G</td><td>3½</td><td>45.5</td><td>5.5</td></tr>
    <tr><td>15.0</td><td>H½</td><td>4¼</td><td>47</td><td>7</td></tr>
    <tr><td>15.5</td><td>I½</td><td>4¾</td><td>48.5</td><td>8.5</td></tr>
    <tr><td>16.0</td><td>K</td><td>5½</td><td>50.5</td><td>10</td></tr>
    <tr><td>16.5</td><td>L</td><td>6</td><td>52</td><td>11.5</td></tr>
    <tr><td>17.0</td><td>M½</td><td>6½</td><td>53.5</td><td>13</td></tr>
    <tr><td>17.5</td><td>N½</td><td>7¼</td><td>55</td><td>14.5</td></tr>
    <tr><td>18.0</td><td>P</td><td>7¾</td><td>56.5</td><td>16</td></tr>
    <tr><td>18.5</td><td>Q½</td><td>8½</td><td>58</td><td>17.5</td></tr>
    <tr><td>19.0</td><td>R½</td><td>9</td><td>59.5</td><td>19</td></tr>
    <tr><td>19.5</td><td>T</td><td>9¾</td><td>61.5</td><td>20.5</td></tr>
    <tr><td>20.0</td><td>U</td><td>10¼</td><td>63</td><td>22</td></tr>
    <tr><td>20.5</td><td>V½</td><td>11</td><td>64.5</td><td>23.5</td></tr>
    <tr><td>21.0</td><td>W½</td><td>11½</td><td>66</td><td>25</td></tr>
    <tr><td>21.5</td><td>Y</td><td>12¼</td><td>67.5</td><td>26.5</td></tr>
    <tr><td>22.0</td><td>Z</td><td>12¾</td><td>69</td><td>28</td></tr>
    <tr><td>22.5</td><td>Z+1½</td><td>13¼</td><td>70.5</td><td>29.5</td></tr>
    <tr><td>23.0</td><td>Z+2½</td><td>14</td><td>72.5</td><td>31</td></tr>
    <tr><td>23.5</td><td>Z+4</td><td>14½</td><td>74</td><td>32.5</td></tr>
    <tr><td>24.0</td><td>Z+5</td><td>15¼</td><td>75.5</td><td>34</td></tr>
  </tbody>
</table>

---

<div style="text-align: center; margin-top: 2rem;">
  <a href="https://play.google.com/store/apps/details?id=com.peacheybyte.theringthing" target="_blank" rel="noopener noreferrer">
    <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" style="height: 60px;">
  </a>
</div>
