# jekyll-practice-1

## 『 notes 』
### [ basic use ]
- new、build、serve

<hr>

### [ style ]
- scss
    - main、partial
    - partial的內容必須放在"_sass"這個資料夾內
    - main可以直接存取到_sass內的partial scss file，而不用考慮路徑的階層
        - ex：`@import "partial";`
    - main所在的資料夾，不管位於多深，build之後會產生同樣的階層架構在_site裡面
