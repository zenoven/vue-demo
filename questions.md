### element directive中的bind方法不执行？
```js
Vue.elementDirective('zen-element-directive', {
        bind: function () {
            console.log(this);
//            alert(111)
        },

        update: function(){
            console.log('sss');// can not run
        }
    });
```