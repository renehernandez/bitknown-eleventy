# bitKnown-eleventy

BitKnown is a responsive theme focused on features to make easier to write programming posts to be used with eleventy

## Features

* Prism Syntax Highlight
* Include MathJax for math writing  
* Mobile first approach
* Font Awesome home page Social Link Icons (easily configurable by code injection in the admin area)
* RRSSB Extraordinary Social Sharing Buttons  

This theme is currently used at [bitsofknowledge](https://bitsofknowledge.net).

## Configuration

No need to configure Prism or RRSSB buttons.

To add Left Navigation Menu links simply add the links in your Navigation Admin Area. They may be useful for static pages (AboutMe for example) or for shortcut to your (best) post tags.

BitKnown comes with a default favicon generated with Real Favicon Generator. If you want to add your favicon you can generate your own (with Real Favicon Generator) and place downloaded files inside the assets/img/favicons BitKnown directory.

Font Awesome Home Page Social Link Icons are disabled by default, but they are easily configurable with Blog Header Code Injection inside your Ghost Admin Area.

```javascript
// to enable Social Link Icons add the social_link object
// with the pair key/value -> social_network/link
// NB: the key is used to include the right icon from Font Awesome
// (you can include any Font Awesome icon)

// Example1: default social network icons
var social_link = {
    'twitter': 'twitter_url',
    'linkedin': 'linkedin_url',
    'github': 'github_url',
    // you can add more icons
}
</script>
```

## Copyright & License

See [License](LICENSE)
