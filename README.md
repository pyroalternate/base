
# astro

astro is a web proxy front-end that features support for both Palladium and Rhodium along with having a built-in game and movie library


[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)


## Deployment

[![Deploy to Heroku](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/heroku.svg)](https://heroku.com/deploy/?template=https://github.com/pyroTM/astro)

[![Run on Replit](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/official/replit.svg)](https://replit.com/github/pyroTM/astro)


  
```
Choose one of the Hosting Providers Above.

Create a Netlify Account along with a freenom account. 

Register a domain on Freenom (They Are Free).

Once you have registered one go to manage domain and then to NameServers

Go to Netlify and click the add domain button and put in the domain you just got from freenom.

Hit Add Domain and Change the NameServers on the Freenom to the Ones displayed on Netlify

Repl.it:

Once you have added your domain to netlify, go back to replit and hit the pencil icon in the top right and put in the domain you want to use for the domain

Copy the CNAME Record Value that it gives you. Put that into netlify as a CNAME record and the Name as @. 

Once you have done that hit link domain and give it a couple seconds. Now the Front-End Should be Linked

Heroku: 

For Custom Domains with heroku you will need a credit card for verification

Once you do that you do that you can go to the settings tab and hit the Custom Domain Button, 

Put in your freenom domain and copy the CNAME Value it gives you. 

Put that into your Netlify Panel as a CNAME Record with the name as @ and the value as the one you just copied.


```


Once you've gotten the Front-End hosted you will need to host 2 backend proxies.

Palladium and Corrosion. 


```
https://github.com/BinBashBanana/Corrosion-Heroku

https://github.com/LudicrousDevelopment/Palladium

Go to these link and deploy it on one of the hosting services that are provided.

Then follow the instructions from earlier on how to link a custom domain to them.

Once you've done this go to the go.download.js file in the index_files directory and replace the url in there with the url for the one you just created.

Go the Games.json file and do the same.




```

Once you've done this you will be done and left with a working self-hosted instance of astro.
## Appendix

astro has gone open-source because of multiple reports being filed against me and astro itself threatening legal action. It has become too risky to run this website and so I have released the source.


## Acknowledgements

 - [Titanium Network](https://github.com/titaniumnetwork-dev)
 - [Ludicrous Development](https://github.com/LudicrousDevelopment)
 - [Fog Network](https://github.com/FogNetwork)


## FAQ

Q: "I don't know how to do this plsss hlep me"

A: "Figure it out idc, its not hard"

