# hello-word

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


## Sample add script
Can add script as a component, or simple, add script as a component's partial:

HelloWorld.vue
```
<script type="text/javascript" charset="utf-8" async defer>
    !function(e,t,n,a,c,s,o){e.FirstContact=c,e.fcSrc="https://first-contact.jp/assets/js/firstcontact.js",e[c]=e[c]||function(){(e[c].q=e[c].q||[]).push(arguments)},e[c].l=1*new Date,s=t.createElement(n),o=t.getElementsByTagName(n)[0],s.async=1,s.src=fcSrc,o.parentNode.insertBefore(s,o)}(window,document,"script",0,"firstcontact");
    firstcontact("0f9aa7cc-87b2-11e7-bb31-be2e44b06b34");
</script>
```
