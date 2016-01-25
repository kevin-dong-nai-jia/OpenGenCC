# C Container Collection

## Synopsis

A collection of **high-performance** containers implemented by standard C macros.

## Example

```C
cc_dllst(msg, char*);
cc_dllst_iter(msg_iter, msg);

cc_dllst_push_back(msg, "Hello everyone:\n");
cc_dllst_push_back(msg, "Welcome to C Container Collection Project!\n");

cc_dllst_trav(msg_iter, msg)
    printf("%s", ***msg_iter);

cc_dllst_dealloc(msg);
```

## Macros List

* [dllst container](http://people.cs.nctu.edu.tw/~dongnj/C-Container-Collection/doc/macros%20list.html) - in development

* dcarr container

## Contributor

Kevin Dong Nai Jia <<kevin.dong.nai.jia@gmail.com>>

## License

This project is distributed under GPLv2 or later.
