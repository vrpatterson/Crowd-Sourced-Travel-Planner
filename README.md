# Travel-Planner
Crowd-Sourced Travel Planner created for OSU Capstone

# Backend

The backend is uses the Flask framework. The code can be found in the `\backend` directory.

Railyway.app is the host for the production backend. Initial Flask boilerplate template from Railway.app was used for intial code to ensure compatibility. 

## Running backend locally


To run backend locally:
### Installation of backend
0. Have Python 3 and Node version 16 or above installed
1. Open `backend` directory in a terminal
2. Set up a python virtual environment with: `python -m venv venv` [for MacOS: python -m venv env]
3. Activate the virtual environment with: `.\venv\Scripts\activate` [for MacOS: source ./env/bin/activate]
4. Install requirments with: `python -m pip install -r requirements.txt`
5. Deactivate python environment for railway setup with commnad: `deactivate`
6. Install railway cli tool with : `npm i -g @railway/cli`
7. Log into railway with `railway login`

### Running backend
0. After installation
1. Open `backend` directory in a terminal
2. Activate the virtual environment with: `.\venv\Scripts\activate` [for MacOS: source ./env/bin/activate]
3. Run the main entry point with: `railway run python main.py`
4. Go to http://localhost:5000/ to see greeting from Travel Planner backend

# Frontend

The frontend uses Next.js. The code can be found int he `.\frontend` directory.

The frontend will be hosted on Vercel.

To run frontend locally:
### Installation of frontend
0. Have Node version 16 or above installed
1. Open `frontend` directory in a terminal
2. Set up environment with: `npm install`
3. Run `npm run dev`
4. Go to http://localhost:3000/ 



# Dev Plan

## Routes
- Home
- Login
- Sign Up
- Trips
- Explore
- Search
- Experience
- Create Experience Form


# Sources
## Big thanks to :
- The Net Ninja Next.JS playlist @ https://www.youtube.com/playlist?list=PL4cUxeGkcC9g9gP2onazU5-2M-AzA8eBw
  -  Referenced for page routing, and Layout.js/Header.js/Footer.js structure
