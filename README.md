## Minimal monorepo MERN stack boilerplate

### Development 
  - Start backend and frontend concurrently ```npm start```
  - Start backend : ```npm run server:dev```
  - Start frontend : ```npm run client:dev```

### Deployment
  - Client\
     [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fdominggo1999%2Fmern-monorepo%2Ftree%2Fmaster%2Fclient&env=VITE_APP_BACKEND_URL)
  - Backend\
    [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/dominggo1999/mern-monorepo)   

### Environment variables
- Client 
  - ```BACKEND_URL=YOUR_BACKEND_URL```

### Stack
  - Client 
    - Vite
    - React 
    - React router dom
    - Twin Macro
    - Styled Components
    - Zustand
    - Immer
  - Backend
    - Express
