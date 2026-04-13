# IP Visualizer and Analyzer

A comprehensive web-based tool for analyzing and visualizing IP addresses, subnetting, and network allocation. Built as a B.Tech Computer Networks Module 4 Project.

## 📋 Features

### 1. **IP Address Analysis**
- Analyze any IP address with optional subnet mask
- Display complete network information including:
  - IP Classification (Class A, B, C, D, E)
  - Network Address and Broadcast Address
  - Host Range and Total Hosts
  - First and Last Usable IP
  - Subnet Mask details
- Binary mode toggle for detailed binary representation
- Quick test buttons for demo IPs (Class A, B, C, D, Loopback, Subnetted)

### 2. **Network Division & Subnet Allocation**
Three allocation methods:
- **Divide Equally**: Split network into equal-sized subnets
- **VLSM (Variable Length Subnet Mask)**: Unequal subnet allocation
- **Hierarchical Division**: Divide by customer groups

### 3. **ISP Block Allocation (Type 4)**
- Simulate ISP block distribution to multiple customer groups
- Calculate required prefix for each customer group
- Track remaining available addresses
- Professional ISP allocation planning tool

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server installation required

### Usage
1. Open `index.html` in your web browser
2. Choose from three main analysis tools:
   - **Input Details**: Enter IP and subnet mask
   - **Network Division**: Configure allocation method and number of networks
   - **ISP Block Allocation**: Design ISP customer blocks

### Quick Start Examples
- Use "Class A" button for `10.0.0.0` example
- Use "Class B" button for `172.16.0.0` example
- Use "Class C" button for `192.168.1.0` example
- Use "Subnetted" button for `172.16.10.0/26` example

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, Tailwind CSS
- **Scripting**: Vanilla JavaScript
- **No Backend Required**: Fully client-side processing

## 📊 Key Capabilities

### IP Classification
- Classful addressing analysis
- Subnet mask calculations
- Binary representation toggle

### Network Management
- Multiple subnet allocation strategies
- VLSM support for flexible subnet sizing
- Hierarchical network organization
- Remaining address tracking

### Educational Value
- Learn tab with detailed explanations
- Help section with usage guidance
- Developer credits and team information
- Visual interface for network concepts

## 📝 Supported Features

✅ IPv4 address analysis  
✅ CIDR notation support (/8 to /32)  
✅ Binary mode visualization  
✅ Multiple allocation methods  
✅ ISP block planning  
✅ Responsive design  
✅ Print-friendly reports  

## 👥 Team

- **Developed by**: Computer Networks Project Team
- Submission: B.Tech Module 4 Project

## 📄 License

Educational use

## 🤝 Contributing

This is an educational project. For modifications or improvements, please contact the development team.

## 📞 Support

For help using the tool:
1. Click the "❓ Help" button in the application
2. Check the "🎓 Learn" section for detailed explanations
3. Use quick test buttons to understand features

## 🔗 Links

- **GitHub Repository**: [IP-Visualizer-Analyzer](https://github.com/mr-reyansh/IP-VISUALIZER-ANALYZER)
- **Live Demo**: Open `index.html` in a web browser

---

**Note**: This tool is designed for educational purposes and network analysis learning. Always verify results with official network tools before production use.
