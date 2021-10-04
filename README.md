# 일기장 앱

## 구현 목표
- 일기를 작성할 수 있다(`데이터 전달`)
- 작성한 일기를 저장, 콜렉션 뷰로 띄워줄 수 있다(`UserDefaults`, `UICollectionViewFlowLayout`, `UICollectionViewDataSource`, `UICollectionViewDelegateFlowLayout`)
- 작성한 일기를 터치했을 때, 상세보기 뷰에서 내용을 볼 수 있다
- 작성한 일길를 삭제할 수 있다
- 작성한 일기를 수정할 수 있다(`NotificationCenter`, `Observer`)
- 별 버튼이 true일 때, 즐겨찾기 탭에서 볼 수 있다
- 즐겨찾기로 지정한 일기를 즐겨찾기 탭에서 콜렉션 뷰로 띄워줄 수 있다
- 즐겨찾기 탭에서 각각 셀들을 선택했을 때, 상세보기 뷰에서 내용을 볼 수 있다

## 활용 기술
- UITabBarController
- UICollectionView
- UserDefaults
- NotificationCenter
