# openalias-badges

Today, I'll show you how to create a cute openalias badge to include on your github page, personal website, or anywhere else that supports html tags.
We will be using shields.io The service respects your privacy, but if you feel the need you can self-host: https://github.com/badges/shields/

![Example](https://img.shields.io/static/v1?label=Monero&message=donate&color=orange&logo=monero&link=monero:donate.getmonero.org)


Click the link below to see what it looks like. If you're on mobile you can click the badge and your phone will open up monerujo or cake wallet, with the donate.getmonero.org openalias autopopulated. Of course if you do not have openalias setup with your own domain you can specify a monero address.


  https://img.shields.io/static/v1?label=Monero&message=donate&color=orange&logo=monero&link=monero:donate.getmonero.org


To create your own, all you need to do is change the link param in the url above. If you have an openalias id you can include it.


  &link=monero:888tNkZrPN6JsEgekjMnABU4TBzc2Dt29EPAvkRxbANsAnjyPbb3iQ1YBRk1UXcdRsiKc9dhwMVgN5S9cQUiyoogDavup3H


Refresh the page to regenerate your own badge.


Now that your badge has been generated, let's copy the html tag to be used on another site.


Right click the white space of the website, then click view page source. Copy the entire line and paste within another html page.
https://img.shields.io/static/v1?label=Monero&message=donate&color=orange&logo=monero&link=monero:donate.getmonero.org

If you would like to include in your github page use markdown:

  !\[Example\]\(https://img.shields.io/static/v1?label=Monero&message=donate&color=orange&logo=monero&link=monero:donate.getmonero.org)
  
  
Other cryptocurrencies are supported

![Bitcoin Example](https://img.shields.io/static/v1?label=Bitcoin&message=donate&color=yellow&logo=bitcoin&link=btc:1FhnVJi2V1k4MqXm2nHoEbY5LV7FPai7bb)
https://img.shields.io/static/v1?label=Bitcoin&message=donate&color=yellow&logo=bitcoin&link=btc:1FhnVJi2V1k4MqXm2nHoEbY5LV7FPai7bb
  
  
  Be aware that your mobile wallet won't notify you of an incoming transaction at this address.
  To remedy this, you can utilize this project that you will need to setup on your own computer: https://github.com/apprises/apprise-transactions
