# Vizinn – Hyperlocal Marketplace for nearby regions

## 🏡 About the Project

**Vizinn** is an innovative platform that connects users in specific regions for buying, selling, and offering services in a practical and secure way. Our goal is to strengthen the local economy and create a reliable environment for transactions between neighbors and nearby communities.

## 🌟 Open Source Project

**Vizinn** is an open source project that welcomes contributors from all backgrounds. Whether you're a seasoned developer or just starting out, this project offers a fantastic opportunity to:

- 📚 Learn modern technologies in a real-world application
- 👥 Collaborate with a community of developers
- 📝 Build a meaningful addition to your professional portfolio
- 🌐 Make an impact on local communities through technology

We believe in transparent, collaborative development and look forward to your contributions!



## 💼 Market Impact

**Vizinn** is poised to transform local economies and community interactions in significant ways:

### 🌱 Economic Impact
- **Stimulate Local Commerce**: Reduce economic leakage by keeping transactions within communities
- **Empower Small Entrepreneurs**: Lower barriers to entry for micro-entrepreneurs and service providers
- **Reduce Transport Costs**: Minimize logistics expenses by facilitating hyperlocal transactions
- **Create New Market Opportunities**: Enable service providers to reach customers in their immediate vicinity

### 👥 Social Impact
- **Strengthen Community Bonds**: Foster connections between neighbors who might otherwise never interact
- **Increase Safety and Trust**: Create a verified marketplace with accountability through the rating system
- **Reduce Environmental Footprint**: Decrease carbon emissions by encouraging local consumption
- **Bridge Digital Divide**: Provide technological access to local markets for all community members

### 🚀 Innovation Potential
- **Data-Driven Insights**: Generate valuable data about local commerce patterns
- **Scalable to Different Contexts**: Adaptable to various settings from condominiums to university campuses
- **Integration with Local Services**: Potential to connect with local delivery networks and payment systems
- **Community-Led Development**: Features can evolve based on specific community needs

By addressing these market gaps, **Vizinn** represents not just an app but a paradigm shift in how we think about community commerce and neighborhood interactions.



## 🚀 Initial Focus

- Users can define their area of interest, allowing transactions within their condominium or in strategic locations such as universities, shopping centers, and specific neighborhoods.

## 📌 Main Features

- ✅ **Exclusive Marketplace** – Only verified residents or users in nearby regions can post listings and make purchases.
- 🌟 **Featured Listings** – Users can pay to highlight their listings and increase visibility.
- 📍 **Smart Location Filters** – Search for products and services within your condominium or specific areas.
- 🔄 **Exchange and Donation Area** – Encouraging circular economy within communities.
- 🏢 **Building Manager Panel** – Announcements, condominium rules, and event organization.
- ⭐ **Ratings and Reputation** – Feedback system to increase trust between users.
- 🔒 **Security and Moderation** – Reporting inappropriate listings and identity validation.
- 💳 **Integrated Payment Option** – Facilitating secure transactions within the app.
- 📢 **Specific Requests** – Users can publish specific demands, such as "I want lunch at UFRN."

## 📌 MVP Essential Features

### ✅ 1. Registration and Login
🔹 **Objective:** Ensure that only residents or users in the region have access to the platform.

📌 **Features:**
- Registration via email and password or login with Google/Facebook.
- Validation via SMS/email code to ensure identity.
- Residence confirmation via condominium code (optional).
- Basic user profile (name, photo, location).

🔧 **Suggested technologies:** Firebase Authentication, OAuth, Twilio (SMS).

### ✅ 2. Hyperlocal Marketplace
🔹 **Objective:** Allow residents to buy and sell products/services among themselves.

📌 **Features:**
- Create listings with title, description, price, and photos.
- Category selection (e.g., Electronics, Services, Furniture).
- Feed of listings organized by location and category.
- Option to mark an item as "Sold."

🔧 **Suggested technologies:** Firestore, PostgreSQL/MongoDB, Cloudinary.

### ✅ 3. Smart Location Filters
🔹 **Objective:** Allow users to find products and services near them.

📌 **Features:**
- Manual definition of the area of interest.
- Distance filtering (e.g., up to 2km, up to 5km).
- Search only within the user's condominium.

🔧 **Suggested technologies:** Google Maps API, GeoFire.

### ✅ 4. Internal Chat between Users
🔹 **Objective:** Facilitate communication between buyers and sellers directly in the app.

📌 **Features:**
- Private messages between users.
- Push notifications for new messages.
- Read/unread message indication.

🔧 **Suggested technologies:** Firestore (real-time), Firebase Cloud Messaging.

### ✅ 5. Moderation and Security
🔹 **Objective:** Create a safe and reliable environment for users.

📌 **Features:**
- **Reporting System:** Report suspicious listings or users.
- **Basic Rules:** Terms of use visible and accepted during registration.
- **User Blocking:** Active moderation.

🔧 **Suggested technologies:** Firebase Moderation, manual moderation.

## 📢 Subscription Plan in MVP

### ✅ 1. Subscription Model

#### **Free User:**
- Can post up to **3 simultaneous listings**.
- Each listing can contain a maximum of **2 images**.
- Normal access to marketplace and chat.

#### **Premium User (Paid):**
- **Unlimited listings**.
- Can add **more than 2 images** per listing.
- Ability to **highlight listings for free** (X times per month).
- **Priority support** and future exclusive features.

### ✅ 2. Subscription Implementation

📌 **Features:**
- Subscription screen with benefit details.
- Integrated payment system (**Stripe, Mercado Pago, or App Store/Google Play**).
- Plan control in the user's profile.
- Alert when the free user reaches the limit of listings or images.

🔧 **Suggested technologies:**
- **Stripe / Mercado Pago** (recurring payments).
- **Firebase Firestore** for subscription status.
- **Cloud Functions** for permission control.

### ✅ 3. User Experience
- **When trying to create a 4th listing**, a pop-up offers the premium upgrade.
- **When trying to add more than 2 images**, a message alerts about the limitation.
- **"My Listings" page** showing the count of active listings.

## 🛠 Technologies Used

### **Front-End (TypeScript)**
- ⚛ **React Native** – Framework for building native mobile apps.
- 📱 **Expo** – Platform for universal React applications.
- 🚀 **Ignite** – Boilerplate for accelerated development.
- 🎨 **NativeWind (TailwindCSS)** – Efficient and optimized styling for React Native.
- 🔗 **Axios** – Efficient HTTP requests.
- 📲 **React Navigation** – Flexible navigation system.

### **Back-End (Python)**
- ⚡ **FastAPI** – Modern and high-performance framework for APIs.
- 🗄 **SQLAlchemy** – ORM for SQL databases.
- 🔐 **JWT** – Secure authentication.
- 🏦 **SQLite/PostgreSQL** – Scalable and reliable database.

### **Other Technologies**
- 🔔 WebSockets for real-time updates.
- 🚀 CI/CD for automated deployment.

## 👾  Discord

If you wish to support this initiative or be part of the project, contact us:

🔗  **[Link](https://discord.gg/GkfDbTY6xu)**

## Monorepo Structure

This monorepo contains the following packages:

- `packages/frontend-app`: React Native/Expo application
- `packages/backend`: Python API with FastAPI
- `packages/shared-ui`: UI utilities shared between frontend projects

## 🚀 Contributing

We welcome contributions to the Vizinn project! Contributing to this project not only helps us build something amazing, but also provides you with valuable experience in modern development practices and technologies.

### Why Contribute to Vizinn?

- Gain experience with modern tech stack (React Native, FastAPI, etc.)
- Build your portfolio with meaningful open source contributions
- Connect with a community of developers
- Learn collaborative development workflows
- Make a positive impact on local communities

### Contribution Workflow

1. **Fork the repository** to your own GitHub account
2. **Clone your fork** to your local machine:
   ```bash
   git clone https://github.com/YOUR-USERNAME/vizinn-app.git
   cd vizinn
   ```
3. **Set up the project** by following the installation instructions below
4. **Create a branch** for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
5. **Make your changes** and commit them with clear, descriptive messages:
   ```bash
   git commit -m "Add feature: description of your changes"
   ```
6. **Push to your fork**:
   ```bash
   git push origin feature-name
   ```
7. **Open a pull request** to the main repository

### Contribution Guidelines

- Before starting work, check the issues and existing PRs to avoid duplication
- Follow the code style and conventions used in the project
- Write clear commit messages
- Include tests and documentation for your changes
- Keep PRs focused on a single feature or fix

### Becoming a Contributor

Once your PR is accepted:
- You'll be given the "contributor" role on our Discord server
- Your name will be added to our contributors list
- You'll have the opportunity to become a regular maintainer

For a detailed contribution guide, check out our [CONTRIBUTING.md](https://github.com/adamsnows/vizinn/blob/main/CONTRIBUTING.md) file.

## Requirements

- Node.js >= 18.0.0
- pnpm >= 8.0.0
- Python >= 3.13
- Poetry (for managing backend dependencies)

## Installation

```bash
# Install monorepo dependencies
pnpm install

# Install backend dependencies (Python)
cd packages/backend
poetry install
```

## Available Commands

### Development

```bash
# Start React Native app
pnpm dev:app

# Start backend API
pnpm dev:backend

# Start both frontend and backend servers in separate terminals (recommended)
pnpm start

# Start both servers in a single terminal
pnpm start:alt

# Start both servers in a single terminal using the unified script
pnpm start:unified

# Display manual start instructions
pnpm start:manual

# Run all services in parallel
pnpm dev
```

## Starting Servers

There are multiple ways to start the development servers:

```bash
# Recommended: Start frontend and backend in separate terminals (full QR code visibility)
pnpm start

# Alternative: Start both servers in a single terminal
pnpm start:alt

# Alternative with script: Start both in a single terminal
pnpm start:unified

# Start manually with instructions
pnpm start:manual
```

### Build

```bash
# Build React Native app
pnpm build:app

# Build all packages
pnpm build
```

### Linting and Testing

```bash
# Lint React Native app
pnpm lint:app

# Test React Native app
pnpm test:app
```

## Adding New Dependencies

To add dependencies to a specific package:

```bash
# For the React Native app
pnpm --filter ./packages/frontend-app add <package-name>
```

To add development dependencies:

```bash
pnpm --filter <package-name> add -D <dependency-name>
```

## Using Shared Packages

To use shared packages in a frontend project:

```bash
# Add shared-ui package to frontend-app
pnpm --filter ./packages/frontend-app add "shared-ui@workspace:*"
```

## Creating New Shared Packages

Use the available script to easily create new shared packages:

```bash
./create-shared-package.sh package-name "Package description"
```

## Managing the Backend

The backend uses Poetry for Python dependency management:

```bash
# Inside the packages/backend folder
poetry add <package-name>

# Run the FastAPI server
poetry run uvicorn backend.app:app --reload
```

## 📚 Learning Resources

To help you get started with the technologies used in this project, we've compiled a list of useful resources:

### React Native & Expo
- [React Native Official Documentation](https://reactnative.dev/docs/getting-started)
- [Expo Documentation](https://docs.expo.dev/)
- [React Navigation Guide](https://reactnavigation.org/docs/getting-started/)
- [NativeWind (TailwindCSS for React Native)](https://www.nativewind.dev/quick-starts/expo)

### FastAPI & Python
- [FastAPI Official Documentation](https://fastapi.tiangolo.com/)
- [SQLAlchemy Tutorial](https://docs.sqlalchemy.org/en/20/tutorial/index.html)
- [Poetry Documentation](https://python-poetry.org/docs/)
- [Python Type Hints Guide](https://mypy.readthedocs.io/en/stable/cheat_sheet_py3.html)

### Monorepo & pnpm
- [pnpm Workspace Guide](https://pnpm.io/workspaces)
- [Monorepo Best Practices](https://monorepo.tools/)

### Development Workflows
- [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow)
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
- [Pull Request Best Practices](https://github.blog/2015-01-21-how-to-write-the-perfect-pull-request/)

## 🚀 Vizinn App – Transforming Neighborhoods, Connecting People!
