# Football Tracking with YOLOv11

## Overview
This project leverages **YOLOv11** to track football, players, goalkeepers, referees, and classify players from two different teams. The system assigns unique tracking IDs to each player to maintain consistency across frames. 

## Features
- **Football Tracking**: Detects and tracks the ball in real-time.
- **Player Classification**: Differentiates players from two opposing teams.
- **Goalkeeper & Referee Detection**: Identifies and tracks goalkeepers and referees separately.
- **Unique Player ID Assignment**: Ensures consistent tracking of players throughout the video.
- **Real-time Performance**: Optimized for high FPS tracking.
- **Demo Video**: A video demonstration is included to showcase the results.

## Technology Stack
- **YOLOv11**: Object detection and tracking
- **Umap, SigLip & KNN**: Single class interim object tracking 
- **OpenCV**: Video processing
- **Python**: Main programming language
- **NumPy & Pandas**: Data processing


## Usage
```bash
Run google collab notebooks directly but before running setup roboflow api.
```

## Results
The model successfully tracks football, players, goalkeepers, and referees while assigning tracking IDs to players. A sample output video is included in the repository.

## Video Demonstration
[![Demo Video](https://img.icons8.com/fluency/48/play-button-circled.png)](https://drive.google.com/file/d/1qSAoxgSC6eDaEQfcqmmnRVbTQw22UJwk/view?usp=sharing)

> Click the play button above to watch the demo.

## Contributing
Feel free to fork the repository and open pull requests for improvements!

## License
This project is licensed under the MIT License.

## Contact
For queries, reach out via [your email] or create an issue in the repository.

---

### **Keywords**
YOLOv11 football tracking, player classification, multi-object tracking, sports analytics, AI in football, deep learning sports tracking, player detection, real-time object tracking.
