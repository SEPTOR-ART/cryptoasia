# NovaCrypto Exchange

A modern cryptocurrency portfolio tracker and exchange platform built with Next.js 13+ (App Router).

## Features

- User authentication (login/signup)
- Portfolio tracking dashboard
- Cryptocurrency purchase requests
- Support center with FAQ
- Responsive design with dark theme

## Project Structure

```
client/
├── app/                 # Next.js 13+ App Router
│   ├── api/             # API routes
│   ├── dashboard/       # Dashboard page
│   ├── login/           # Login page
│   ├── request-purchase/ # Purchase request page
│   ├── signup/          # Signup page
│   ├── support/         # Support page
│   ├── layout.tsx       # Root layout
│   └── page.tsx         # Home page
├── components/          # Reusable components
├── lib/                 # Utility functions
├── public/              # Static assets
└── package.json         # Project dependencies
```

## Getting Started

1. Install dependencies:
   ```bash
   cd client
   npm install
   ```

2. Run the development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

## Technologies Used

- [Next.js 13+](https://nextjs.org/) with App Router
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Icons](https://react-icons.github.io/react-icons/)

## Pages

- `/` - Home page
- `/login` - User login
- `/signup` - User registration
- `/dashboard` - Portfolio dashboard
- `/request-purchase` - Cryptocurrency purchase requests
- `/support` - Support center

## API Routes

- `/api/crypto` - Cryptocurrency data endpoints

## Development

To start the development server:

```bash
cd client
npm run dev
```

The application will be available at http://localhost:3000

## Building for Production

To create a production build:

```bash
cd client
npm run build
```

To start the production server:

```bash
cd client
npm start
```

## Deployment

### GitHub Repository Setup

1. Create a new repository on GitHub.com (don't initialize with a README)
2. Copy the repository URL
3. Run these commands in your terminal:
   ```bash
   cd client
   git remote add origin YOUR_GITHUB_REPO_URL
   git branch -M main
   git push -u origin main
   ```

### Deploy to Netlify

1. Go to [netlify.com](https://netlify.com) and sign up or log in
2. Click "New site from Git"
3. Connect to your GitHub account
4. Select your repository
5. Configure the deployment settings:
   - Build command: `npm run build`
   - Publish directory: `.next`
6. Click "Deploy site"

Netlify will automatically deploy your site and provide you with a URL.

### Deploy to Render

1. Go to [render.com](https://render.com) and sign up or log in
2. Click "New Web Service"
3. Connect to your GitHub repository
4. Configure the service:
   - Name: novacrypto-exchange
   - Environment: Node
   - Build command: `npm run build`
   - Start command: `npm start`
5. Click "Create Web Service"

Render will automatically deploy your site and provide you with a URL.

## License

This project is proprietary and confidential. All rights reserved.