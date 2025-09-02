# Hardware Integration Checklist
## Date: September 2, 2025

### Pre-Installation
- [ ] Verify all hardware components received
- [ ] Prepare workspace with adequate lighting
- [ ] Gather all necessary tools (screwdrivers, cables, etc.)
- [ ] Ensure power supply meets requirements (12V/4A for Jetson)

### Camera Mounting
- [ ] Mount IMX519 cameras on robot chassis
- [ ] Ensure cameras are parallel and aligned
- [ ] Secure mounting to prevent vibration
- [ ] Check baseline distance between cameras (recommended: 6-12 cm)
- [ ] Verify cameras are at same height level

### Cabling
- [ ] Connect MIPI CSI-2 cables to Jetson
- [ ] Ensure cables are properly seated (click sound)
- [ ] Route cables to avoid pinch points
- [ ] Secure cables with zip ties
- [ ] Connect power to cameras (if required)

### Power Requirements
- [ ] Connect Jetson power supply
- [ ] Verify power LED lights up
- [ ] Check for adequate power (use multimeter if available)
- [ ] Ensure no power shortages with multiple components

### Video Transmission Setup
- [ ] Connect HDMI output from Jetson to AV converter
- [ ] Connect AV converter to video transmitter
- [ ] Connect antenna to transmitter
- [ ] Power on video transmitter
- [ ] Verify transmitter LED indicators

### Testing
- [ ] Power on the entire system
- [ ] Check Jetson boot sequence (monitor connected)
- [ ] Verify camera detection in system
- [ ] Test video transmission to monitor
- [ ] Check for video sync issues
- [ ] Verify latency meets requirements (<100ms)

### Calibration Preparation
- [ ] Print chessboard pattern (A4, 9x6, 30mm)
- [ ] Prepare flat surface for calibration
- [ ] Ensure good lighting conditions
- [ ] Plan calibration image capture (20+ images)