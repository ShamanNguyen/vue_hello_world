<template>
    <div id="first_contact"></div>
</template>

<script>
import postscribe from 'postscribe'
export default {  
  name: 'JSComponent',
  mounted: function () {
    postscribe('#first_contact', `<script type="text/javascript" charset="utf-8" async defer">
        !function(e,t,n,a,c,s,o){e.FirstContact=c,e.fcSrc="https://first-contact.jp/assets/js/firstcontact.js",e[c]=e[c]||function(){(e[c].q=e[c].q||[]).push(arguments)},e[c].l=1*new Date,s=t.createElement(n),o=t.getElementsByTagName(n)[0],s.async=1,s.src=fcSrc,o.parentNode.insertBefore(s,o)}(window,document,"script",0,"firstcontact");
        firstcontact("0f9aa7cc-87b2-11e7-bb31-be2e44b06b34");
    <\/script>`)
  }
}
</script>