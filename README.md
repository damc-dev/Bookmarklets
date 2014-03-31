Custom Bookmarklets
============

#### My collection of custom bookmarklets http://damc-dev.github.io/bookmarklets/

### [Toggle Hide/Show Laravel Docs Side Bar Navigation](laravelDocs_hideNav.html)

```
javascript: (function () {
    if (document.documentElement.contentEditable === false || document.designMode === 'off') {
        document.body.contentEditable = 'true';
        document.designMode = 'on';
        $('#docs').hide();
        $('#docs-content').css('float', 'left');
        void 0;
    } else if (document.documentElement.contentEditable === true || document.designMode === 'on') {
        document.body.contentEditable = 'false';
        document.designMode = 'off';
        $('#docs').show();
        $('#docs-content').css('float', 'right');
        void 0;
    }
})();
```
