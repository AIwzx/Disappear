# Disappear

A project makes anything disappear in your image/video, combines with Meta's SAM.

> 🛠️☣️⚠️ Work in progress.

Think that you just need typing `make the dogs in image gone`, and then the dogs in your image are completely gone. This now can be done along with SAM!


However, this seems not easy to integrate, we will implement it in 3 phases:

- **step 1**: Remove humans in video;
- **step 2**: integrate SAM models;
- **step 3**: SAM + Inpainting;


Here are some result:

![](https://jihulab.com/mingliu/pics/-/raw/main/pictures/2023/04/8_19_18_58_ezgif-4-d56197716c.gif)

![](https://jihulab.com/mingliu/pics/-/raw/main/pictures/2023/04/8_19_19_7_4.gif)

![](https://jihulab.com/mingliu/pics/-/raw/main/pictures/2023/04/8_19_19_13_5.gif)


## Install

```
pip install -U alfred-py
pip install -e .
```

pypi comes soon.


## Note

All models can be found on GitHub, you can train with it if you like as well.
