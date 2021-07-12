# [Dimensional reduction와 Feature Selection의 차이는 무엇일까?](https://stackoverflow.com/questions/16249625/difference-between-pca-principal-component-analysis-and-feature-selection)

- Feature Selection도 데이터 X에서 Feature를 제거하는 차원을 낮추는 작업이고 Dimensional Reduction도 차원을 낮추는 작업이라면 그 두가지의 차이점은 무엇일까?

여러 답변이 있었지만 이 답변이 제일 간명했다.

1. The difference is that **PCA** will try to reduce dimensionality by **exploring how one feature of the data is expressed in terms of the other features**(linear dependecy). **Feature selection** instead, takes the **target** into consideration.

2. PCA를 포함해서 다른 차원축소 방법에도 적용될 말이기에, 거칠게 요약하면 차원 축소는 다른 피처들과의 공분산행렬을 이용해서 진행하기 때문에 다른 피처들과의 관계가 중요하고, 피처 선택은 타깃과의 관계를 보고 결정한다는 내용이다.

3. 코드로 설명하는 Feature Selection vs Dimensional Reduction : [링크](https://towardsdatascience.com/feature-selection-and-dimensionality-reduction-f488d1a035de)
