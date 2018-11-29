# Hugo Apps Theme
[![GitHub stars](https://img.shields.io/github/stars/gonapps/hugo-apps-theme.svg?style=flat-square)](https://github.com/gonapps/hugo-apps-theme/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/gonapps/hugo-apps-theme.svg?style=flat-square)](https://github.com/gonapps/hugo-apps-theme/fork)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://raw.githubusercontent.com/gonapps/hugo-apps-theme/master/LICENSE)

Hugo apps theme

## Installation
From the root of your website
```bash
mkdir -p themes
cd themes
git clone https://github.com/gonapps/hugo-apps-theme
```
From config.toml of your site
```toml
theme = "hugo-apps-theme"
```

## Creating a page
```bash
hugo new about.md
#hugo new about.html
```
```bash
hugo new apps/myapp.md
#hugo new apps/myapp.html
```
```bash
mkdir apps/myapp
touch apps/myapp/index.html
touch apps/myapp/app.js
touch apps/myapp/app.css
```

## Configuration

### Front Matter
- title(string): title for your page
- weight(integer): weight of your page, used for sorting
- full(boolean): whether your page is full page or not
- enableDisqus(boolean): wheter your page uses disqus or not, even though this value is true you cannot enable disqus for full page
- img(string): logo image for your page

### config.toml
- baseURL(string): base url of your site
- hasCJKLanguage(boolean): whether you support CJK language or not
- disqusShortname(string): disqus short name
- googleAnalytics(string): google analytics tracking id
- title(string): title of your site
- copyright(string): copyright of your site
- [params]avatar(string): avatar image url of index page of your site
- [params]author(string): your name at index page
- [params]info(string): info string below your name at index page
- [[menu.main]]name(string): name of menu item
- [[menu.main]]url(string): url of menu item
- [[menu.main]]weight(integer): weight of menu item, used for sorting

## Features
* Responsive
* Disqus
* HighlightJS
* Google Analytics
* Open Graph

### Contribution
Fork this repository and create an PR to dev branch.

## Inspired by
This theme is inspired by following themes:<br/>
[Hugo Coder](https://github.com/luizdepra/hugo-coder)

## License
Licensed under the [MIT](https://opensource.org/licenses/MIT) License.<br/>
See the [LICENSE](https://raw.githubusercontent.com/gonapps/hugo-apps-theme/master/LICENSE) file for more details.
