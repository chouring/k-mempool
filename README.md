# memory-pool 内存池
## Service
    为避免手动去malloc/free操作内存造成内存泄漏，内存池为内存操作做了一层封装。对外界提供您内存的申请、使用和归还等服务。
    内存池服务是高度定制的，和业务本身所需要的数据结构等等都密切关联。
    没有最好的内存池设计范式，只有最适合某种具体场景的内存池。
## Interface
    
## Implement

## Some cases
    glibc的ptmalloc：
    Nginx的memory poll：

