# Setup Meshery on docker labs

Steps:
1. Open `https://labs.play-with-docker.com/`
2. Login to the labs
3. Create an instance
4. Run the following:
```bash
# Clone the repositor
git clone https://github.com/utkarsh-pro/meshery-kind-alpine-setup.git

cd meshery-kind-alpine-setup

# Change the permissions
chmod +x setup.sh

# Start the script
./setup.sh
```

5. If you get an error in the browser "Aw Snap!" then please click on "reload", the rest of the process should be smooth.
6. That's it! Now Click on "Open Port" and type in port `9081` to access meshery dashboard