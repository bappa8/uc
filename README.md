# ⚡ Unit Converter Pro

A modern, feature-rich unit converter web application built with vanilla HTML, CSS, and JavaScript. Supports **18 categories** of units with an intuitive dark/light theme interface.

## ✨ Features

- **18 Unit Categories**: Length, Mass/Weight, Area, Volume, Temperature, Time, Digital Storage, Speed, Energy, Power, Pressure, Angle, Force, Torque, Fuel Economy, Frequency, Density, and Electric Current.
- **Dark / Light Mode**: Toggle between dark and light themes with a single click. Preference is persisted via `localStorage`.
- **Responsive Sidebar**: Collapsible sidebar with category search for quick navigation.
- **Real-time Conversion**: Results update instantly as you type.
- **Swap Units**: One-click button to swap the "From" and "To" units.
- **Copy Result**: Copy the converted value to your clipboard with visual feedback.
- **Toast Notifications**: Non-intrusive feedback messages.
- **Mobile-Friendly**: Fully responsive design with hamburger menu on smaller screens.


## 🧮 Supported Conversions

| Category          | Icon | Units                                                              |
|-------------------|------|--------------------------------------------------------------------|
| Length            | 📏   | Nanometers, Micrometers, mm, cm, Meters, Kilometers, Inches, Feet, Yards, Miles, Nautical Miles |
| Mass / Weight     | ⚖️ | Micrograms, Milligrams, Carats, Grams, Kilograms, Metric Tons, Ounces, Pounds, Stones, Grains, Slugs |
| Area              | 📐   | mm², cm², m², km², in², ft², yd², mi², Acres, Hectares            |
| Volume            | 🧊   | ml, Liters, m³, in³, ft³, yd³, Teaspoons, Tablespoons, fl oz, Cups, Pints, Quarts, Gallons, Acre-feet |
| Temperature       | 🌡️  | Celsius, Fahrenheit, Kelvin, Rankine                                |
| Time              | ⏱️  | Nanoseconds, Microseconds, ms, Seconds, Minutes, Hours, Days, Weeks, Months, Years, Decades, Centuries |
| Digital Storage   | 💾   | Bits, Nibbles, Bytes, KB, MB, GB, TB, PB, EB                      |
| Speed             | 🚀   | m/s, km/h, ft/s, mph, Knots, Mach, Speed of Light                 |
| Energy            | ⚡   | Joules, kJ, Calories, kcal, Wh, kWh, eV, BTU, ft-lb, Therms        |
| Power             | 🔌   | Watts, kW, MW, GW, Horsepower, BTU/h, ft-lb/s                      |
| Pressure          | 🎈   | Pa, kPa, MPa, Bar, PSI, Atmospheres, Torr, mmHg, inHg              |
| Angle             | 📐  | Degrees, Radians, Gradians, Milliradians, Arcminutes, Arcseconds   |
| Force             | 💪   | Newtons, kN, Pound-force, Dynes, Kips, Poundals                    |
| Torque            | 🔧   | Nm, kNm, lb-ft, lb-in, kg-m                                        |
| Fuel Economy      | ⛽   | MPG, MPG (Imperial), L/100km, km/L                                 |
| Frequency         | 〰️  | Hz, kHz, MHz, GHz, THz, RPM                                        |
| Density           | 🧪   | kg/m³, g/cm³, g/ml, lb/ft³, lb/in³                                 |
| Electric Current  | ⚡   | nA, µA, mA, A, kA                                                  |

## 🎨 Theme

The application supports both **dark mode** (default) and **light mode**. Toggle between them using the theme button in the top-right corner. The selected theme is saved to `localStorage` and persists across sessions.

## 📱 Responsive Design

- **Desktop**: Full sidebar with search, main content area centered.
- **Mobile / Tablet**: Hamburger menu activates a sliding sidebar overlay.
- Conversion inputs stack vertically on smaller screens.

## 🛠️ Technical Stack

- **HTML5** – Semantic markup
- **CSS3** – Custom properties (variables), Flexbox, responsive media queries
- **Vanilla JavaScript** – No frameworks or libraries
- **localStorage** – Theme persistence

## 📂 Project Structure

```
.
├── index.html   # Single-file application (HTML, CSS, JS)
└── README.md    # This file
```

The entire application is contained in a single `index.html` file for simplicity and portability.

## 📄 License

This project is licensed under the MIT License.

## 🙏 Author

**Bappa Ghosh**
