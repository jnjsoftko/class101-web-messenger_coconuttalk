## 1-1 HTML과 CSS

### src/index.html

- `index.html` 생성
- html snippet
  - `!` -> Enter
- 파일 편집

### src/style.css

- `style.css` 생성
- 파일 편집

## 1-2 HTML주요 태그 및 속성

### src/index.html

- 파일 편집

### src/chat.html

- 파일 편집

## 1-3 CSS 주요 속성 (1)

> position.html
> position.css

### position 속성

- 문서 상에 요소를 배치하는 방법을 지정

#### relative

- 요소를 일반적인 문서 흐름에 따라 배치하고, 자기 자신의 원래 위치를 기준으로 위치를 결정할 수 있게 합니다.

#### absolute

- 가장 가까운 상위 position 요소를 기준으로 위치를 결정할 수 있게 합니다. position 요소란 static 상태가 아닌 요소를 뜻합니다.

#### fixed

- 요소를 일반적인 문서 흐름에서 제외시키고, 화면을 기준으로 위치를 결정할 수 있게 합니다.

#### sticky

- 요소를 일반적인 문서 흐름에 따라 배치하고, 가장 가까운 스크롤되는 상위 요소를 기준으로 위치를 고정시킵니다.

## 1-4 CSS 주요 속성 (2)

> display.html
> display.css

### display 속성

#### inline

- 인라인 레벨 요소는 너비와 높이, 즉 width와 height를 가지지 않고 오직 콘텐츠의 양에 따라 크기가 결정됩니다. span은 대표적인 인라인 레벨 요소입니다.

#### inline-block

- 요소의 배치는 인라인 레벨로 하지만, 블록 레벨의 요소처럼 width와 height를 지정할 수 있게 해줍니다. a 나 button 등이 이에 해당합니다.

#### block

- 요소의 배치를 블록 레벨로 유지합니다. div나 h1, p 등이 블록 레벨 요소입니다.

#### flex

- 요소 자신은 블록 레벨로 유지되지만, 자식 요소 배치에 대한 추가 속성을 제공하는 속성값입니다.

### flex box

- flex 속성값이 지정된 요소를 '플렉스 박스'라 표현합니다.

플렉스 박스에는 주축과 교차축이라는 개념이 있는데,

기본 주축은 가로 방향, 교차축은 세로 방향입니다.

#### flex-direction

- 플렉스 박스 주축의 방향을 결정할 수 있는 속성
- row
- column
- row-reverse
- column-reverse

#### justify-content

- 주축에서의 요소 배치 방식을 결정할 수 있는 속성
- flex-start
- flex-end
- center
- space-between
- space-around
- space-evenly

#### align-items

- 교차축에서의 요소 배치 방식을 결정할 수 있는 속성
- flex-start
- flex-end
- center
- space-between
- space-around
- space-evenly

## 1-5 무료 아이콘 사용 방법

> icon.html

### 폰트어썸

- 폰트어썸은 아이콘 저장소 서비스로써, 여기에서는 웹문서에서 사용할 벡터 아이콘을 얻을 수가 있습니다.

#### 폰트어썸 주소

- https://fontawesome.com/

#### 킷코드(kit code)

- 폰트어썸을 사용하려면 회원가입 후 이메일 인증 절차를 거쳐야 하며, 회원에게 발급되는 킷코드(kit code)를 웹 문서에 추가해야 합니다.

#### 킷코드 추가

- 폰트어썸에서 발급받은 킷코드를 웹 문서에 추가하는 것이

먼저입니다.

- 킷코드는 <head> 태그의 안쪽 아무데나, 또는 <body> 태그 안쪽 맨 아래에 추가하는 것이 일반적입니다. 영상에서는 <head> 안쪽에 추가하였습니다.

- https://fontawesome.com/search
- 킷코드를 추가한 상태에서, 사용하고자 하는 아이콘을 폰트어썸 사이트에서 검색합니다. 검색 시에는 아이콘과 관련있는 키워드를 입력해 검색합니다. 예를 들어 강아지 아이콘을 원한다면 dog나 puppy 등으로...

- 아이콘을 검색하면, 곧 검색 결과가 나타납니다.

색깔로 무료 아이콘과 유료 아이콘이 구분지어져 있습니다.

- 사용할 아이콘의 상세 페이지로 들어가면, 아이콘을 표시하기

위해 제공되는 <i>태그를 복사할 수 있습니다.

이를 복사하여 웹문서의 원하는 위치에 추가하면 됩니다.

- 복사한 <i> 태그의 시작 태그에 클래스를 추가하여 사이즈를

조절할 수 있습니다.
