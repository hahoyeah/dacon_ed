# dacon_ed

구내식당 최종

따릉이 기본

따릉이1: 그리드서치를 이용한 하이퍼파라미터

따릉이2: wheater라는 feature 추가

따릉이3: RandomizedSearchCV을 이용한 하이퍼파라미터

따릉이4: 피쳐엔지니어링에 하이퍼파라미터 추가 0.1438 - 가장 좋은 값이 나옴

따릉이5: differ이라는 feature을 만들었지만 성능 x - 0.1464

따릉이6: sky_condition feature을 제거해줌 -0.15

랜덤포레스트 모델이 가장좋았다. (linear도 해봤지만 성능 x) - 0.1892

최종: 랜덤포레스트, 그리드서치, wheater 피쳐사용 (differ도 잘 다루면 성능이 좋아질거같다...)
