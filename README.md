﻿#### 使用方式
通过v-animated传入动画的class，建议配合animate.css更加方便

#### 使用方式

以animate.css为例

```
//main.js

import animated from 'animated'

Vue.use(animated);


//index.vue

<div v-animated="{className : 'animated bounceIn'}"></div>


//app.vue
<style>

 @import animate.css;
 
</style>


```


