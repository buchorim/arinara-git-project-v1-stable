# Arinara Git - GitHub Account Management Application

A sophisticated GitHub account management platform with advanced Notion integration, designed to streamline multi-account workflows and enhance developer productivity.

## Features

### Core Functionality
- **Multi-Account GitHub Management**: Seamless switching between multiple GitHub accounts
- **Repository Operations**: Complete CRUD operations (create, read, edit, delete)
- **Advanced File Management**: Create, edit, and delete files with syntax highlighting
- **Activity Logging**: Comprehensive tracking of all user actions
- **Notion Integration**: Real-time synchronization with Notion databases

### Technical Architecture
- **Frontend**: React 18 with TypeScript and Tailwind CSS
- **Backend**: Node.js with Express and PostgreSQL
- **Database**: Persistent storage with Drizzle ORM
- **Authentication**: GitHub OAuth with session management
- **UI Components**: Radix UI and Shadcn/ui components
- **State Management**: TanStack Query for data fetching and caching

### Key Features
- Mobile-first responsive design
- Plugin system for extensibility
- Real-time repository synchronization
- Comprehensive error handling
- Session persistence across server restarts
- Advanced repository trash management
- Bulk operations support

## Installation

1. Clone the repository
```bash
git clone https://github.com/buchorim/arinara-git-project-v1-stable.git
cd arinara-git-project-v1-stable
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
cp .env.example .env
# Add your database URL and other required environment variables
```

4. Run database migrations
```bash
npm run db:push
```

5. Start the development server
```bash
npm run dev
```

## Usage

1. Navigate to the application in your browser
2. Authenticate with your GitHub account
3. Start managing your repositories and files
4. Configure Notion integration for enhanced workflow

## Contributing

We welcome contributions! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Support

For support, please open an issue on GitHub or contact the development team.