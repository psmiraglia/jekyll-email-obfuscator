# jekyll-email-obfuscator

Jekyll plugin to obfuscate email addresses. Plugin inspired by a
[@labnol](https://twitter.com/labnol) post (see References).

## How to install and use the plugin

1.  Copy `_plugins/email_obfuscator.rb` under `<siteroot>/_plugins/` and
    `_sass/_email-obfuscator.scss` under `<siteroot>/_sass/`

2.  Append to `<siteroot>/css/main.scss`

        @import "email-obfuscator";

3.  In your site's pages use

        {% email john.doe@example.com %}

## References

*   [Jekyll Plugins](https://jekyllrb.com/docs/plugins/)
*   [How to Hide your Email Address on Web Pages](http://www.labnol.org/internet/hide-email-address-web-pages/28364/)
