# PocoByte Implmentation for video converancing platform
![Poco](https://drive.google.com/uc?export=view&id=1zOYoctOgaU3xeV7ours-zLlsiQgGot1b)
## Content:
- **BaseLine**: Main Algorithms of core Architecture 
  - This the current baseLine and we are researching for better baselines
  - FOMM
  - Bilayer
- **PocoByte For You**: User interface(Website)
  - index.html: main website page
- **PocoByte Meeting App**: video conference based on webrtc and firebase utilizing this repo
    - https://github.com/fireship-io/webrtc-firebase-demo?fbclid=IwAR1HFdclJDRWxelqIrO7bUGtQRrjLxKEBI5AkG8-80w9HhJ7G3d7crWYDrY
  - index.html: "create a call" page
  - index2.html: "join a call" page
- **Notebook**: showcase of how Proof of concept were Implemented.
# Evaluation:(proof of concept)
We made an experiment to compare between our baseline and H.264 codec We used video of 10 sec with 256x256 
resolution and the original size was 34.44Mb and after processing to our model and h264 we got videos with this sizes 
|            | Original  | BaseLine  | H.264 |
| :---:      |  :-:      | :-:       | :-:   |
| Resolution | 256x256   | 256x256   | 256x256|
| size       | 34.44Mb       | 87.69Kb       | 87.69Kb   |

- crf=32 compression ratio about 2.4% which is minmal for video quality.

# Refrences:
  - https://aliaksandrsiarohin.github.io/first-order-model-website/
  - https://arxiv.org/abs/2008.10174

