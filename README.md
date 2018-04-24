# Nanum Square <span style="font-size:0.85em"> - with Fallback</span>
기존 나눔스퀘어에서는 한자를 포함해 완성형 글자(2350자)를 뺀 나머지 글꼴들이 공백처리되는 문제가 존재합니다. 빈 글자가 아닌, 다른 폰트로 대체(fallback)할 수 있도록 수정했습니다.

[관련링크 - 나눔스퀘어 글꼴에서는 안보이는 글자들 ](http://hanjoonkblog.blogspot.kr/2017/12/blog-post.html)

## Usage
```html
<link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/skt-t1-byungi/nanum-square-fallback/master/webfont/nanum-square.css">
<style>
html, body{
  font-family: NanumSquare, sans-serif;
}
</style>
```

## Related
- [네이버 나눔글꼴](http://hangeul.naver.com/font)

## License
나눔글꼴 라이센스 정책에 의거해 비상업적 용도에 한해 수정 및 재배포 가능합니다. 
