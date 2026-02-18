# Scheme Finder App

A modern web application that helps users find government and private sector schemes they're eligible for based on their personal and financial profile.

## Features

- **Interactive Form**: Users can input their age, income, state, occupation, gender, category, and disability status
- **Smart Matching Engine**: Compares user profile against eligibility criteria for 20+ schemes
- **Dual Sector Coverage**: Includes both government and private sector schemes
- **Filter & Browse**: Filter schemes by sector and expand details
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## Tech Stack

- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS
- **Development**: ESLint, TypeScript strict mode

## Getting Started

### Prerequisites

- Node.js 18+ and npm

### Installation

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure

```
src/
├── app/              # Next.js app router pages
│   ├── layout.tsx    # Root layout with header/footer
│   ├── page.tsx      # Main page
│   └── globals.css   # Global styles
├── components/       # React components
│   ├── SchemeForm.tsx     # User input form
│   └── SchemeResults.tsx  # Results display
├── data/             # Static data
│   └── schemes.ts    # Scheme database
└── lib/              # Utilities
    └── schemeMatchingEngine.ts  # Eligibility logic
```

## Available Schemes

The app includes 20+ schemes:

### Government Schemes
- PM Kisan Samman Nidhi
- Pradhan Mantri Ujjwala Yojana
- Ayushman Bharat - PMJAY
- Pradhan Mantri MUDRA Yojana
- MGNREGA
- Atal Pension Yojana (APY)
- And more...

### Private Schemes
- Infosys Foundation Scholarship
- Tata Scholarships
- Reliance Industries Scholarship
- Cisco Networking Academy
- Microsoft AI for Good Lab
- Amazon Future Engineer Scholarship
- And more...

## Build

To create a production build:

```bash
npm run build
npm start
```

## Development

- Run ESLint:
```bash
npm run lint
```

## Future Enhancements

- Add API backend for dynamic scheme management
- User authentication and saved searches
- Email notifications for new schemes
- Scheme application tracking
- Admin dashboard for scheme management
- Multi-language support
- More detailed eligibility criteria

## License

This project is open source and available under the MIT License.
