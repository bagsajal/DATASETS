# Industrial IoT Alarm Management System

A comprehensive, self-contained HTML application for managing industrial IoT alarms with a modern, professional interface inspired by PrimeNG components.

## 🎯 Features Overview

### 🎛️ Configuration & Management UI
- **Low-code alarm rule creation** with intuitive forms and validation
- **Visual alarm configuration** with dropdowns for device types, conditions, and priorities
- **Import/Export functionality** for configuration backup and restoration
- **Multi-device support** with various sensor types (Temperature, Pressure, Flow, Vibration, etc.)

### 📊 Dashboard & Monitoring
- **Real-time alarm statistics** with color-coded severity levels
- **Live alarm feed** showing recent activity and current status
- **Device status monitoring** with online/offline indicators
- **Interactive navigation** between different modules

### ⚠️ Active Alarm Management
- **Bulk operations** - acknowledge or shelve multiple alarms simultaneously
- **Individual alarm actions** with quick action buttons
- **Advanced filtering** and search capabilities
- **Priority-based visual indicators** for quick assessment

### 📈 Analytics & History
- **Alarm trend analysis** with placeholders ready for chart integration
- **Historical data export** functionality
- **Device-wise alarm distribution** views
- **Performance metrics** including response times and acknowledgment rates

### � Multi-language Support
- **5 languages included**: English, Spanish, German, French, Chinese
- **Dynamic language switching** without page reload
- **Extensible translation system** for additional languages

### 📱 Modern Industrial UI
- **Responsive design** that works on tablets and mobile devices
- **Professional color scheme** suitable for industrial environments
- **Accessibility considerations** with proper contrast ratios
- **Real-time notifications** for user feedback

## � Getting Started

### Quick Start
1. Download the `industrial-iot-alarm-system.html` file
2. Open it in any modern web browser
3. The application is fully functional with simulated data

### System Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- No server or installation required

## 📋 Module Guide

### Dashboard
- Overview of system status and alarm statistics
- Real-time device status monitoring
- Priority-based alarm distribution
- Recent alarm activity feed

### Active Alarms
- View and manage all active alarms
- Filter by priority, status, or search terms
- Bulk acknowledge or shelve operations
- Individual alarm actions

### Configuration
- Create and manage alarm rules
- Configure thresholds and conditions
- Set notification preferences
- Import/export configuration files

### Devices
- Manage connected IoT devices
- Monitor device status and values
- Add new devices with various protocols
- View device-specific information

### Analytics
- Performance metrics and KPIs
- Device-wise alarm analysis
- Response time statistics
- Ready for chart library integration

### History
- Complete alarm history
- Date range filtering
- Export historical data
- Resolution time tracking

## 🔧 Industrial IoT Integration Features

### Supported Protocols
- **Modbus TCP/RTU** - Industrial standard for device communication
- **OPC UA** - Industry 4.0 communication protocol
- **MQTT** - Lightweight messaging for IoT devices
- **HTTP/REST** - Web-based device integration
- **BACnet** - Building automation systems

### Alarm Management
- **Configurable thresholds** with multiple condition types
- **Priority levels**: Critical, High, Medium, Low
- **Multiple notification methods**: Email, SMS, Dashboard, Webhook
- **Acknowledgment and shelving workflows**

### Data Management
- **Local storage** for configuration persistence
- **Export/Import** functionality for data backup
- **Real-time simulation** for demonstration purposes

## 🎨 Customization

### Styling
The application uses CSS custom properties for easy theming:
- Modify color schemes in the CSS variables
- Adjust component sizes and spacing
- Customize the industrial color palette

### Language Support
Add new languages by extending the `translations` object:
```javascript
translations.pt = {
    dashboard: 'Painel',
    alarms: 'Alarmes',
    // ... add more translations
};
```

### Data Integration
Replace the `generateSampleData()` function with real data sources:
- Connect to actual IoT devices
- Integrate with existing databases
- Add real-time WebSocket connections

## 🔒 Security Considerations

For production deployment:
- Implement proper authentication and authorization
- Use HTTPS for secure communication
- Validate all user inputs
- Implement role-based access control
- Add audit logging for all actions

## 📊 Performance Features

- **Efficient rendering** with minimal DOM updates
- **Real-time updates** every 5 seconds (configurable)
- **Responsive design** for various screen sizes
- **Memory-efficient** data handling

## 🛠️ Development Notes

### Architecture
- **Single-page application** with modular design
- **Component-based** rendering system
- **Event-driven** alarm checking and updates
- **Extensible** module system

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## 📈 Future Enhancements

### Chart Integration
The application includes placeholders for charts. Integrate with:
- Chart.js for basic charts
- D3.js for advanced visualizations
- Highcharts for professional dashboards

### Real-time Features
- WebSocket integration for real-time updates
- Push notifications for critical alarms
- Live device status monitoring

### Advanced Analytics
- Machine learning for predictive maintenance
- Trend analysis and forecasting
- Anomaly detection algorithms

## 📞 Support

This is a demonstration application showcasing industrial IoT alarm management capabilities. For production use, consider:

1. **Backend Integration** - Connect to real data sources
2. **Authentication System** - Implement user management
3. **Database Integration** - Persistent data storage
4. **API Development** - REST/GraphQL APIs for device integration
5. **Monitoring & Logging** - Production-grade observability

## 📝 License

This application is provided as a demonstration of industrial IoT alarm management capabilities. Modify and use according to your requirements.

---

**Industrial IoT Alarm Management System** - Professional grade alarm monitoring and management for industrial environments.