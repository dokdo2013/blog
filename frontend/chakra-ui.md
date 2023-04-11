# Chakra UI 간단 사용기

> 원본 글 : [https://blog.haenu.com/2](https://blog.haenu.com/2)
>
> 2022년 3월 9일에 작성된 포스트를 가져왔습니다.

<figure><img src="https://blog.kakaocdn.net/dn/y4zup/btrE5Tnv0EB/VbSEoS9Gw6P4PpRGxWAMPK/img.png" alt=""><figcaption></figcaption></figure>

이번에 '포도당 노래책' 프로젝트를 진행하며 Chakra UI를 처음 사용해보았다. 이전에 대학생 개발자 단톡방에서 React에서 사용 가능한 UI Library 추천을 받았었는데, 그때 추천받았던 Chakra UI가 상당히 깔끔해서 마음에 들었다. Material UI와 Ant Design도 간략히 사용해봤었는데, 개인적으로 Charka UI의 디자인 스타일이 더 좋아서 이번 기회에 사용해보기로 했다.

### 1. 설치

{% embed url="https://github.com/chakra-ui/chakra-ui" %}

```
yarn add @chakra-ui/react @emotion/react@^11 @emotion/styled@^11 framer-motion@^5
```

리액트 프로젝트를 세팅한 후 위 명령어를 입력하여 설치하면 된다. 자세한 내용은 깃허브 참고.

### 2. 템플릿(?)

{% embed url="https://chakra-templates.dev/" %}

사실 리액트의 다른 UI 라이브러리들도 비슷한 상황이지만 템플릿들이 많이 부족한게 현실이다. Envato Market과 같은 템플릿 판매 사이트에서도 워드프레스나 부트스트랩 기반 템플릿은 매우 많은데 반해 MUI나 Ant Design, Chakra UI 등을 이용한 템플릿은 매우 적은 수준이다. 이번에 Chakra UI를 사용해보며 여러 템플릿들을 살펴보았는데 위 템플릿에 기본적으로 필요한 레이아웃이 모두 있어 사용하게 되었다.

### 3. 없으니 아쉬운 기능들...

<figure><img src="https://blog.kakaocdn.net/dn/7E0XY/btrvwJUNWiG/HEsIXTlSpGVZqHKhXi9L2k/img.png" alt=""><figcaption><p>Chakra UI에는 Datepicker가 없다</p></figcaption></figure>

Chakra UI에는 Datepicker가 없다. 꼭 필요할 때 없으면 참 아쉬운 것 같다. 다행히 이번 프로젝트에선 사용할 일이 없었는데 'currently we don't provide' 라고 했으니 머지않은 시일 내에 추가되길 기대해본다.

<figure><img src="https://blog.kakaocdn.net/dn/WpR4k/btrvvalFklz/pf0vL3Cc5SOUnAvy7MOEkk/img.png" alt=""><figcaption><p>MUI의 Search Input 기능</p></figcaption></figure>

Bootstrap 기반의 템플릿들을 사용하다보면 검색이 가능한 Select Box가 있곤 하다. MUI와 Ant Design에서도 제공해주기도 하는데, Chakra UI에서는 제공해주지 않고 있다. chakra-ui-autocomplete라는 서드파티 라이브러리가 있긴 한데, 주로 해시태그처럼 Multi Select 용도로 사용되는 것 같고, 커스터마이징이 어려워 사용을 포기했다.

{% embed url="https://github.com/koolamusic/chakra-ui-autocomplete" %}

### 4. 생태계는 여전히 부족한듯?

단순히 깃허브 Repository 숫자로만 판단할 수는 없겠지만,  다른 라이브러리들에 비해 서드파티 라이브러리들이 많이 부족한 게 느껴진다.&#x20;

\- Bootstrap 검색 시 : 405,947 Repositories

\- Material Ui 검색 시 : 27,323 Repositories

\- Ant Design 검색 시 : 8,006 Repositories

\- Semantic Ui 검색 시 : 5,114 Repositories

\- Chakra Ui 검색 시 : 2,914 Repositories

### 5. 총평

Chakra UI... 참 좋은데 쓰다 보면 약간씩 부족한 느낌이 든다. UI 라이브러리가 모든 기능에 대한 Needs를 충족시킬 수는 없겠지만, 대부분의 라이브러리들은 커뮤니티의 지원을 통해 그 부족한 부분을 최대한 채우기 위해 노력하고 있다.

개인적으로 깔끔하고 직관적인 디자인이 매우 마음에 들었다. 부트스트랩 디자인은 이미 너무 오래되었고, Material Design 역시 너무 흔한 디자인이 되었다. Ant Design은 영어 자료에 비해 중국 자료가 월등히 많아 서칭에도 어려움이 있었다. 타 라이브러리들에 비해 여러 방면에서 우위를 가지고 있는 만큼 더 성장했으면 하는, 앞으로가 더 기대되는 라이브러리이다.
