# coder
Coder images and templates for Kubernetes on ARM.

# Usage
```
~ $ cd /tmp/
/tmp $ git clone https://github.com/rpersee/coder.git
/tmp $ cd coder/
/tmp/coder $ kubectl -n coder cp templates <coder pod>:/home/coder/
/tmp/coder $ kubectl -n coder exec <coder pod> exec -it -- sh

/home/coder $ coder login <coder url>
/home/coder $ cd templates/<template name>/
/home/coder/templates/<template name> $ coder templates push
```