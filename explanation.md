# Choice of Objects Used

This project utilizes deployment, services, config maps, and persistent volume. The files are separated into the backend and the client DIR for efficiency.

The services for both client and backend are set to ensure that they are exposed externally.

# Storage solutions

This project uses a local Mongo DB connection and a persistent volume size of 5Gi. This volume is linked to the backend deployment since they are interdependent. The config map stores the db URL to the local Mongo DB.

# Git workflow

The Yolo app is cloned and dockerized. With the images pushed to the docker hub, the deployment files call the already stored images. The

