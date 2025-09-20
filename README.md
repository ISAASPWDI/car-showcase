# Car Showcase

A modern car showcase website built with Next.js that displays various car types with comprehensive information, advanced filtering, and pagination capabilities.

## Tech Stack

- **Next.js** - React framework with server-side rendering
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework

## How the App Works

### Core Functionality

The Car Showcase app fetches car data from a third-party API and presents it in an intuitive, searchable interface. The application leverages Next.js server-side rendering for optimal performance and SEO.

### Key Features

**Car Display**
- Displays a grid of car cards with essential information (make, model, year, fuel type)
- Each car card shows an image, pricing, and key specifications
- Responsive design that adapts to different screen sizes

**Search & Filtering**
- Search cars by manufacturer and model
- Filter by multiple criteria:
  - Manufacturer (Acura, BMW, Tesla, etc.)
  - Year of production (2015-2023)
  - Fuel type (Gas, Electricity)
- Real-time filtering updates the displayed results

**Car Details**
- Click on any car card to view detailed information
- Modal popup displays comprehensive car specifications
- Additional images and detailed descriptions

**Pagination**
- Navigate through large datasets efficiently
- Load more cars as needed without overwhelming the interface
- Smooth transitions between pages

### Data Sources

- **Car Information**: Retrieved from RapidAPI's Cars API
- **Car Images**: Generated using Imagin Cars API for consistent, high-quality vehicle images

### Performance Features

- **Server-Side Rendering**: Initial page loads are fast and SEO-optimized
- **Optimized Metadata**: Each car listing includes proper meta tags for search engines
- **TypeScript Integration**: Enhanced code quality and development experience
- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices

### User Experience

1. **Landing Page**: Users see an attractive hero section with featured cars
2. **Browse Cars**: Scroll through the car showcase with filtering options
3. **Search**: Use the search bar to find specific manufacturers or models
4. **Filter**: Apply filters to narrow down results by year, fuel type, or manufacturer
5. **View Details**: Click on any car to see detailed specifications and additional information
6. **Navigate**: Use pagination to explore more vehicles

## Quick Start

### Prerequisites

- Node.js
- npm or yarn
- Git

### Installation

```bash
# Clone the repository
git clone [repository-url]
cd project_next13_car_showcase

# Install dependencies
npm install

# Set up environment variables
# Create .env file with:
NEXT_PUBLIC_RAPID_API_KEY=your_rapid_api_key
NEXT_PUBLIC_IMAGIN_API_KEY=your_imagin_api_key

# Run the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the application.

## Environment Variables

- `NEXT_PUBLIC_RAPID_API_KEY`: API key for accessing car data from RapidAPI
- `NEXT_PUBLIC_IMAGIN_API_KEY`: API key for generating car images from Imagin Cars

The app provides a seamless experience for users to explore, search, and learn about different vehicles with modern web technologies and optimized performance.