# HotFeedbackSearch
this is the hot-feedback search using vue,sass

## What
- 實時搜尋

## How to use
```
filtered() {
      const filter_covers = this.filtering //[]
      var _this = this;
      return filter_covers.filter(filter_cover => {
        var tag = ["title"];
        var flag = false;
        tag.forEach(function(now_tag) {
          if (
            filter_cover[now_tag]
              .toLowerCase()
              .indexOf(_this.filter.toLowerCase()) != -1
          ) {
            flag = true;
          }
        });
        return flag;
      });
    }
```
## Using
Vue ,Sass, Webpack,bootstrap4

## DEMO
CodePen: https://codepen.io/chienweiluo/pen/QMYYxy
