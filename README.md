# Non-Lambertian 4D Light-Field Dataset

# Non-Lambertian LF

**Non-Lambertian-LF** is a synthetic light field depth estimation dataset focused on non-Lambertian objects. 
| Type              | Device  | Angle Resolution | Spatial Resolution | Element                                                      |
| ------------------| --------| ---------------- | ------------------ | ------------------------------------------------------------ |
| Non-Lambertian-LF | Blender | 9×9              | 926×926            | sub-aperture images, disparity information of central view.  |

Non-Lambertian-LF contains four scenes with ground truth disparity range [-0.41,0.48] pixels between adjacent views, transparency range [20%, 90%], reflectance range [20%, 90%], and concentration range of fog [0%, 80%].
<br/>

- "Teddy" is a scene of a teddy bear half obscured by glass, which is designed to test the continuity of the background's disparity result. 
- "David" is a set of images with the same scene, where the head of the statue David is obscured by a glass of varying transparency. The transparency of the glass itself gradually decreases from 90% to 20% by 20% as a step, and the transparency floats between plus and minus 10% due to random noise and patterns on the glass. 
- "Apple" is a set of images with the same scene, where an apple sits on a smooth marble table. The marble tabletop with different reflectivity reflects the reflection of the apple. This set of data is used to test the robustness of different reflectances.
- "Foggy Mine" is a set of images of mine scenes with different concentrations of fog. The concentration of fog in the mine gradually increased from 0% to 80%. This set of data is used to test the robustness of different concentration of fog.

### Data Link
Data is publicly available in [Baiduyun](https://pan.baidu.com/s/1rMLxu1vY8l8yrAtTw7r_Ig?pwd=ms87) and [Google](https://drive.google.com/file/d/1obKkSmINfBHFaQK8MVtf-dKfbQnp31Sx/view?usp=share_link).

<br/>

# Citation

If you find this work is helpful to you, please cite the following paper:

```
@ARTICLE{sheng2022urbanlf,
  author={Sheng, Hao and Cong, Ruixuan and Yang, Da and Chen, Rongshan and Wang, Sizhe and Cui, Zhenglong},
  journal={IEEE Transactions on Circuits and Systems for Video Technology}, 
  title={UrbanLF: A Comprehensive Light Field Dataset for Semantic Segmentation of Urban Scenes}, 
  year={2022},
  volume={32},
  number={11},
  pages={7880-7893},
  doi={10.1109/TCSVT.2022.3187664}}

@ARTICLE{10174727,
  author={Cui, Zhenglong and Sheng, Hao and Yang, Da and Wang, Sizhe and Chen, Rongshan and Ke, Wei},
  journal={IEEE Transactions on Circuits and Systems for Video Technology}, 
  title={Light Field Depth Estimation for Non-Lambertian Objects via Adaptive Cross Operator}, 
  year={2024},
  volume={34},
  number={2},
  pages={1199-1211},
  keywords={Estimation;Image reconstruction;Shape;Image color analysis;Costs;Cameras;Three-dimensional displays;Light field;non-Lambertian;depth estimation;non-Lambertian region detection;adaptive cross operator},
  doi={10.1109/TCSVT.2023.3292884}}
```

<br/>


