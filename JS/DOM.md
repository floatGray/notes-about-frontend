# DOM

文档对象模型

- 将网页的源代码文档抽象成一个个对象，最基础的是节点，例如HTML元素节点，文本节点，注释节点，然后整个文档就可以形成树结构，有各种继承关系
- ![image-20220907134853473](C:\Users\朱敏\AppData\Roaming\Typora\typora-user-images\image-20220907134853473.png)

- Document 节点表示的整个载入的网页，它的实例是全局的 document 对象，它是 DOM 的 **入口点** ，可以从 document 开始去访问任何节点元素；

- DOM中的node的一些常见属性：`innerHTML、textContent、nodeName、tagName`

- 元素的全局属性-hidden

- 元素的attribute，有标准下的以及自定义的，attribute有几个通用操作，并且名字是大小写不敏感，获取的返回值是字符串

- 元素的属性property,标准的attribute在对应的对象中都有property对应，修改property同时会改变attribute，修改attribute同时会改变property。

  ```javascript
  let obj = {
  //property
  name:"test"
  }
  ```

- 用class修改style
- `classList`修改class

