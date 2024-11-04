# GGStatify
Python에서 실수 배열을 대상으로 통계, 분포, 확률, 스케일링과 관련된 다양한 메서드를 제공하는 라이브러리입니다.
* 현재 개발 진행 중인 코드로, 내부 코드들과 라이브러리 구조는 언제든지 수정될 수 있습니다.

</br>
</br>
</br>

## A. modules
* 해당 라이브러리는 다음과 같은 모듈들로 구성되어 있습니다.
### 1. descript
* 기술 통계량을 출력하기 위한 method들의 모음입니다.
* 해당 코드에는 다음과 같은 method 들로 구성되어 있습니다.
> * frequency_table(): 빈도표 생성
> * cross_table(): 교차표 생성

</br>

### 2. distribution
* 무작위 분포를 생성하기 위한 method들의 모음입니다.
* 해당 코드에는 다음과 같은 method 들로 구성되어 있습니다.
> * linear(): 무작위 선형 분포 생성
> * normal(): 무작위 정규 분포 생성
> * f(): 무작위 f 분포 생성

</br>

### 3. probability
* 확률 관련 method들의 모음입니다.
* 해당 코드에는 다음과 같은 method 들로 구성되어 있습니다.
> * binary_probability(): p의 확률로 True 출력
> * choose_one(): 입력된 배열에서 무작위로 한 개의 원소 출력

</br>

### 4. scaler
* scaling 관련 method들의 모음입니다.
* 해당 코드에는 다음과 같은 method 들로 구성되어 있습니다.
> * small_denominator(): 분모가 0인 경우, 매우 작은 값을 대신 출력
> * min_max(): 입력된 배열에 대하여 min-max scaling
> * min_max_range_normalization(): 입력된 배열을 min, max 사이로 min-max scaling 함
> * z_score_normalization(): 입력된 배열을 평균이 0, 표준편차가 1인 z-score로 정규화함
> * natural_logarithm(): 입력된 배열을 자연 로그 치환
> * robust(): 입력된 배열을 사분위 범위를 이용하여 Robust scaling 함
> * max_abs(): 입력된 배열을 절대값 기준으로 최대 절대값이 1.0이 되도록 스케일링

</br>
</br>
</br>

## B. 외부 라이브러리 의존성
* 해당 코드는 현재 개발중인 단계로 CI/CD 를 위한 외부 라이브러리 의존성 버전 확인이 진행되지 않은 상태입니다.
* 현재 작성되어 있는 각 라이브러리의 버전은 개발 환경의 버전입니다.
> * numpy == 1.26.4
> * pandas == 2.2.2
> * scipy == 1.14.0