
# Sociopedia Frontend

This is the frontend for Sociopedia, a modern social media platform built with React and Vite.

## Features
- User authentication (Auth0, Google OAuth)
- Real-time messaging (WebSocket)
- Friend requests and management
- Posts, comments, and likes
- Responsive design with Tailwind CSS

## Getting Started

### Prerequisites
- Node.js (v16 or higher recommended)
- npm or yarn

### Installation
1. Clone the repository:
	```sh
	git clone https://github.com/LABGIT-1004/Socipedia.git
	cd sociopedia-frontend-main
	```
2. Install dependencies:
	```sh
	npm install
	# or
	yarn install
	```
3. Start the development server:
	```sh
	npm run dev
	# or
	yarn dev
	```

### Build for Production
```sh
npm run build
# or
yarn build
```

### Project Structure
- `src/` - Main source code
- `public/` - Static assets
- `package.json` - Project metadata and scripts
- `README.md` - Project documentation

## Configuration
- Auth0 and Google OAuth settings are in `src/config/`
- Tailwind CSS configuration in `tailwind.config.js`
- Vite configuration in `vite.config.js`

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.
