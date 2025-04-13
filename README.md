# EcoBin - Smart Waste Management System

EcoBin is a smart waste management system designed to make waste collection efficient, sustainable, and rewarding. By classifying waste into organic, recyclable, and hazardous categories, users can earn rewards while contributing to a cleaner environment. Our IoT-enabled smart dustbins track fill levels, and a smart routing system optimizes waste collection. EcoBin won *first runner-up* in our first offline hackathon!

> **Note:** This is a **group project** developed by two members — **Harshvardhan Mishra** and **Ayan Khan**.

This repository contains the Minimum Viable Product (MVP) for EcoBin, featuring a user-friendly web interface with community and admin dashboards.

**[Live Demo](https://LIVE_URL_HERE)**

---

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features
- **Waste Classification**: Users classify waste into organic, recyclable, and hazardous categories.
- **Smart Dustbins**: IoT-based dustbins track fill levels and send notifications when full.
- **Smart Routing**: Optimized waste collection routes using Open Route Service (ORS).
- **Community Dashboard**:
  - View total points, reports, and waste cleaned.
  - Raise reports for landfills or garbage issues.
  - Track environmental impact and leaderboard rankings.
  - Redeem rewards using earned points.
  - Participate in community tasks.
- **Admin Dashboard**:
  - Monitor dustbins, vehicles, and drivers.
  - Visualize and assign optimized routes.
  - Manage community reports and contributions.
- **Landing Page**: Informative pages for Home, About, Learn, and Community.

---

## Tech Stack
- **Frontend**: [Next.js](https://nextjs.org/) - React framework for building the web interface.
- **Backend/Database**: [Supabase](https://supabase.com/) - Open-source Firebase alternative for authentication and real-time database.
- **Routing**: [Open Route Service (ORS)](https://openrouteservice.org/) - Free API for smart route optimization.
- **Deployment**: Hosted on [https://LIVE_URL_HERE](https://LIVE_URL_HERE)

---

## Installation

Follow these steps to set up EcoBin locally:

1. **Clone the repository**:

```bash
git clone https://github.com/your-username/ecobin.git
cd ecobin
```

2. **Install dependencies**:

```bash
npm install
```

3. **Set up environment variables**:

Create a `.env.local` file in the root directory and add the following:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
NEXT_PUBLIC_ORS_API_KEY=your_ors_api_key
```

- Get `SUPABASE_URL` and `SUPABASE_ANON_KEY` from your Supabase project dashboard.
- Get `ORS_API_KEY` from Open Route Service (free tier available).

4. **Run the development server**:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Usage

- **Community Users**:
  - Sign up via the Community tab.
  - Access the dashboard to raise reports, track points, redeem rewards, and join community tasks.

- **Admins**:
  - Log in to the Admin Dashboard to manage dustbins, vehicles, drivers, routes, and community contributions.

- Explore the landing page for more info on waste management and EcoBin’s mission.

---

## Contributing

We welcome contributions to make EcoBin even better! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

Please ensure your code follows our coding standards and includes relevant tests.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions or feedback, reach out to us:

- Email: [your-email@example.com](mailto:your-email@example.com)
- GitHub Issues: [Create an issue](https://github.com/your-username/ecobin/issues)

Let’s make waste management smarter and greener together! 🌱

