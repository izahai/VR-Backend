## Workflow
![Workflow](https://raw.githubusercontent.com/izahai/VR-Backend/refs/heads/main/workflow.png)

## Setup

For Mac user, ffmpeg and ffprobe are essential make sure you export it in terminal
```bash
export PATH="<path where ffmpeg and ffprobe are placed>:$PATH"
```

Create virtual env
```
conda env create -f environment.yml
```

Activate env
```
conda activate VrBackend
```

Get ip LAN
```
ifconfig | grep inet
```

## Command-line usage
```
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```