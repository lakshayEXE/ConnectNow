# ConnectNow 🌐

ConnectNow is a real-time video chat application that connects users with strangers for one-on-one video calls. It offers distance-based matching, interactive face filters, and robust safety features, making conversations engaging and secure. Built with modern web technologies, ConnectNow prioritizes seamless communication and user experience.

---

## Key Features ✨

- **Real-Time Video Chat**  
  Powered by WebRTC for low-latency, peer-to-peer video streaming.  
- **Smart Matching**  
  Connects users based on geographical proximity using the HTML5 Geolocation API and Haversine formula.  
- **Interactive Face Filters**  
  Apply real-time filters during calls using TensorFlow.js for face detection and Canvas API for rendering.  
- **Safety First**  
  Report or block inappropriate users, with automated moderation flags.  
- **Responsive UI**  
  Built with React.js for a smooth, cross-device experience.

---

## Technology Stack 🛠️

- **Frontend**: React.js, Redux (state management), Styled Components  
- **Backend**: Node.js, Express.js, RESTful APIs  
- **Real-Time Communication**: WebRTC (video), Socket.io (signaling)  
- **Face Filters**: TensorFlow.js, Face-api.js  
- **Geolocation**: HTML5 Geolocation API, Geocode conversion (OpenStreetMap)  
- **Database**: MongoDB (user reports/sessions) *[Add if applicable]*  

---

## Installation & Setup 🚀

### Prerequisites
- Node.js ≥16.x
- npm ≥8.x
- A modern browser (Chrome/Firefox recommended)

### Steps
1. Clone the repository:
   
   git clone https://github.com/lakshayEXE/ConnectNow.git
   cd ConnectNow  # Match the repository's case sensitivity

2. Install dependencies for both client and server:

# Frontend
cd client
npm install

# Backend (in a new terminal)
cd ../server
npm install


3. Start the application:
# Frontend (from /client)
npm start  # Runs on http://localhost:3000

# Backend (from /server)
node index.js  # Runs on http://localhost:5000

