# 2019.03 b과제
## FAQ UI만들기

> 웹에 자주 사용되는 FAQ UI를 제작합니다.

### RULE
1. **완료기한 > 2019.03.20**
2. HTML, CSS는 아래 예시 코드를 사용한다. (코드 비교 수월)  
3. 각 row의 제목을 클릭하면 숨겨져있던 해당 row의 콘텐츠를 노출시킨다. 
4. 클릭한 row 외 콘텐츠는 모두 숨김처리 한다.
5. 클릭한 row 의 콘텐츠가 이미 열려있으면 숨김처리 한다.

***

```html
<style>
* {margin:0; padding:0;}
ul, li {list-style:none;}
.faqBox {margin:10px auto; max-width:640px; border:1px solid #ccc;}
.faqBox li {border-top:1px solid #ccc;}
.faqBox li:first-child {border-top:0;}
.faqBox li .question {display:block; padding:15px;}
.faqBox li .answer {height:0; position:relative; padding:0; overflow:hidden;}
.faqBox li.active .question {color:#fff; background:#333;}
.faqBox li.active .answer {padding:15px; height:auto; border-top:1px solid #ccc;}
</style>
<div class="faqBox">
    <ul class="list">
        <li class="active">
            <a href="javascript:;" class="question">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent du</p>
            </a>
            <div class="answer">
                <p>
                    ligula et molestie consectetur, metus mi scelerisque sem, a lobortis eros metus sed ante. 
                    Donec tincidunt rutrum ultrices. Quisque malesuada vel est a consectetur. Suspendisse mattis bibendum est, 
                    non tincidunt massa dignissim eu. Sed nec posuere quam, ac condimentum lacus. Proin dapibus justo et varius congue. 
                    Cras non posuere ipsum, eget tincidunt erat. Etiam non lorem feugiat, volutpat felis ut, consequat arcu. 
                    Phasellus vel leo vulputate metus dignissim sollicitudin. 
                    Morbi molestie viverra purus, a fringilla risus placerat et. Curabitur molestie magna et dui mollis venenatis.
                </p>
            </div>
        </li>
        <li>
            <a href="javascript:;" class="question">
                <p>Aliquam mauris arcu, blandit quis tempus et, dapibus id nulla. M</p>
            </a>
            <div class="answer">
                <p>
                    ligula et molestie consectetur, metus mi scelerisque sem, a lobortis eros metus sed ante. 
                    Donec tincidunt rutrum ultrices. Quisque malesuada vel est a consectetur. Suspendisse mattis bibendum est, 
                    non tincidunt massa dignissim eu. Sed nec posuere quam, ac condimentum lacus. Proin dapibus justo et varius congue. 
                    Cras non posuere ipsum, eget tincidunt erat. Etiam non lorem feugiat, volutpat felis ut, consequat arcu. 
                    Phasellus vel leo vulputate metus dignissim sollicitudin. 
                    Morbi molestie viverra purus, a fringilla risus placerat et. Curabitur molestie magna et dui mollis venenatis.
                </p>
            </div>
        </li>
        <li>
            <a href="javascript:;" class="question">
                <p>Phasellus eu aliquam elit. Pellentesque habitant morbi tristiqu</p>
            </a>
            <div class="answer">
                <p>
                    ligula et molestie consectetur, metus mi scelerisque sem, a lobortis eros metus sed ante. 
                    Donec tincidunt rutrum ultrices. Quisque malesuada vel est a consectetur. Suspendisse mattis bibendum est, 
                    non tincidunt massa dignissim eu. Sed nec posuere quam, ac condimentum lacus. Proin dapibus justo et varius congue. 
                    Cras non posuere ipsum, eget tincidunt erat. Etiam non lorem feugiat, volutpat felis ut, consequat arcu. 
                    Phasellus vel leo vulputate metus dignissim sollicitudin. 
                    Morbi molestie viverra purus, a fringilla risus placerat et. Curabitur molestie magna et dui mollis venenatis.
                </p>
            </div>
        </li>
        <li>
            <a href="javascript:;" class="question">
                <p>Donec gravida vel magna a mollis. Nulla et mauris ut leo m</p>
            </a>
            <div class="answer">
                <p>
                    ligula et molestie consectetur, metus mi scelerisque sem, a lobortis eros metus sed ante. 
                    Donec tincidunt rutrum ultrices. Quisque malesuada vel est a consectetur. Suspendisse mattis bibendum est, 
                    non tincidunt massa dignissim eu. Sed nec posuere quam, ac condimentum lacus. Proin dapibus justo et varius congue. 
                    Cras non posuere ipsum, eget tincidunt erat. Etiam non lorem feugiat, volutpat felis ut, consequat arcu. 
                    Phasellus vel leo vulputate metus dignissim sollicitudin. 
                    Morbi molestie viverra purus, a fringilla risus placerat et. Curabitur molestie magna et dui mollis venenatis.
                </p>
            </div>
        </li>
    </ul>
</div>
```

![결과물 UI](./201903b_.png)  

***

__과제에 대한 자세한 설명은 업데이트 중__
  
