# Echo - Voice to Tabs

## Getting Started

### Frontend

#### Setup

```
cd frontend
npm install
```

#### Testing

Download the Expo Go app from the [iOS App Store](https://apps.apple.com/us/app/expo-go/id982107779) or [Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=en_US&gl=US&pli=1).

Then run:

```
cd frontend
npm run start
```

You can now scan the QR code in the terminal to test the app on mobile.

### Backend

#### Setup

Make sure you have a virtual environment in place. You will also need `portaudio`` installed to install the package `pyaudio`.

##### Windows

```
cd backend
python3 -m venv venv  # create virtual environment
venv\Scripts\activate  # activate environment
pip install -r requirements.txt  # install necessary packages
```

##### macOS/Linux

```
cd backend
python3 -m venv venv  # create virtual environment
source venv/bin/activate  # activate environment
pip install -r requirements.txt  # install necessary packages
```

#### Testing

```
source venv/bin/activate  # activate environment
python3 app.py  # temporary API launch; can be run with more specific Flask settings
```
