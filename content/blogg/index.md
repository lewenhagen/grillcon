---
views:
    main:
        data:
            class: blog

    block-about: false
    article-toc: false

    blog-list:
        region: main
        template: default/blog-list
        sort: 2
        data:
            meta: 
                type: toc
                items: 7
                orderorder: desc

    blog-toc:
        region: sidebar-right
        template: default/blog-toc
        sort: 2
        data:
            meta: 
                type: toc
                items: 4
                orderorder: desc

...
GrillCon Blogg
===========================

Om GrillCon och relaterat.
