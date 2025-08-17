# React Leaflet Map Application

A modern Next.js application showcasing interactive maps using React Leaflet with geocoding and search capabilities.

## 🗺️ Project Overview

This project demonstrates how to integrate React Leaflet into a Next.js application to create interactive, feature-rich maps. It includes geocoding, search functionality, and modern UI components.

## 🚀 Technologies Used

### Core Framework

- **Next.js 15.4.6** - React framework with App Router
- **React 19.1.0** - Latest React with concurrent features
- **TypeScript** - Type-safe JavaScript development

### Mapping & Geospatial

- **React Leaflet 5.0.0** - React components for Leaflet maps
- **Leaflet 1.9.4** - Open-source JavaScript library for interactive maps
- **Leaflet Geosearch 4.2.0** - Geocoding and search functionality
- **Leaflet Default Icon Compatibility 0.1.2** - Fixes icon compatibility issues

### Styling & UI

- **Tailwind CSS 4** - Utility-first CSS framework
- **PostCSS** - CSS processing

### Development Tools

- **ESLint** - Code linting and quality
- **TypeScript** - Static type checking
- **Git** - Version control

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/mohd-khan09/React-leaflet.git
   cd React-leaflet
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🛠️ Available Scripts

- `npm run dev` - Start development server with Turbopack
- `npm run build` - Build the application for production
- `npm run start` - Start the production server
- `npm run lint` - Run ESLint for code quality

## 🗂️ Project Structure

```
react-leaflet/
├── src/
│   └── app/
│       ├── components/     # React components
│       ├── globals.css     # Global styles
│       ├── layout.tsx      # Root layout
│       └── page.tsx        # Home page
├── public/                 # Static assets
├── package.json           # Dependencies and scripts
├── tsconfig.json          # TypeScript configuration
├── tailwind.config.js     # Tailwind CSS configuration
└── README.md              # This file
```

## 🗺️ Features

- **Interactive Maps** - Full-featured Leaflet maps with React components
- **Geocoding** - Search and locate places on the map
- **Modern UI** - Clean, responsive design with Tailwind CSS
- **TypeScript** - Type-safe development experience
- **Performance** - Optimized with Next.js and Turbopack

## 🔧 Configuration

### Leaflet Configuration

The project includes proper Leaflet configuration with:

- Default icon compatibility fixes
- Geosearch integration
- TypeScript support

### Next.js Configuration

- App Router enabled
- TypeScript support
- Tailwind CSS integration
- ESLint configuration

## 📚 Key Dependencies Explained

### React Leaflet

Provides React components that wrap Leaflet functionality, making it easy to create interactive maps in React applications.

### Leaflet Geosearch

Adds geocoding capabilities, allowing users to search for locations and automatically place markers on the map.

### Leaflet Default Icon Compatibility

Fixes common issues with Leaflet icons in modern bundlers and frameworks.

## 🚀 Getting Started with Maps

To create a basic map component:

```tsx
import { MapContainer, TileLayer, Marker, Popup } from "react-leaflet";
import "leaflet/dist/leaflet.css";

function MyMap() {
  return (
    <MapContainer
      center={[51.505, -0.09]}
      zoom={13}
      style={{ height: "400px" }}
    >
      <TileLayer
        url="https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png"
        attribution='&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
      />
      <Marker position={[51.505, -0.09]}>
        <Popup>
          A pretty CSS3 popup. <br /> Easily customizable.
        </Popup>
      </Marker>
    </MapContainer>
  );
}
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Useful Links

- [React Leaflet Documentation](https://react-leaflet.js.org/)
- [Leaflet Documentation](https://leafletjs.com/)
- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

## 📞 Support

If you have any questions or need help, please open an issue on GitHub or contact the maintainer.

---

**Happy Mapping! 🗺️**
