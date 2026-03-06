# BraidTrack 360: Operator Industrial Hub

![BraidTrack 360 Banner](https://picsum.photos/seed/industrial/1200/400)

**BraidTrack 360** is a high-end SaaS industrial monitoring platform designed for smart factory management. It features real-time analytics, machine health tracking, and operator performance metrics wrapped in a futuristic, immersive UI.

## 🚀 Features

- **Role-Based Access Control**: Distinct dashboards for **Operators** and **Admins**.
- **Real-Time Monitoring**: Live tracking of machine status (Running, Off, Issue, Service).
- **Interactive Dashboards**:
  - **Operator View**: Focus on assigned machines, issue reporting, and shift summaries.
  - **Admin View**: Global factory overview, revenue forecasting, machine inventory management, and workforce administration.
- **Data Visualization**: Beautiful, animated charts for production output, revenue, and downtime analysis using `recharts`.
- **Immersive UI/UX**:
  - Glassmorphism design system.
  - Particle effects and 3D-style animations.
  - Fully responsive layout.
- **Issue Management**: Comprehensive system for reporting, tracking, and resolving machine faults.

## 🛠️ Tech Stack

- **Frontend Framework**: [React 19](https://react.dev/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Animations**: [Motion](https://motion.dev/) (formerly Framer Motion)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Charts**: [Recharts](https://recharts.org/)

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/braidtrack-360.git
   cd braidtrack-360
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## 🖥️ Usage

### Login Credentials (Demo)

The application includes a demo login screen with pre-filled credentials for testing:

- **Admin**:
  - Username: `admin`
  - Password: `password`
- **Operator**:
  - Username: `operator01`
  - Password: `password`

### Admin Functions
- **Add Machine**: Navigate to the "Machines" tab and click "Add New Machine".
- **Manage Operators**: Navigate to the "Operators" tab to add or view operator profiles.
- **Configure Machines**: Click "Configure" on any machine card to update its status or production metrics.

## 🚀 Deployment

### Netlify

This project is configured for easy deployment on Netlify.

1. **Push to GitHub**: Ensure your project is pushed to a GitHub repository.
2. **New Site from Git**: Log in to Netlify and select "New site from Git".
3. **Connect Repository**: Choose your repository.
4. **Build Settings**: Netlify should automatically detect the settings from `netlify.toml`:
   - **Build command**: `npm run build`
   - **Publish directory**: `dist`
5. **Deploy**: Click "Deploy site".

The included `netlify.toml` file handles the configuration for you, including SPA redirect rules.

## 📄 License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.

---

*Built with ❤️ for the future of industrial automation.*
