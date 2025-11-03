# Maps for running and walking demo

AI-powered surface condition analysis for running paths and pedestrian routes.

## 📋 How to Use

1. **Set Start Point**: Click "Click Map to Set Start Point" and click anywhere on the map
2. **Set End Point**: Click "Click Map to Set End Point" and click your destination
3. **Route Auto-Plans**: The route automatically calculates when both points are set
4. **View Analysis**:
   - See color-coded route lines showing hardness and slipperiness
   - Review detailed segment analysis in the sidebar
   - Check overall route statistics and air quality

## 🎨 Color Legend

### Hardness Index (Top Line)
- 🟢 Green: Soft (0-13 m/s²) - Grass, dirt trails
- 🟡 Yellow: Medium (13-26 m/s²) - Gravel, asphalt
- 🟠 Orange: Hard (26-33 m/s²) - Brick, concrete
- 🔴 Red: Very Hard (33-40 m/s²) - Dense concrete

### Slipperiness Index (Bottom Line)
- 🟢 Green: Low (0-33%) - Good grip
- 🔵 Blue: Medium (33-66%) - Moderate grip
- 🟣 Purple: High (66-83%) - Slippery
- 🔴 Red: Very High (83-100%) - Very slippery

## 🛠️ Technology

- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Maps**: Google Maps JavaScript API
- **Routing**: Google Directions API (walking mode)
- **Data**: Demo mode with realistic mock data

## 📝 Note

This is a **demo version** using simulated data. For real ML-powered surface analysis, connect to the backend API.

## by Junho Oh and Jaeyoung Oh

