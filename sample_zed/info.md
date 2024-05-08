This is a small dataset where I. The data contains both stereo images and depth image. Usage:

```python
data = np.load('data.npz')
stereo_images = data['stereo']
depth_images = data['depth']

cv2.imshow('Stereo Image', stereo_images[0])
```
git lfs track "*.npz"
