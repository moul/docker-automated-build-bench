FROM busybox

RUN mkdir -p /a        \
 && env > /a/env.txt   \
 && date > /a/date.txt \
 && cat /a/date.txt

RUN mkdir -p /b        \
 && env > /b/env.txt   \
 && date > /b/date.txt \
 && cat /b/date.txt

RUN mkdir -p /c        \
 && env > /c/env.txt   \
 && date > /c/date.txt \
 && cat /c/date.txt
