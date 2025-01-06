# Setup : Custom PWA

### React App
- `npx create-react-app myapp`

### Installation
- `npm install`

### Run the Application
- `npm start`


### Config Errors
- web-vitals error : `npm install web-vitals`

### Setup PWA
- Install Service Worker Packages : `npm install workbox-core workbox-expiration workbox-precaching workbox-routing workbox-strategies`
- Modify `manifest.json` file in public folder
- Enable service worker in `src/index.js`
- Install server package globally : `npm install serve -g`
- Build the project : `npm run build`

### Run the PWA application
- Run the build project using serve package : `serve -s build`
