# Graphic Library Builder - Digital Twin Configuration

A comprehensive PrimeNG-based HTML application for building and managing graphic libraries for digital twin configurations in thermal power plant systems.

## Features

### 🔧 **Graphic Upload Panel**
- **Drag & Drop Upload**: Intuitive file upload with visual feedback
- **Supported Formats**: .svg, .png, .jpg, .jpeg
- **Metadata Management**:
  - System Type (Condensate, Feed Water, SH/RH, Steam, Cooling)
  - Tag Category (Pump, Valve, Heat Exchanger, Sensor, Motor, Pipe)
  - Description field for detailed documentation
- **Visual Upload Feedback**: Hover effects and upload notifications

### 📚 **Thumbnail Gallery & Library Management**
- **Grid View**: Responsive thumbnail display with metadata
- **Advanced Filtering**:
  - Filter by System Type
  - Filter by Tag Category
  - Real-time search by description
- **Visual Selection**: Click to select graphics with visual highlighting
- **Drag-to-Canvas**: Direct drag & drop from gallery to canvas

### 🎨 **Canvas Builder (Konva.js Integration)**
- **Interactive Canvas**: Grid-based workspace with snap-to-grid functionality
- **Tool Palette**:
  - Select Tool: Click and select symbols
  - Pan Tool: Navigate large diagrams
  - Zoom In/Out: Scale control for detailed work
  - Reset View: Return to default zoom/position
- **Symbol Management**:
  - Drag symbols from library to canvas
  - Resize and position symbols
  - Visual selection indicators
  - Real-time status updates

### 🔗 **Asset Binding Interface**
- **Dynamic Side Panel**: Appears when symbols are selected
- **Asset Assignment**: Dropdown selection of predefined assets
- **Telemetry Tag Selection**:
  - Temperature (°C)
  - Pressure (Bar)
  - Flow Rate (L/min)
  - Vibration (mm/s)
  - Operational Status
- **Real-time Data Visualization**:
  - Enable/disable real-time updates
  - Visual indicators for bound symbols
  - Color-coded status representation
- **Binding Preview**: Live preview of configuration settings

### ⚡ **Real-time Monitoring Simulation**
- **Color-coded Status**: Symbols change color based on simulated sensor data
- **Pulsing Indicators**: Animated indicators for real-time enabled symbols
- **Temperature Simulation**: 
  - Red: >80°C (High temperature alert)
  - Yellow: 60-80°C (Warning range)
  - Normal: <60°C (Safe operation)

## Usage Instructions

### 1. **Upload Graphics**
1. Select System Type and Tag Category from dropdowns
2. Add description (optional)
3. Either drag & drop files or click "Choose Files"
4. Files will automatically appear in the gallery below

### 2. **Browse Library**
1. Use filter dropdowns to narrow down graphics by system/category
2. Use search box to find graphics by description
3. Click on thumbnails to select them

### 3. **Build Canvas Diagrams**
1. Drag symbols from the gallery to the canvas
2. Use toolbar tools to navigate and manipulate the view
3. Click on symbols to select them (highlighted with blue border)
4. Enable "Snap to Grid" for precise alignment

### 4. **Configure Asset Binding**
1. Select a symbol on the canvas
2. Choose an asset from the dropdown (e.g., "CP-101 - Condensate Pump")
3. Select relevant telemetry tags
4. Enable real-time updates if desired
5. Click "Apply Binding" to save configuration

### 5. **Monitor Real-time Data**
- Bound symbols with real-time enabled will show pulsing green indicators
- Symbol colors will change based on simulated sensor readings
- Use this to visualize system status at a glance

## Technical Features

### **Frontend Technologies**
- **PrimeNG**: Professional UI component library
- **Konva.js**: High-performance 2D canvas library
- **HTML5 Canvas**: Hardware-accelerated graphics
- **CSS Grid**: Responsive layout system
- **JavaScript ES6+**: Modern web standards

### **Canvas Capabilities**
- **Performance**: Optimized for large-scale diagrams
- **Interactivity**: Full mouse/touch support
- **Scalability**: Zoom and pan for detailed work
- **Persistence**: Maintains symbol properties and bindings

### **Data Management**
- **In-memory Storage**: Client-side graphic library management
- **Metadata Preservation**: System/category/description tracking
- **Binding Persistence**: Asset and telemetry tag relationships
- **Real-time Simulation**: Live data visualization

## Sample Assets Included

The application comes pre-loaded with sample graphics:

1. **Pump Symbol** (Condensate System)
   - Green circular design with "PUMP" label
   - Ready for condensate pump asset binding

2. **Valve Symbol** (Feed Water System)
   - Orange triangular design with "VALVE" label
   - Ideal for control valve configurations

3. **Heat Exchanger Symbol** (SH/RH System)
   - Blue rectangular design with crossing lines
   - Perfect for heat transfer equipment

## Browser Compatibility

- **Chrome**: 90+ (Recommended)
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+

## File Structure

```
graphic-library-builder.html    # Main application file
README.md                      # Documentation (this file)
```

## Future Integration Points

This application is designed to integrate with:

- **Google Cloud Platform**: Firestore for canvas storage
- **Pub/Sub**: Real-time telemetry data streams
- **Cloud Functions**: Server-side processing
- **Digital Twin Systems**: Asset and tag management
- **SCADA Integration**: Live plant data feeds

## Getting Started

1. Download the `graphic-library-builder.html` file
2. Open in any modern web browser
3. Start uploading your graphics and building diagrams
4. No installation or server setup required!

## Performance Notes

- **Optimized Rendering**: Konva.js provides smooth canvas operations
- **Memory Efficient**: Client-side storage with minimal footprint
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Fast Filtering**: Real-time search and filter capabilities

---

**Built for Digital Twin Configuration**  
*Enabling visual flow diagram creation for thermal power plant systems*