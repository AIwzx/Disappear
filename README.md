<div align="center">
<h1>Disappear</h1>
</div>


<div align=center>
<img src="https://jihulab.com/mingliu/pics/-/raw/main/pictures/2023/04/8_19_18_58_ezgif-4-d56197716c.gif" width=300"/>

<img src="https://jihulab.com/mingliu/pics/-/raw/main/pictures/2023/04/8_19_24_15_ezgif-4-fe68de1579.gif" width="300"/><img src="https://jihulab.com/mingliu/pics/-/raw/main/pictures/2023/04/8_19_31_31_ezgif-4-67745aad04.gif" width="300"/>
</div>

A project makes anything disappear in your image/video, combines with Meta's SAM.

> 🛠️☣️⚠️ Work in progress.

Think that you just need typing `make the dogs in image gone`, and then the dogs in your image are completely gone. This now can be done along with SAM!


However, this seems not easy to integrate, we will implement it in 3 phases:

- **step 1**: Remove humans in video;
- **step 2**: integrate SAM models;
- **step 3**: SAM + Inpainting;

Here are some result:




## Install

```
pip install -U alfred-py
pip install -e .
```

pypi comes soon.


## Note

All models can be found on GitHub, you can train with it if you like as well.
