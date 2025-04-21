# T-Shirt Designer by ArtCraft Sports Apparel

A modern, interactive web application for designing custom t-shirts. Built with React, TypeScript, and Firebase.

## Features

- Interactive t-shirt design interface
- Real-time preview with SVG animations
- Multiple style options (gender, sleeve type, collar style)
- Fabric blend selection
- Color customization
- Image upload and placement
- User authentication
- Project saving and sharing
- Admin notifications

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- Firebase account
- Modern web browser

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/tshirt-designer.git
cd tshirt-designer
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with your Firebase configuration:
```
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```

4. Start the development server:
```bash
npm start
```

The application will be available at `http://localhost:3000`

## Project Structure

```
src/
  ├── components/         # React components
  │   ├── steps/         # Step components for the design process
  │   └── ...
  ├── services/          # API and service functions
  ├── types/             # TypeScript type definitions
  ├── hooks/             # Custom React hooks
  ├── context/           # React context providers
  ├── utils/             # Utility functions
  └── assets/            # Static assets
```

## Features

### Design Options
- Gender selection (Adult, Female, Children)
- Sleeve type (Short sleeve, Long sleeve, Sweatshirt, Jacket)
- Collar style (Round neck, V-neck, Tank top)
- Fabric blend (100% Cotton, 60/40 Cotton/Polyester, Triblend)
- Color selection with custom color picker
- Image upload and placement

### User Features
- User authentication
- Project saving
- Design sharing
- Download designs
- Purchase integration

### Admin Features
- New user notifications
- Project submission notifications
- Live chat support

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

ArtCraft Sports Apparel - artdept@artcraftsports.com

Project Link: [https://github.com/yourusername/tshirt-designer](https://github.com/yourusername/tshirt-designer)
