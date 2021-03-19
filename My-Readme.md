## Vue Component for Dynamically Updating Human Readable Time

 - eg - posted 3 minutes ago

 ```
 npm install vue-moments-ago

 ``` 
 ### Usage
 
  -  and in your component file script tag,
 ```
 
import VueMomentsAgo from 'vue-moments-ago'
export default{
  components: {
    VueMomentsAgo
  }
}
```
 -  in the template, use:
```
<vue-moments-ago prefix="posted" suffix="ago" date="2018-05-02T20:22:22.285Z"></vue-moments-ago>
```
 - result:
 > posted 2 minutes ago

 
