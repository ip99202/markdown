#markdown
  
문단을 구분하려면 2줄 이상의 빈줄이 있거나 2칸 이상의 빈칸을 두면 줄 개행이 가능하다  

# 헤더 크기 (h1) 
## 헤더 크기 (h2) 
### 헤더 크기 (h3) 
#### 헤더 크기 (h4) 
##### 헤더 크기 (h5) 
###### 해더 크기 (h6)
#의 갯수에 따라 글자의 크기가 달라진다 하나가 가장 크고 6개가 가장 작다


목록사용법
Unordered 
* Item 1 
* Item 2 
    * Item 2a 
    * Item 2b 

Ordered 
1. Item 1 
1. Item 2 
1. Item 3 
    1. Item 3a 
    1. Item 3b
    
unodered는 *을 붙여 사용한다
odered는 숫자를 붙여 사용한다


이미지 삽입
첫번째 방법 
![Github logo](/images/markdown_logo.jpg) 
Format: ![이미지 alt명](url 링크) 

두번째 방법 
<a href="#"><img src="https://github.com/..각자절대경로../images/markdown_syntax.jpg" width="400px" alt="sample image"></a> 
Format: img 태그 사용 - 이미지경로는 상대경로 or 절대경로



하이퍼링크
[GitHub](http://github.com "깃허브")



코드 블록
해당 언어를 쓰면 인식한다
```C++ 
int main() {
  int a;
  cin >> a;
  cout << a;
}
```


인용상자
As Grace Hopper said: 

> I’ve always been more interested. 
> in the future than in the past.
