# CNN_
생활코딩 3일차 Conv2D의 코드입니다.\
더 자세히 알고 싶다면 [링크](https://opentutorials.org/module/5268/29788)를 클릭하세요.

생활코딩 4,5일차의 내용도 함께 있습니다. 

## Conv2D
Conv2D는 특징맵을 만드는 함수이다. 특징 자동 추출기라는 이름을 가지고 있다.\
`Conv2D(3, kernel_size = 5, activation = 'swish')` 에서 맨 첫번째 숫자는 특징맵의 개수를 의미한다.


## MaxPool2D
MaxPool2D는 해상도를 낮추어서 메모리 사용량과 연산량을 줄이는 역할을 한다.\
Conv2D 파일과 비교해서 보면 파라미터의 수가 현저히 줄어있는 것을 볼 수 있다. 
