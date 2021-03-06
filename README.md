# ๐Dialogue State Tracking
## Task Description
- Task: ์ฃผ์ด์ง ๋ชฉ์  ์งํฅํ ๋ํ์ Dialogue State๋ฅผ ์์ธกํฉ๋๋ค.
- Metric: Joint Goal Accuracy, Slot Accuracy, Slot F1 Score

## Command Line Interface
### Train Phase
```python
>>> cd code
>>> python train.py --project_name [PROJECT_NAME] --model_fold [MODEL_FOLD_NAME] --dst [DST_MODEL]
```

### Inference Phase
```python
>>> cd code
>>> python inference.py --model_fold [MODEL_FOLD_NAME] --chkpt_idx [CHECKPOINT INDEX]
```

### Application: wandb
1. train.pyํ์ผ์ ์ํํ๋ฉด ๋ค์๊ณผ ๊ฐ์ ํ๋ฉด์์ 2๋ฒ ์ ํ

  ![image](https://user-images.githubusercontent.com/46676700/116401727-89628d80-a866-11eb-9069-5c7a947741ab.png)


2. API key๋ฅผ ๋ฐ์ ์ ์๋ ๋งํฌ๋ก ๋ค์ด๊ฐ (๊ทธ๋ฆผ 2๋ฒ์งธ ์ค) ๊ณต์  ๊ณ์ ์ผ๋ก ๋ก๊ทธ์ธ

  ![image](https://user-images.githubusercontent.com/46676700/116401752-91223200-a866-11eb-80e7-78af8acb2049.png)

3. ์๋์ ๊ฐ์ด key๊ฐ์ terminal ์ฐฝ์ ๋ณต์ฌ ๋ถ์ฌ ๋ฃ๊ธฐ


    <img src="https://user-images.githubusercontent.com/46676700/116401797-9f704e00-a866-11eb-91b3-1cb509c19c88.png" width="40%">

    - ๋ค์๊ณผ ๊ฐ์ด ์ํ๋จ
  
    ![image](https://user-images.githubusercontent.com/46676700/116401807-a26b3e80-a866-11eb-93ee-7a7e0b510a8b.png)


4. wandb ํํ์ด์ง์์ ๋ค์๊ณผ ๊ฐ์ด ๋ง๋ค์ด์ง project๋ฅผ ํ์ธํ  ์ ์์

  ![image](https://user-images.githubusercontent.com/46676700/116401826-a6975c00-a866-11eb-806b-21e6cc6c5492.png)

  ![image](https://user-images.githubusercontent.com/46676700/116401835-a9924c80-a866-11eb-9b67-a918fb258b52.png)

## TEAM FreshTomato๐
- [๊ณ ์งํ](https://github.com/iloveslowfood), [๊น์งํ](https://github.com/KimJinHye0n), [๋ฌธ์ฌํ](https://github.com/MoonJaeHoon), [๋ฐฐ์๋ผ](https://github.com/arabae), [์ต์ ๋ผ](https://github.com/Yuuraa), [์ต์ค๊ตฌ](https://github.com/soupbab)