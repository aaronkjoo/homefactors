# Home Factors Web App (HTML/CSS/JS)
🏠 Home Factors - Property Intelligence Platform
A comprehensive web application that analyzes property addresses and provides detailed insights including safety scores, school ratings, resale potential, walkability, local amenities, and environmental factors.

🌟 Features
Address Analysis: Enter any property address to get comprehensive insights
Multi-Factor Scoring: 6 key property factors with visual scoring system
🛡️ Safety Score - Crime rates and neighborhood security
🎓 School Score - Educational institution quality ratings
📈 Resale Potential - Market trends and investment viability
🚶‍♂️ Walkability - Access to transit and pedestrian-friendly features
🏪 Local Amenities - Shopping, dining, and entertainment proximity
🌱 Environmental - Air quality, green spaces, and pollution levels
Property Valuation: Current market value estimates with trend analysis
Smart Insights: AI-generated recommendations based on property data
Responsive Design: Works seamlessly on desktop, tablet, and mobile devices
Real-time Analysis: Instant property evaluation with loading animations
🚀 Live Demo
Visit the live application: https://aaronkjoo.github.io/homefactors/

🛠️ Technology Stack
Current Frontend:

HTML5
CSS3 (with modern gradients and animations)
Vanilla JavaScript
Responsive grid layout
Planned Backend Integration:

Java
Maven
MongoDB
Spring Boot REST APIs
📦 Installation & Setup
Option 1: Direct File Usage
Download the index.html file
Open it directly in any modern web browser
No additional setup required!
Option 2: Local Web Server
bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Then visit http://localhost:8000
Option 3: GitHub Pages Deployment
Fork this repository
Go to Settings → Pages
Enable Pages from main branch
Your site will be live at https://yourusername.github.io/repository-name
🔮 Future Development Roadmap
Phase 1: Backend Integration
 Set up Java Spring Boot backend
 Create MongoDB data models
 Implement REST API endpoints
 Add address geocoding service
Phase 2: Real Data Sources
 Integrate crime data APIs
 Connect to school rating services
 Add real estate market data
 Implement walkability calculations
 Connect environmental data sources
Phase 3: Advanced Features
 User authentication and saved searches
 Property comparison tool
 Historical trend analysis
 Email alerts for property updates
 Interactive maps integration
 Export reports functionality
🔌 API Integration Guide
Backend Endpoints (Planned)
GET /api/property/analyze?address={address}
GET /api/property/safety/{address}
GET /api/property/schools/{address}
GET /api/property/market-data/{address}
Frontend API Connection
Replace the mock data in analyzeProperty() function:

javascript
async function analyzeProperty() {
    const response = await fetch(`/api/property/analyze?address=${address}`);
    const data = await response.json();
    // Update UI with real data
}
📊 Data Sources (Planned Integration)
Safety Data: Local police department APIs, FBI crime statistics
School Ratings: GreatSchools.org API, state education databases
Property Values: Zillow API, local MLS data
Walkability: Walk Score API, transit agency data
Amenities: Google Places API, Yelp API
Environmental: EPA air quality data, noise pollution metrics
🤝 Contributing
Fork the repository
Create a feature branch (git checkout -b feature/amazing-feature)
Commit your changes (git commit -m 'Add amazing feature')
Push to the branch (git push origin feature/amazing-feature)
Open a Pull Request
📝 Usage Examples
Basic Property Analysis
Enter address: "123 Main Street, San Francisco, CA"
Click "Analyze Property"
View comprehensive property insights
Understanding Scores
85-100: Excellent 🟢
70-84: Good 🟡
50-69: Average 🟠
Below 50: Needs Attention 🔴
🔧 Configuration
Customizing Factor Weights
Modify the scoring algorithm by adjusting weights in the JavaScript:

javascript
const factorWeights = {
    safety: 0.25,
    schools: 0.20,
    resale: 0.20,
    walkability: 0.15,
    amenities: 0.10,
    environmental: 0.10
};
📱 Browser Support
Chrome 80+
Firefox 75+
Safari 13+
Edge 80+
🐛 Known Issues
Currently uses mock data for demonstration
Limited to US addresses in current implementation
Requires active internet connection for full functionality
📄 License
This project is open source and available under the MIT License.

👨‍💻 Author
Created with ❤️ by Aaron Joo

🙏 Acknowledgments
Design inspiration from modern real estate platforms
Color scheme based on contemporary UI/UX best practices
Icons and visual elements designed for accessibility
📞 Support
For questions, issues, or feature requests:

Create an issue in this repository
Email: aaron.k.joo@gmail.com
LinkedIn: https://www.linkedin.com/in/aaronkjoo/
⭐ Star this repository if you find it helpful!

