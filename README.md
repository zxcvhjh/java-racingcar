# Racing Game

## 기능 요구 사항
1. **자동차 이름 입력**: 쉼표(,)로 구분된 자동차 이름을 입력받습니다. 각 이름은 5자 이하여야 합니다.
2. **시도 횟수 입력**: 시도할 횟수를 입력받습니다.
3. **경주 진행**:
   - 각 자동차는 무작위 값(0~9)을 받아 4 이상일 때 전진합니다.
   - 경주가 진행될 때마다 각 자동차의 위치를 출력합니다.
4. **우승자 발표**: 최종 우승자를 출력합니다. 동점자가 있으면 쉼표(,)로 구분하여 여러 우승자를 표시합니다.
5. **잘못된 입력 처리**: 자동차 이름이 5자를 초과하거나, 입력 값이 부적절하면 `IllegalArgumentException`이 발생하고 프로그램은 종료됩니다.

