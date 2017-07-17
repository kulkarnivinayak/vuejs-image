# Vue Image :zap:

+ This is [on GitHub](https://github.com/vinayakkulkarni/vue-image)  so let me know if I've b0rked it somewhere, give me a star :star: if you like it :cheers:

### :white_check_mark: Install :ok_hand:
``` npm i vue-flashcard```

### :white_check_mark: Usage :mortar_board:
- Add it to your component  :tada:

```javascript
import vueImage from 'vue-image';

export default {

components : { vueImage }

}
```

### :white_check_mark: Example :four_leaf_clover: 

```html
<vue-image 
alt="Alt Text for the Image" 
name="name"
maxWidth="100px"
maxHeight="100px">
</vue-image>
```
### :white_check_mark: :book: Props: 
+ `id` (ID for html `input`) [default: "name"]
+ `name` (ID for html `input`) [default: "name"]

+ `maxWidth` (Max Width for Image Container)  [default: "200px"]
+ `maxHeight` (Max Height for Image Container)  [default: "200px"]
+ `paddingBottom` (Padding Bottom between Image and Button) [default: "5px"]