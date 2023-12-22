## Steps to run Code

- Clone the repository
```
git clone https://github.com/tahmid-sarker-mahi/Detection-of-football-players-and-the-ball.git
```
- Goto the cloned folder.
```
cd Detection-of-football-players-and-the-ball
```
- Install the dependencies
```
pip install -e '.[dev]'
```

- Setting the Directory.
```
cd ultralytics/yolo/v8/detect
```
- Unzip the deep_sort_pytorch folder into the yolo/v8/detect folder
- Run the code with mentioned command below.
```
python predict.py model=yolov8l.pt source="your_video.mp4" show=True
```
## Credits

This project was developed by [Md. Tahmid Sarker Mahi](https://tahmid-sarker.github.io).