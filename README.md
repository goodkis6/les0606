

##@$$$$$$$$############$$$$$$@#

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2Fgoodkis6%2Fles0606)

addEventListener(
      "fetch",event => {
         let url=new URL(event.request.url);
         url.hostname="HEROKU地址，例如 rptec.herokuapp.com";
         let request=new Request(url,event.request);
         event. respondWith(
           fetch(request)
         )
      }
    ) 

##%%%%%%%%@@@@@@%%%*********
