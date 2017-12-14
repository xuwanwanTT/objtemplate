## template


### css

* 单行文本溢出隐藏省略号

  ```
  .hide-word-one {
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    word-break: normal;
  }
  ```
* 文字渐变

  ```
  background: linear-gradient(to bottom, red, blue);
  -webkit-background-clip: text;
  color: transparent;
  ```
* 修改滚动条
  ```
  wrap::-webkit-scrollbar {/*滚动条宽度*/
    width:
    height:
  }
  wrap::-webkit-scrollbar-thumb {/*滚动条里面小方块*/
    border-radius: 
    box-shadow: inset 0 0 5px rgba(0,0,0,0.2);
    background: 
  }
  wrap::-webkit-scrollbar-track {/*滚动条里面轨道*/
    box-shadow: inset 0 0 5px rgba(0,0,0,0.2);
    border-radius: 
    background: 
  }
  ```
