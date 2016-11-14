# temporal-median-video

Python program for processing a temporal median filter effect across a set of frames from a video. 
<br><br>
**Usage:**

`python temporal_median.py -i "<set_of_frames>" -o "<output_path>" -l <number of frames to process> -offset <length of filter in frames> -simul <frames to process simultaneously> `

<br>
**Surfing Example:**
<br>
<br>
Original:<br>
[<img src="img/gopro_surf_trim.gif" width="500px"/>](https://www.youtube.com/watch?v=LUGksGa4WJA)<br>
https://www.youtube.com/watch?v=LUGksGa4WJA
<br><br>
TMF:<br>
[<img src="img/gopro_surf_tmf.gif" width="500px"/>](https://www.youtube.com/watch?v=6K8_iQOxo4w)<br>
https://www.youtube.com/watch?v=6K8_iQOxo4w

<br>
**Saigon Traffic Example:**

Original: https://www.youtube.com/watch?v=8QCsQnr2w4w

TMF: https://www.youtube.com/watch?v=Yhy1uc9s8IU

<br><br>
**Dependencies:**

[PIL] (http://www.pythonware.com/products/pil/)
[Numpy] (http://www.numpy.org/)

<br>

**Prior Works:**

Similar to zo7's median-video (but that one is in C++ and requires OpenCV). 
https://github.com/zo7/median-video

