# Position을 알아보자
## 공통사항
1. position: relative, absolute, fixed에서만 left, right, top, bottom이 적용된다.
2. 모든 태그는 떠오르는 순간 위치값(left, ...)을 지정하지 않으면 제자리에서 레이어가 된다.
3. 모든 태그는 떠오르는 순간 작아진다(내용물의 크기만큼 줄어든다)
4. z-index로 높이를 줄 수 있다. (숫자가 높을수록 위로 온다)

## position: absolute
1. 떠오르는 순간 문서의 기준점을 찾는다. **기준점은 그때그때 달라요.**
	- 기준점은 부모중 가장 가까운 레이어가 된(position: absolute, relative, fixed)부모를 기준으로 한다.

## position: relative
1. 레이어가 되지만, 크기나 위치가 변하지 않는다. 그래서 기준점이 되기 위해 주로 적용한다.

## position: fixed
1. 무조건 현재 보이는 화면(브라우저)을 기준으로 한다.

## position: static(기본값)
1. 모든 태그를 생성하면 기본으로 **position: static**이 적용된다