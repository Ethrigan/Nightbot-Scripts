# Nightbot-Scripts
Scripts para Nightbot Twitch

<pre>
!chuva	$(eval a=['bleedPurple ','coryngCoracao ',':heart: '];x=a[Math.floor(Math.random()*a.length)];x.repeat(20))


!dolar_euro	$(eval a=$(urlfetch json https://economia.awesomeapi.com.br/last/USD-EUR);" US$ 1,00 / EUR$ " + parseFloat(a["USDEUR"]["high"]).toFixed(2).replace(".",","))	

!dolar_real	$(eval a=$(urlfetch json https://economia.awesomeapi.com.br/last/USD-BRL);"US$ 1,00 / R$ " + parseFloat(a["USDBRL"]["high"]).toFixed(2).replace(".",","))	


!euro_real	$(eval a=$(urlfetch json https://economia.awesomeapi.com.br/last/EUR-BRL);"EUR$ 1,00 / R$ " + parseFloat(a["EURBRL"]["high"]).toFixed(2).replace(".",","))		 

!horas	No Brasil são $(time Brazil/East "H:mm") e em Portugal são $(time Europe/Lisbon "H:mm")

</pre> 
