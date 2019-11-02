关于css 
要写组件不能写纯css文件，会用css预处理语言
less  scss 

使用scss 有一个风格要遵守： BEM 风格
什么是 BEM？
block:块   .block
element:元素    .block__element
modifier：修饰符  .block--modifier

.box{


  &__element{
  
  }

  &--modifier{

  }

}