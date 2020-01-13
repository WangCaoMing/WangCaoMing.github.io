# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## 代码示例

``` java tab="Java"
public class Main {
    public static void main(String[] args) {
        Sustem.out.println("hello world");
    }
}
```

``` kotlin tab="Kotlin"
class Main {
    compain object {
        fun main(args:Array<String>) {
            println("hello world")
        }
    }
}
```

hello: excuse me?


``` json tab="json"
{
    "item1": 0,
    "value1": "hello",
    "value2": "中文也能正常显示哦"
}
```

``` yaml tab="yaml"
item1: 0
value1: "hello"
value2: "中文也能正常显示哦"
```


## other style

!!! warning " FBI Warning"
    **Do not** look this items, because if you look this items, you will be killed!
    
    |hah|houhou|
    | ---- | ---- |
    |hello|world|


??? note "title"
    概要, 概要, 概要.


## Images

![ballon](./index_images/ballon_flying.jpg "10*200")


## Local Videos

<iframe src="./index_images/video_sample.mp4" width="720" height="1280" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## tables 

|name|age|gender|
| -- | -- | -- |
|王萌|28|男|


## 流程图


!!! note "hello"
    ```flow
    st=>start: Start:>http://www.google.com[blank]
    e=>end:>http://www.google.com
    op1=>operation: My Operation
    sub1=>subroutine: My Subroutine
    cond=>condition: Yes
    or No?:>http://www.google.com
    io=>inputoutput: catch something...

    st->op1->cond
    cond(yes)->io->e
    cond(no)->sub1(right)->op1
    ```


## 脚注

这是一个脚注[^1]


[^1]: [脚注内容](https://www.baidu.com)