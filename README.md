# GPS-Based Automated Attendance System  

## Overview  
This project is a mobile application designed for faculty members to manage attendance efficiently using GPS geofencing, facial recognition, and deep learning techniques. It ensures secure, accurate, and convenient attendance tracking by automating the process when faculty members enter or leave the campus.  

![Application Phase Flow Diagram](images/application_phase_flow_diagram.png)  

## Features  
- **Geofencing**: Determines faculty presence within the campus area using GPS.  
- **Facial Recognition**: Employs the FaceNet model for robust and efficient facial verification.  
- **Real-Time Updates**: Logs session IDs, GPS coordinates, and timestamps for accurate attendance records.  
- **Enhanced Security**: Verifies faculty identity with a unique ID and location-based confirmation.  

![Geofence Google Map](images/geofence_google_map_image.png)  

## Tools and Technologies  
- **GPS**: Geofencing for location verification.  
- **FaceNet**: High-dimensional facial recognition model developed by Google.  
- **TensorFlow Lite**: Facilitates on-device inference for facial recognition models.  
- **EfficientNet-B7**: Selected for its optimal performance in facial recognition tasks.  

![Why FaceNet Statistics](images/why_facenet_statistics.png)  

## Development Progress  
1. Unique ID verification (one-time setup).  
2. Location verification using GPS.  
3. Facial verification using the FaceNet model.  
4. Logging session data:  
   - Session ID  
   - GPS coordinates  
   - Timestamp  

![Android User Phase 1](images/android_user_phase_1.png)  
![Android User Phase 2](images/android_user_phase_2.png)  

## Motivation  
The project aims to modernize traditional attendance tracking in educational institutions by combining location-based services, facial recognition, and deep learning techniques. This solution reduces administrative burdens and fosters a technologically advanced learning environment.  

## Application Download  
[Download the Application](#)  

## Team  
- **Sk Abdul Subhan** - 211FA18096  
- **Sk Siraj** - 211FA18101  
- **K.N.S. Sesha Kumar** - 211FA18112  

## References  
- FaceNet by Google  
- TensorFlow Lite  
- EfficientNet-B7  
