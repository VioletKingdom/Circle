# Circle

Circle (Frontend): a Cloud and React based Social Network

- Designed and implemented a geo-based social network web application with React JS.

- Implemented features for users to create and browse posts and support search nearby posts (Ant Design,
GeoLocation API and Google Map API.)

- Improved the authentication using token based registration/login/logout flow with React Router v4 and
server-side user authentication with JWT.


Circle (Backend): a Geo-index and Image Recognition based Social Network
- Launched a scalable web service in Go to handle posts and deployed to Google Cloud (Google Kubernetes Engine) for better scaling.
- Used ElasticSearch (GCE) to provide geo-location based search functions such that users can search nearby posts within a distance (e.g. 200km)
- Utilized Google Dataflow to dump daily posts to a BigQuery table and perform offline analysis (keyword based spam detection)
- Used Google Cloud ML API and TensorFlow to train a face detection model and integrate with the Go service.

These are the pictures show how the webpages look like.
You can register, log in and post what you want to post.

![alt text](https://i.ibb.co/10xCKyD/Capture12.jpg)

![alt text](https://i.ibb.co/GHhsbxm/Capture8.jpg)

![alt text](https://i.ibb.co/mC2txPj/Capture7.jpg)

![alt text](https://i.ibb.co/PcpdhL3/Capture9.jpg)


For the images posts, the webpage can distinguish people faces.

![alt text](https://i.ibb.co/f8S76Qj/Capture10.jpg)

![alt text](https://i.ibb.co/VWZGN4Z/Capture11.jpg)
