# jekyll-hux-theme

>clean style theme

![Screenshot](/screenshot.jpg)

## 参考

* [Huxpro](https://github.com/Huxpro/huxpro.github.io)
* [jekyll-search](https://github.com/androiddevelop/jekyll-search)

## Installation

>make sure that you have already installed `ruby`, `jekyll`, [jekyll-installation](http://wiki.jikexueyuan.com/project/jekyll/installation.html)

1. To install a theme, first, clone it to your dir

    ```
    $ git clone git@github.com:stuarthua/jekyll-hux-theme.git
    $ gem install jekyll-paginate rouge
    ```

2. Then, custom config file `_config.yml`:
    
    ```
    # Site settings
    title: Stuart Hua's Blog
    auther: Stuart Hua
    SEOTitle: Stuart Hua's Blog
    header-img: img/home-bg.jpg
    email: stuarthua.cn@gmail.com
    description: "关于技术、产品、生活 | Stuard Hua, Engineer"
    keyword: "产品, 技术, 生活"
    url: "https://blog.stuarthua.com"              # your host, for absolute URL
    baseurl: ""         # for example, '/blog' if your blog hosted on 'host/blog'


    # SNS settings
    RSS: true
    # weibo_username: 339719222
    # zhihu_username: stuarthua
    github_username: stuarthua
    twitter_username: stuarthua_sir
    facebook_username: stuarthua.sir
    # linkedin_username:  firstname-lastname-idxxxx


    # Friends settings
    friends: [
        {
            title: "Stuart Hua",
            href: "https://blog.stuarthua.com"
        },{
            title: "Github",
            href: "https://github.com"
        }
    ]


    # Disqus settings
    # disqus_username: stuarthua


    # Netease settings
    # netease_comment: false


    # Analytics settings
    # Baidu Analytics
    # ba_track_id: 15604eac1992a89871cd85f2cd425d50

    # Google Analytics
    # ga_track_id: 'UA-55082727-2'            # Format: UA-xxxxxx-xx
    # ga_domain: stuarthua.com


    # Google Adsense settings
    # google_ad_client: 'ca-pub-6137478455292280'

    # Sidebar settings
    sidebar: true                           # whether or not using Sidebar.
    sidebar-about-description: "Rethink to be Better!"
    sidebar-avatar: /img/avatar-stuart.jpg  # use absolute URL, seeing it's used in both `/` and `/about/`
    ```

3. Config `about` on `/_includes/about/zh.md`, `/_includes/about/en.md`
    
## License

This project is licensed under the [MIT license](http://opensource.org/licenses/MIT).
