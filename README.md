### cobweb
---
https://github.com/stewartmckee/cobweb/

https://rubygems.org/gems/cobweb

https://github.com/create3000/cobweb

```
gem install cobweb
gem 'cobweb'
```

```ruby
crawler = Cobweb.new(:follow_redirects => false)
crawler.start("http://www.google.com/")

crawler.get("http://www.google.com/")
crawler.head("http://www.google.com/")

crawler = CobwebCrawler.new(:cache => 600)
statistics = crawler.crawl("http://www.pepsico.com")

crawl = CobwebCrawlHelper.new(options)
```

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <link rel="stylesheet" type="text/css" href="http://code.create3000.de/latest/dist/x_ite.css"/>
    <script type="text/javascript" src="http://code.create3000.de/x_ite/latest/dist/x_ite.min.js"></script>
    <style>
    X3DCanvas {
      width: 768px;
      height: 432px;
    }
    </style>
  </head>
  <body>
    <X3DCanvas src="path/to/your/X3D/world.x3d">
      <p>Your browser may not support all features required by X_ITE!</p>
    </X3DCanvas>
  </body>
</html>

<X3DCanvas src="world.x3d">
  <p>Current stock price: $3.15 +0.15</p>
</X3DCanvas>
<X3DCanvas src="world.x3dv">
  <img src="images/clock.png" />
</X3DCanvas>
```

