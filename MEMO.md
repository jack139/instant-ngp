## MEMO

### 从视频生成 NeRF 数据集

```bash
cd video
python3.6 ../scripts/colmap2nerf.py --video_in 1.mp4 --video_fps 2 --run_colmap --aabb_scale 32
```

> pip3.6 list

```text
opencv-python            4.5.5.64
opencv-python-headless   4.5.3.56
imageio                  2.13.5
scipy                    1.5.4
numpy                    1.18.5
```



### 训练

```bash
./instant-ngp video
```


