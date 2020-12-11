# choleor-DB

### 1. 영상 링크 및 적합성 정보 수집
![스크린샷, 2020-12-11 23-26-45](https://user-images.githubusercontent.com/50199997/101917674-dde4d380-3c0b-11eb-89fe-f0f2ea52db33.png)

### 2. 영상을 8박자 단위로 끊고 끊어진 영상 frame 기록(FrameSliceTool.ipynb 사용)
![스크린샷, 2020-12-11 23-27-01](https://user-images.githubusercontent.com/50199997/101917683-de7d6a00-3c0b-11eb-9599-458457007ec3.png)

### 3. 끝어진 영상의 시작과 끝 포즈의 포즈값, x_mean, y_min, y_max등의 값 수집(MakeDatebaseTool.ipynb 사용)
![스크린샷, 2020-12-11 23-27-37](https://user-images.githubusercontent.com/50199997/101917692-dfae9700-3c0b-11eb-95e6-dd5ab95548f6.png)

### 4. 각 8박자 영상의 움직임 정보 수집(MovementValue.ipynb 사용)
![스크린샷, 2020-12-11 23-27-57](https://user-images.githubusercontent.com/50199997/101917696-e0dfc400-3c0b-11eb-912f-458379331308.png)

### 5. 4번에서 구한 값을 1~10의 번주형 수치로 변환해서 사용
![스크린샷, 2020-12-11 23-28-07](https://user-images.githubusercontent.com/50199997/101917707-e3421e00-3c0b-11eb-9f52-b5ff280b1f55.png)
